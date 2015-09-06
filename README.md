# Writ

Opinionated, classless styles for semantic HTML.

## Usage

```html
<!DOCTYPE html>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="//writ.cmcenroe.me/1.0.2/writ.min.css">
```

[Full template][template]

Writ is served through the CloudFlare CDN.

[template]: template.html

## Goals

- Drop-in stylesheet
  - No classes
  - No extra elements
- Responsive, without special-casing
- Visually pleasing

## Motivation

<abbr>HTML</abbr> is super easy to write. Markdown is even easier to write and
generate <abbr>HTML</abbr> from. But what does it look like?

<p style="text-align: center;">
  <img alt="Default styles" width="285" src="screenshot/default.png">
</p>

Not very nice, and it gets worse the more there is. Applying the Writ
stylesheet makes it better.

<p style="text-align: center;">
  <img alt="Writ styles" width="285" src="screenshot/writ.png">
</p>

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
