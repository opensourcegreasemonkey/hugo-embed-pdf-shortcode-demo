---
title: "Multiple pdf embed demo"
description: "This a demo page for the hugo-embed-pdf-shortcode multiple embed"
---
### This is a demo of how to embed multiple pdf with hugo-embed-pdf**

#### In the page content just drop the following shortcode 

```
{{ < embed-pdf url="./path/to/your/file_1.pdf"  > }}
```
#### This shortcode loads the first page and displays pagination


#### In the page content just drop the following shortcode again with another document

```
{{ < embed-pdf url="./path/to/your/file_2.pdf"  > }}
```
### This is the first embed
{{< embed-pdf url="./hugo-embed-pdf-sample-1.pdf" hideLoader="false" hidePaginator="false" >}}


### This is the second embed
{{< embed-pdf url="./hugo-embed-pdf-sample-2.pdf" hideLoader="false" hidePaginator="false" >}}


### This is the third embed
{{< embed-pdf url="./hugo-embed-pdf-sample-3.pdf" hideLoader="false" hidePaginator="false" >}}
