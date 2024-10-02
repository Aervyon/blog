---
title: "Welcome to A Glimpse of Aervyon"
datePublished: Sun Feb 04 2024 16:00:27 GMT+0000 (Coordinated Universal Time)
cuid: cls7ow6mf000n08jwfe076w7l
slug: welcome-to-a-glimpse-of-aervyon
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1707043948598/ee44dbd6-7237-4f5e-90c5-759e87a7ecc6.png
tags: software-development, developer, hello-world

---

Not to mention some security bits, when I can.

Thanks for checkin' out my blog. Below you'll find out why this blog exists, what I'll be posting, and a little bit about me  
... In other words

```go
package main
import "fmt"

func main() {
    fmt.println('Hello World!')
}
```

## Why a blog?

...Why not? Obviously "to post" but like, what's the actual reason here?  
Well, to put it simply. I've wanted a blog since version 3 of my site, and now I *have* one. I wanted somewhere to post my discoveries, the "why" behind some of code, and just little tidbits I find out about security, games, and the like. Even though I am best classified as a junior developer.

### What are these "discoveries?"

Well, they're mostly little nuances I pick up on in software, weird quirks, ways I think you should do xyz (like not using passwords for ssh in 2024). Although, the last one is just my opinion.

Take the following for example:

Folderr uses signed JWT tokens for its authentication, and so I made a bit of a code for `foldcli`[viewable here](https://github.com/Folderr/foldcli/blob/70c263914a0d5e23b423929bb28cf4d02e9207b1/cmd/db.go#L35-L74) that is ***supposed*** to work with jsonwebtoken, at least thats \*my\* understanding of this amount of crypto.

So, that is a little bit about why this blog exists.

Now.

## Just who are you? Why should I trust you?

Well, I'm an undergraduate computer science student, and I've been developing software (mainly websites and APIs) for around 6 years, in my spare time. As to why you should trust me? That's up to you, you can go take a look at all of my public work on [my github](https://github.com/Aervyon), you can ask the people I've worked with (if you can contact them), or you can contact me on [Twitter](https://twitter.com/Aervyon). If you have a business inquiry you can email [aervy@aervyon.com](http://mailto:aervy@aervyon.com)

\*If you're still reading this wondering "hey what's a Folderr?" you can check out [the Folderr github](https://github.com/Folderr) and [Folderr's Docs](https://folderr.net)