+++
title = "DocDock Theme for Hugo"
description = ""
date = "2017-04-24T18:36:24+02:00"

+++

# Basic Sample Site
[Hugo-theme-docdock {{%icon fa-github%}}](https://github.com/vjeantet/hugo-theme-docdock) is a theme for Hugo, a fast and modern static website engine written in Go. Hugo is often used for blogs, **this theme is fully designed for documentation.**

This theme is a partial porting of the [Learn theme of matcornic {{%icon fa-github%}}](https://github.com/matcornic/hugo-theme-learn).

{{%panel%}}docDock works with a "page tree structure" to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "HugoStructure/_index.md"%}}) {{%/panel%}}

## Main features

* [Search]({{%relref "search/_index.md" %}})
* **Unlimited menu levels**
* [Generate RevealJS presentation]({{%relref "page-slide.md"%}}) from markdown (embededed or fullscreen page)
* Automatic next/prev buttons to navigate through menu entries
* [Image resizing, shadow...]({{%relref "Admin/create-page/page-images.md" %}})
* [Attachments files]({{%relref "Admin/shortcodes/attachments.md" %}})
* [List child pages]({{%relref "Admin/shortcodes/children/_index.md" %}})
* [Excerpt]({{%relref "Admin/shortcodes/excerpt.md"%}}) ! Include segment of content from one page in another
* [Mermaid diagram]({{%relref "Admin/shortcodes/mermaid.md" %}}) (flowchart, sequence, gantt)
* [Icons]({{%relref "Admin/shortcodes/icon.md" %}}), [Buttons]({{%relref "Admin/shortcodes/button.md" %}}), [Alerts]({{%relref "Admin/shortcodes/alert.md" %}}), [Panels]({{%relref "Admin/shortcodes/panel.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "Admin/shortcodes/notice.md" %}}), [Expand]({{%relref "Admin/shortcodes/expand.md" %}})
* [customizable look and feel]({{%relref "HugoStructure/customize-style/_index.md"%}}), [theme style]({{%relref "HugoStructure/customize-style/themestyle.md"%}}), [theme variants]({{%relref "HugoStructure/customize-style/theme-variants.md"%}})



Style "Original"

![](https://raw.githubusercontent.com/vjeantet/hugo-theme-docdock/master/images/tn.png?width=33pc&classes=border,shadow)

Style "Flex"

![](style-flexfull.png?width=33pc&classes=border,shadow)

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it
{{%alert%}}Your modification will be deployed automatically when merged.{{%/alert%}}


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docdock` -- source code is [available here at GitHub {{%icon fa-github%}}](https://github.com/vjeantet/hugo-theme-docDock)

{{% panel theme="success" header="Automated deployments" footer="Netlify builds, deploys, and hosts  frontends." %}}
Automatically published and hosted thanks to [Netlify](https://www.netlify.com/).

Read more about [Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)
{{% /panel %}}

