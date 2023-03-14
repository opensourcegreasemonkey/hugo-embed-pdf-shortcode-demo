---
title: "hugo-embed-pdf demo"
description: "This a demo page for the hugo-embed-pdf-shortcode"
---
### This is a demo page to show the working of the hugo-embed-pdf-shortcode**

#### In the page content just drop the following shortcode 

```
{{ < embed-pdf url="./path/to/your/file.pdf"  > }}
```
#### This shortcode loads the first page and displays pagination

#### Hide pagination

If you wish to hide the pagination use the following attribute
```
{{ < embed-pdf url="./path/to/your/file.pdf" hidePaginator="true"  > }}
```

#### Hide loading spinner

If you wish to hide the loading spinner use the following attribute
```
{{ < embed-pdf url="./path/to/your/file.pdf" hideLoader="true"  > }}
```

{{< embed-pdf url="./hugo-embed-pdf-sample.pdf" hideLoader="false" hidePaginator="false" >}}
