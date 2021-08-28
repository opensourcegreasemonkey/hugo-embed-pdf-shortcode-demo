---
title: "hugo-embed-pdf select page demo"
description: "Demonstrate selected page display"
---

## This is a demo page to show how to render particular page at document load.

### In the page content just drop the following shortcode 

```
{{ < embed-pdf url="./path/to/your/file.pdf" renderPageNum="2" > }}
```

{{< embed-pdf url="./hugo-embed-pdf-sample.pdf" hideLoader="false" hidePaginator="false" renderPageNum="2" >}}