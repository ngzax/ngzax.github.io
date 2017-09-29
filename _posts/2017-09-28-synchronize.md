---
comments: false
excerpt:  "Using urbit-sync to initialize and synchronize your local filesystem and your mounted urbit pier."
image:
  feature: bars/yellow.jpg
layout:   post
modified:
tags:     [Urbit, DevOps]
title:    synchronize
---

# Announcing [urbit-sync](https://github.com/ngzax/urbit-sync), a small ruby
script to initialize and synchronize your local filesystem and your mounted
urbit pier.

I created this because it was useful for me at this very early stage of urbit's
life. It lets me check out the repos I am working on and not worry about keeping
the files in sync. It also lets me define the packages that I am including in my
base pier setup so when one crashes, getting another one fully  set up is a
single command.

This is the project ~palfun-foslup called "Fancy." ;)


> DISCLAIMER:

>  It is *not* a substitute for an urbit package management system.
>  ~rophex-hashes has been doing some great early work on a prototype for this
>  called urbit-package. See  [this post on
>  fora](https://urbit.org/fora/posts/~2017.9.7..23.20.06..dc47~/) and [the
>  github repository](https://github.com/asssaf/urbit-package).

Please see the linked repo above for full instructions. I'd love to hear your
feedback if you find this useful.
