# PATH TRAVERSAL - July 17, 2026

## Topics learnt:
1. What is path traversal?
2. Reading arbitrary files through path traversal
3. Nested traversal sequences
   * . . . . // - revert to simple traversal sequences when the inner sequence is stripped
   * . . **. . /**/ becomes . . / after stripping
4. URL Encoding
   * %2e%2e%2f (dot-dot-slash) or double encoding %252e%252e%252f to sneak past input validation filters.
