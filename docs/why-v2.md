# Why rewrite Comic CMS from scratch?

[Comic CMS V1](https://github.com/RitzyMage/comic-cms) was a hobby side project written using Nuxt and express. I read a lot of webcomics and noticed that none of them had very good interfaces. I started this as a UI design experiment and completed it because I liked it. 

The main goal was to make reading comics a better experience. I think that it succeeded in that. 

However, the first version has a few problems. The biggest one is the install size. Nuxt has over 600 dependencies in its tree alone. With the other modules I was using, the app installed over 1400 modules and took up over a gigabyte of storage space. On my small server, this was a lot and I ended up removing the example site from my server. I didn't expect many people to use Comic CMS, I certainly hoped it was something _I_ could use. 

Unfortunately, that's not a simple problem to solve without re-writing the entire app using a different framework. Since it's a small app and I'm just doing this for fun anyway, I think that's a wise decision. Next.js looks like a great choice and I want to learn that anyway, so I plan on doing that.

The details on what I'm doing are in [goals.md].
