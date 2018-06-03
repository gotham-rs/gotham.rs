---
layout: post
title: The State of Gotham
date: 2018-05-31 15:00 +1000
categories: blog
author: Shaun Mangelsdorf
---

**Update (2018-06-04)**: The call for maintainers has been answered. Stay tuned.

---

When we set out to build Gotham, we had some main ideas that helped to shape it:

* A framework that runs on stable Rust, taking advantage of as much as possible
  of what it offers;
* A framework that allowed us to write applications in the way **we** wanted to
  write them;
* A learning experience and experiment in what we could achieve with the goal of
  building a useful web framework.

We're excited about the framework we've built and the ideas we've put into it,
but have paused to consider Gotham’s present and future position and want to
share these thoughts with the community.

#### Major changes in the ecosystem

The current state of the web ecosystem in Rust is one of flux. There are some
major efforts underway which will improve the future of both web and
asynchronous applications (in no particular order):

* Tokio reform and its wider adoption by the community
* The experimental Futures 0.2, and the upcoming Futures 0.3
* Wider adoption of the http crate
* Hyper 0.12
* Continued evolution of the Rust language

Gotham is at a point now where everything is back on the table, including the
design choices based on what was stable in Rust at the time we started Gotham in
early 2017.

#### A call for maintainers

In recent months, development activity in Gotham has decreased. There are two
major reasons that we’ve been less active as maintainers:

* Waiting and watching for the changes above to be ready for our adoption; and
* Family, paid work, and other commitments that have demanded more of our time.

The second of these points is sufficiently demanding that we don’t have enough
time to maintain Gotham as a serious contender in the Rust web framework arena.

We’d like to “pass the torch” to some new maintainer(s) who are willing to give
Gotham the attention it deserves. If that’s you, please reach out to one of us
via Gitter or email (`@bradleybeddoes`' and `@smangelsdorf`'s email addresses
are in the project’s Git history).

#### What’s next for Gotham?

Gotham, as it stands, isn’t going away. The repositories, crates and chat
channel will remain. We’ll continue accepting security fixes and releasing patch
versions if necessary, until we determine what’s next.

Feature contributions are still welcome, but may be delayed until a current or
future maintainer has time to consider its relevance, impact on the wider
framework, and the contribution itself.

Beyond that, it’s up to the next maintainer(s) to set the next priorities. We’re
happy to provide our own thoughts on what that should be.

Bradley and Shaun
