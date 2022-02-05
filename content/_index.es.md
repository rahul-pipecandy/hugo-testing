+++
title = 'Hugo GitHub Issue #7805 (es)'
date = 2022-02-04T16:04:32-08:00
draft = false
details = 'https://github.com/gohugoio/hugo/issues/7805'
description = "Multilingual bug: relativeURLs=true with multilingual website produces broken relative urls?"
+++
[test.txt](/subdir/test.txt)

PASS: with `relativeURLs = false` this resolves to:

```text
http://localhost:1313/subdir/test.txt 
```

FAIL: with `relativeURLs = true` this resolves to:

```text
http://localhost:1313/subdir/subdir/test.txt
```
