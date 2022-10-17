# HTML Docs

## Tag Syntax

- Elements Surroundeed in angle Brackets
- Usually hava start & end Tag
- Some Tags close themselves (Remnant of XHTML)

```html
## Start and End Tag
<h1>HTML</h1>
<p>This is my first website</p>
## Self Closing Tags
<br>,<hr> Valid in HTML5
 <br /> Valid in HTML5 & XHTML
```

## DocType

- All HTML documents must start with a <!DOCTYPE> declaration.
- The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.
- In HTML 5, the declaration is simple:

```html
<!DOCTYPE html>
```

### Older HTML Documents

In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition).

HTML 4.01:

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```

XHTML 1.1:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
```

- The <!DOCTYPE> declaration is NOT case sensitive.

#### Examples

```HTML
<!DOCTYPE html>
<!DocType html>
<!Doctype html>
<!doctype html>
```
