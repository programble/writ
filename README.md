# Writ

Simple CSS for simple writing.

Writ provides simple, elegant styles for HTML 5 semantic elements. No classes,
and no extra `div`.

## The Problem

It's pretty easy to start writing something in HTML, especially with HTML 5:

```html
<!DOCTYPE html>
<title>Hello, World!</title>
<meta charset="utf-8">

<h1>Writ</h1>
<p>Simple CSS for simple writing.</p>
```

This is what it looks like:

![Default styles](screenshot/default.png)

Not too bad, but it really starts to be inadequate with more content and
various elements.

[eventual screenshot of reference page with default styles]

## A Solution

By adding the Writ stylesheet, the same HTML can look a lot better:

```html
<link rel="stylesheet" href="https://cmcenroe.me/writ/writ.min.css">
```

![Writ styles](screenshot/writ.png)

## Caveats

Writ is designed for modern, standards compliant browsers only. There are no
compatibility hacks. Writ is tested on the latest stable releases of Safari,
Chrome and Firefox.

## License

Copyright © 2015, Curtis McEnroe <curtis@cmcenroe.me>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
