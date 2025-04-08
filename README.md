# Wrap text

Usage: `wrap-txt [fmt-options] [file]`

Calls `fmt -u` to reformat text so that paragraphs wrap near the character limit, which
is set to 88 by default. When no file is specified, or when file is -, the text is
obtained from the standard input stream.

Notable fmt options:

-c
: preserve indentation of first two lines

-p STRING
: only reformat lines beginning with STRING, and retain the prefix

-s
: only split long lines, do not refill

-u
: uniform spacing, one space between words, two after sentences

-w N
: maximum line width
