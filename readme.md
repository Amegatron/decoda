# Decoda v3.0 #

A stand alone lightweight, BBcode style parser class.

## Requirements ##

* PHP 5.2.x
* GeSHI 1.0.8.4 Library (Comes packaged in the Vendors)

## Contributors ##

* "Marten-Plain" emoticons by Mårten Lundin - http://adiumxtras.com/index.php?a=xtras&xtra_id=6920
* GeSHi - http://qbnz.com/highlighter/

## Features ##

* Parses custom code to valid (X)HTML markup
* Setting to make links and emails auto-clickable
* Setting to use shorthand links and emails
* Implements GeSHi for code highlighting
* Implements the ability to censor words
* Support for adding additional user code
* Supports additional attributes for select tags
* Supports the following: bold, italics, underline, alignment, color, font, sup, sub, font size, h1-h6, code (pre), urls, emails, images, divs, lists, quotes, videos

## Unsupported ##

* Placing [code] tags within [code] tags
* URLs that begin with www and not http:// will not be converted (intentional)
* Certain videos are not supported as their embed code does not match the URL
