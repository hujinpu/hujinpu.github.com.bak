---
layout: post
title: "Don't block the event loop!"
date: 2012-03-27 22:52
comments: true
categories: ruby
tags: [ruby, eventmachine]
---

为下次ruby tuesday准备的ppt。

重点如下：

* 怎么理解并发突破了xxx (CXXXK problem)
* non-blocking i/o 与 asynchronous 的区别
* reactor pattern
* TCP is a stream
* read eventmachine source code
* fiber

如果你想你的程序方便扩展并且non-blocking i/o，请绝不要堵塞你的event loop。

<div style="width:595px" id="__ss_12172128"> <strong style="display:block;margin:12px 0 4px"><a href="http://www.slideshare.net/hujinpu/dont-block-the-event-loop" title="Don’t block the event loop!" target="_blank">Don’t block the event loop!</a></strong> <iframe src="http://www.slideshare.net/slideshow/embed_code/12172128" width="595" height="497" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe> <div style="padding:5px 0 12px"> View more <a href="http://www.slideshare.net/" target="_blank">presentations</a> from <a href="http://www.slideshare.net/hujinpu" target="_blank">hujinpu</a> </div> </div>

