+++
title = 'Test (EN)'
date = 2021-11-12T14:28:20-08:00
draft = true
+++
## Group 1 (Internal)

[posts/post-1](posts/post-1)

[posts/post-1/](posts/post-1/)

[/posts/post-1](/posts/post-1)

[/posts/post-1/](/posts/post-1/)

## Group 2 (Internal)

[posts/post-1?foo=bar](posts/post-1?foo=bar)

[posts/post-1/?foo=bar](posts/post-1/?foo=bar)

[/posts/post-1?foo=bar](/posts/post-1?foo=bar)

[/posts/post-1/?foo=bar](/posts/post-1/?foo=bar)

## Group 3 (Internal)

[posts/post-1#frag](posts/post-1#frag)

[posts/post-1/#frag](posts/post-1/#frag)

[/posts/post-1#frag](/posts/post-1#frag)

[/posts/post-1/#frag](/posts/post-1/#frag)

## Group 4 (Internal)

[posts/post-1?foo=bar#frag](posts/post-1?foo=bar#frag)

[posts/post-1/?foo=bar#frag](posts/post-1/?foo=bar#frag)

[/posts/post-1?foo=bar#frag](/posts/post-1?foo=bar#frag)

[/posts/post-1/?foo=bar#frag](/posts/post-1/?foo=bar#frag)

## Group 5 (Internal when running hugo server, otherwise external)

[http://localhost:1313/posts/post-1](http://localhost:1313/posts/post-1)

[http://localhost:1313/posts/post-1/](http://localhost:1313/posts/post-1/)

[http://localhost:1313/posts/post-1?foo=bar](http://localhost:1313/posts/post-1?foo=bar)

[http://localhost:1313/posts/post-1/?foo=bar](http://localhost:1313/posts/post-1/?foo=bar)

[http://localhost:1313/posts/post-1#frag](http://localhost:1313/posts/post-1#frag)

[http://localhost:1313/posts/post-1/#frag](http://localhost:1313/posts/post-1/#frag)

[http://localhost:1313/posts/post-1?foo=bar#frag](http://localhost:1313/posts/post-1?foo=bar#frag)

[http://localhost:1313/posts/post-1/?foo=bar#frag](http://localhost:1313/posts/post-1/?foo=bar#frag)

## Group 6 (Internal when running hugo, otherwise external)

[https://example.org/posts/post-1](https://example.org/posts/post-1)

[https://example.org/posts/post-1/](https://example.org/posts/post-1/)

[https://example.org/posts/post-1?foo=bar](https://example.org/posts/post-1?foo=bar)

[https://example.org/posts/post-1/?foo=bar](https://example.org/posts/post-1/?foo=bar)

[https://example.org/posts/post-1#frag](https://example.org/posts/post-1#frag)

[https://example.org/posts/post-1/#frag](https://example.org/posts/post-1/#frag)

[https://example.org/posts/post-1?foo=bar#frag](https://example.org/posts/post-1?foo=bar#frag)

[https://example.org/posts/post-1/?foo=bar#frag](https://example.org/posts/post-1/?foo=bar#frag)

## Group 7 (External)

[http://gohugo.io](http://gohugo.io)

[http://gohugo.io/](http://gohugo.io/)

[http://gohugo.io?foo=bar](http://gohugo.io?foo=bar)

[http://gohugo.io/?foo=bar](http://gohugo.io/?foo=bar)

[http://gohugo.io#frag](http://gohugo.io#frag)

[http://gohugo.io/#frag](http://gohugo.io/#frag)

[http://gohugo.io?foo=bar#frag](http://gohugo.io?foo=bar#frag)

[http://gohugo.io/?foo=bar#frag](http://gohugo.io/?foo=bar#frag)

## Group 8 (External)

[https://gohugo.io](https://gohugo.io)

[https://gohugo.io/](https://gohugo.io/)

[https://gohugo.io?foo=bar](https://gohugo.io?foo=bar)

[https://gohugo.io/?foo=bar](https://gohugo.io/?foo=bar)

[https://gohugo.io#frag](https://gohugo.io#frag)

[https://gohugo.io/#frag](https://gohugo.io/#frag)

[https://gohugo.io?foo=bar#frag](https://gohugo.io?foo=bar#frag)

[https://gohugo.io/?foo=bar#frag](https://gohugo.io/?foo=bar#frag)

## Group 9 (External)

<https://gohugo.io>

<https://gohugo.io/>

<https://gohugo.io?foo=bar>

<https://gohugo.io/?foo=bar>

<https://gohugo.io#frag>

<https://gohugo.io/#frag>

<https://gohugo.io?foo=bar#frag>

<https://gohugo.io/?foo=bar#frag>

## Group 10 (External)

https://gohugo.io

https://gohugo.io/

https://gohugo.io?foo=bar

https://gohugo.io/?foo=bar

https://gohugo.io#frag

https://gohugo.io/#frag

https://gohugo.io?foo=bar#frag

https://gohugo.io/?foo=bar#frag

## Group 11 (Other - Don't Assign a Class)

[mailto:john@example.org](mailto:john@example.org)

<mailto:john@example.org>

[file:///test.txt](file:///test.txt)

[something.pdf](something.pdf)

[posts/post-99](posts/post-99)

## Group 12 (Internal - Make sure title is populated)

[posts/post-1 "This is the title"](posts/post-1 "This is the title")

[/ "Home"](/ "Home")

## Group 13 (Internal, same page)

[#frag](#frag)

[/posts/test](/posts/test)

[http://localhost:1313/posts/test](http://localhost:1313/posts/test)

[https://example.org/posts/test](https://example.org/posts/test)
