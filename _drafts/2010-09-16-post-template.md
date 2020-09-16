---
layout: page
title: "Post template - Title"
description: "Post template - Description"
image:
  url: /img/blog/blog-placeholder.jpg
  hide: false
tags:
  - Labs64
author:
  name: Labs64
  url: https://www.labs64.com
sitemap:
  images:
canonical:
---

[Markdown](https://daringfireball.net/projects/markdown/) allows you to write using an easy-to-read, easy-to-write plain text format, which then converts to valid HTML post.

This [post template](https://raw.githubusercontent.com/Labs64/www.labs64.com/gh-pages/_drafts/2010-09-16-post-template.md) includes sample content to guide you on how to create content on [Labs64](https://www.labs64.com).

## HEADERS
---

# This is an H1 header

## This is an H2 header

### This is an H3 header

#### This is an H4 header

##### This is an H5 header

###### This is an H6 header

## TEXT FORMATTING
---

*Emphasized* text (var 1)

_Emphasized_ text (var 2)

**Strong** text (var 1)

__Strong__ text (var 2)

~~Strikethrough~~ text => this doesn't work as per 02.2016

Citations:

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.

> *Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.*

Custom Styles:

Assign Class{:class="blog-center"}

## LISTS
---

Unordered (bulleted) list (var 1)

* labs64.com
* www.labs64.com
* labs64.de

Unordered (bulleted) list (var 2)

- labs64.com
- [www.labs64.com](https://www.labs64.com "Innovative License Management Solution")
- labs64.de

Unordered (bulleted) list (var 3)

+ labs64.com
+ www.labs64.com

  list item - second line

+ labs64.de

Ordered (bulleted) list (var 1)

1. labs64.com
2. www.labs64.com
3. labs64.de

Nested lists

1. labs64.com
2. www.labs64.com
  1. Flexible Licensing Models
  2. Easy Setup and Integration
  3. Cross-Platform Licensing
3. labs64.de

## LINKS
---

This a [link](https://www.labs64.com)

This a [link with title](https://www.labs64.com "Innovative License Management Solution")

Reference-style links: [NetLicensing][NLIC] and [Labs64][2] were developed by [Labs64][3]

[NLIC]: https://www.labs64.com   "Labs64 NetLicensing - Innovative License Management Solution"
[2]: https://www.labs64.de        "Labs64 - Innovations Delivered"
[3]: https://www.labs64.com       "Labs64 - Innovations Delivered"

## IMAGES
---

Image with title and alt tags

![Labs64 QR Code](/img/netlicensing-promo-04.png "Labs64 NetLicensing Lifecycle")

## CODE
---

Syntax highlighting (var 1)

{% highlight ruby %}
require 'netlicensing'
res = NetLicensing.validate("1234-5678-90")
puts res.to_html
{% endhighlight %}

Syntax highlighting (var 2)
{% highlight java %}
final ValidationParameters validationParameters = new ValidationParameters();
validationParameters.put(productModuleNumber, "paramKey", "paramValue");
ValidationResult validationResult = LicenseeService.validate(context, licenseeNumber, productNumber,
licenseeName, validationParameters);
out.writeObject("Validation result for created licensee:", validationResult);

context.setSecurityMode(SecurityMode.APIKEY_IDENTIFICATION);
validationResult = LicenseeService.validate(context, licenseeNumber, productNumber, licenseeName,
validationParameters);
context.setSecurityMode(SecurityMode.BASIC_AUTHENTICATION);
out.writeObject("Validation repeated with APIKey:", validationResult);
{% endhighlight %}

see also [List of supported languages and lexers](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers)
