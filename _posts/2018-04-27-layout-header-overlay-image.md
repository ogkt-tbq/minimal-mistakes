---
title: "Header Image Overlay"
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_url: "https://unsplash.com"
categories:
  - ブログ構築
tags:
  - image
  - Jeykill
  
---

### header imageを指定して、ブログタイトルをimageの上に記載させる

You can use it by specifying the opacity (between 0 and 1) of a black overlay like so:

![transparent black overlay]({{ "/assets/images/mm-header-overlay-black-filter.jpg" | relative_url }})

```yaml
excerpt: "This post should [...]"
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "More Info"
  cta_url: "https://unsplash.com"
```

Or if you want to do more fancy things, go full rgba:

![transparent red overlay]({{ "/assets/images/mm-header-overlay-red-filter.jpg" | relative_url }})

```yaml
excerpt: "This post should [...]"
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  overlay_filter: rgba(255, 0, 0, 0.5)
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "More Info"
  cta_url: "https://unsplash.com"
```
