---
"@biomejs/js-api": patch
---

Fixed `formatContent` computing the formatter's intermediate representation when called with `debug: false`. After successful formatting, the returned `ir` string is empty in this mode.
