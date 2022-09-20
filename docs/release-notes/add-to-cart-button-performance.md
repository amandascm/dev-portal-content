---
slug: "add-to-cart-button-performance"
title: "`Add to cart` button performance"
createdAt: 2020-11-26T18:43:15.322Z
hidden: false
type: "fixed"
---

# img 1

Using external image with HTML tag

<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png?w=360" style="height: 100px; width:100px;"/>

# img 2

Using external image with defaul markdown syntax

![github avatar](https://avatars.githubusercontent.com/u/9919?s=280&v=4)

<div class="badge" id="store-framework">Store Framework</div>
[block:html]
{
  "html": "<br/>"
}
[/block]
Shopping experience was being harmed because of the unexpected extra time needed to redirect users to the Minicart once the `Add to cart` button was clicked on. 

[Our wonderful team deployed a series of performance fixes and small improvements](https://github.com/vtex-apps/add-to-cart-button/pull/50), such as adding a native loading bar to the page, in order to enhance navigation during the shopping experience!
