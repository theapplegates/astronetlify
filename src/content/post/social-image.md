---
title: "Example OG Social Image"
publishDate: "27 January 2023"
description: "An example post for Astro Cactus, detailing how to add a custom social image card in the frontmatter"
tags: ["example", "blog", "image"]
ogImage: "/social-card.png"
---
  ![Hi](https://applegate-paul.mo.cloudinary.net/zoom/train.jpg)
![image2](https://applegate-paul.mo.cloudinary.net/zoom/volvo.jpg)
![test3](https://applegate-paul.mo.cloudinary.net/zoom/wow.jpeg)
![Bye for now](https://applegate-paul.mo.cloudinary.net/zoom/Women-red.jpg)

## Adding your own social image to a post

This post is an example of how to add a custom [open graph](https://ogp.me/) social image, also known as an OG image, to a blog post.
By adding the optional ogImage property to the frontmatter of a post, you opt out of [satori](https://github.com/vercel/satori) automatically generating an image for this page.

If you open this markdown file `src/content/post/social-image.md` you'll see the ogImage property set to an image which lives in the public folder[^1].

```yaml
ogImage: "/social-card.png"
```

You can view the one set for this template page [here](https://astro-cactus.chriswilliams.dev/social-card.png).

[^1]: The image itself can be located anywhere you like.


Some image tests with auto breakpoints and auto format.

![The blossums](https://res.cloudinary.com/paulapplegate-com/image/upload/c_limit/dpr_auto/f_auto,q_auto/w_auto:breakpoints_200_1920_30_15/aedrian-RPokxvk8BCE-unsplash_n9vprs.jpg)

![Hi, snow cars](https://res.cloudinary.com/paulapplegate-com/image/upload/c_limit/dpr_auto/f_auto,q_auto/w_auto:breakpoints_200_1920_30_15/snow-cars_bakzxt-4_abdgsq.jpg)

![Hi](https://res.cloudinary.com/paulapplegate-com/image/upload/c_limit/dpr_auto/f_auto,q_auto/w_auto:breakpoints_200_1920_30_15/hillshire-farm-2_fx2mno.jpg)

![bye](https://res.cloudinary.com/paulapplegate-com/image/upload/c_limit/dpr_auto/f_auto,q_auto/w_auto:breakpoints_200_1920_30_15/automatic-unsplash/142056.jpg)
