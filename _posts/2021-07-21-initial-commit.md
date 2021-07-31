---
title: Initial Commit - Hello World!
description: Process of building this blog
sharing: true
article_header:
  type: cover
  image: 
    src: /assets/Initial Commit - Hello World!/Hello World!.gif
image: /assets/Initial Commit - Hello World!/Hello World!.gif
---

# nuqneH! :wave:

{% include lazyload.html image_src="/assets/nuqneH!.gif" image_alt="nuqneH!" image_title="nuqneH!" %}

At last, it is time for the first post. Welp! Here goes nothing :cold_sweat:.

<!--more-->

## Introduction

People tell me that I'm good at getting my mind across to another person :smirk:. So I **finally** decided to do some form of writing to use this skill.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Write.gif" image_alt="Write" image_title="Write" %}

Back in 2020, I had attempted to get a podcast up and running that was similar to what this blog is about. However, it never reached fruition due to multiple reasons, like the need for investing in mics as the audio quality was bloody bad, a lack of time, or just an obvious lack of interest and drive to follow through :weary:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Can't Afford.gif" image_alt="Can't Afford" image_title="Can't Afford" %}

Now, cut to April 2021, the world has stopped due to the pandemic, school is online, I'm stuck at home, bored, prime time to start something new if you asked me :dizzy_face:. So I started to see how I could do this.

Of course, I could've gone the orthodox way of WordPress hosted on some service with a domain name for it. But that would be too boring now, wouldn't it? :smirk:

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Boring.gif" image_alt="Boring" image_title="Boring" %}

So I started looking for alternatives that were cheap, preferably free of cost, and of course, interesting. I considered hosting WordPress on [Google Cloud](https://cloud.google.com/){:target="_blank"} or [AWS](https://aws.amazon.com/){:target="_blank"} or something for free. I also considered hosting it on my network on my Raspberry Pi 4. 

I would, in the end, come across a static site generator named [Jekyll](https://jekyllrb.com/){:target="_blank"}, and would choose to host it on [GitHub Pages](https://pages.github.com/){:target="_blank"} :satisfied:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/jekyll-og.png" image_alt="Jekyll" image_title="Jekyll" %}

It was perfect as I hadn't the **slightest** idea about Jekyll, nor did I have any previous substantial web development experience :grimacing:. So I started vigorously searching for information about it on the web. YouTube, reddit, [stackoverflow](https://stackoverflow.com/questions/tagged/jekyll){:target="_blank"}, Quora, and various forums, especially this one called [Jekyll Talk](https://talk.jekyllrb.com/){:target="_blank"}, I looked through them all :mag:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Search.gif" image_alt="Search" image_title="Search" %}

If you're like me and are a complete noob at this, you should checkout [this YouTube playlist](https://www.youtube.com/playlist?list=PLWzwUIYZpnJuT0sH4BN56P5oWTdHJiTNq){:target="_blank"} by Bill Raymond. I found it extremely helpful :exclamation:.

## How I chose Jekyll

### Why static websites?

Now, why a static website? Good question.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Great Question.gif" image_alt="Great Question" image_title="Great Question" %}

- The **main** reason is that while static websites are limited, they are extremely simple to create. And I did not need any of this extra functionality that comes with dynamic websites for my blog. Most people don't. Moreover, since it is less complex, there are fewer things to break :relieved:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Break.gif" image_alt="Break" image_title="Break" %}

- Static websites generally load much faster than [WordPress](https://wordpress.org/){:target="_blank"} dynamic websites, but that gap has been nearly closed now, especially due to caching. I didn't want to deal with the hassle of caching.

- WordPress requires substantially more maintenance. Despite using WordPress managed hosting, you're still expected to do some basic core maintenance. You don't need to do that on static websites as they don't have any underlying software to maintain :clap:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Less Work.gif" image_alt="Less Work" image_title="Less Work" %}

- The sheer popularity of WordPress means that countless plugins may not be of the required quality. They may be plagued with compatibility issues, etc. Finding good compatible plugins may be time-consuming.

- You have more degree of control over your website as you have direct access to your code. This will satisfy your inner control freak :smiling_imp:. This will be all the merrier if you have no qualms about getting your hands dirty with code. 

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Control.gif" image_alt="Control" image_title="Control" %}

- Static websites, in the right hands, can be extremely flexible.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Flexible.gif" image_alt="Flexible" image_title="Flexible" %}

- Although this is debatable, dynamic websites are often at a higher risk of being attacked because they interact with the end-user :scream_cat:. In case, for whatever reason, someone decides to DDoS my static website. If it is taken down, all I have to do is re-deploy my website and everything is back to normal. This is **significantly** more complex with dynamic websites.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Dare.gif" image_alt="Dare" image_title="Dare" %}

- Static websites are generally better for SEO as they're easier to be crawled.

- Static HTML pages are cached well, so they're well suited to be used with CDNs which make them even faster.

### Why Jekyll?

Now, why did I choose Jekyll particularly? That's an even better question.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Trick Question.gif" image_alt="Trick Question" image_title="Trick Question" %}

- Jekyll and GitHub Pages seamlessly integrate. GitHub has [outstanding documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll){:target="_blank"} on how to do this.

- It is a blog-aware static site generator, which is exactly what I need it for.

- It is beginner-friendly.

- It has amazing support and a wide range of plugins via Ruby Gems.

- It has many active contributors, so it's not dying out on me anytime soon.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Die.gif" image_alt="Die" image_title="Die" %}

- Lastly, and probably the main reason, I had no idea about the other static site generators :trollface:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/No Idea.gif" image_alt="No Idea" image_title="No Idea" %}

  When I found Jekyll, I had already wasted so much time before, that I just went ahead with it without researching anything else. Also, I think I found Jekyll first because it was the most popular generator among bloggers.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Hugo.png" image_alt="Hugo" image_title="Hugo" %}

Not gonna lie, now that I've discovered [Hugo](https://gohugo.io/){:target="_blank"}, I do have this itch to try and use that instead of Jekyll for this. Maybe I'll do that **soon**. Now, getting back to the topic at hand.

## Creation of the blog

### Theme selection

Finally, after all that searching, I decided on my first step - starting with a Jekyll theme. I thought that it would be easier to start with something pre-built and then change it later. Don't be mistaken, Jekyll themes are nothing like WordPress themes. They're nowhere close in terms of simplicity. It's pretty hard to customise your theme as you have to learn how the theme is built and only then can you customise it to suit your needs. Apart from the very basics, each theme is built in a different way using different functionality and different liquid structures. The guides you find online which teach how to add functionality rarely work seamlessly due to these differences. But that is what we live for, don't we?Troubleshooting, troubleshooting, and more troubleshooting :sob:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Not Easy.gif" image_alt="Not Easy" image_title="Not Easy" %}

So after some more scouring through the web, I found the theme that I wanted to use. It was a theme named [Contrast](https://github.com/niklasbuschmann/contrast){:target="_blank"}. It looked exactly as I envisioned after a few minor colour and font changes, but it was a great big **mistake** :frowning:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Huge Mistake.gif" image_alt="Huge Mistake" image_title="Huge Mistake" %}

Now, why is that a mistake? It's because I had never considered the functions of the theme, only the aesthetics. It looked gorgeous, but it lacked some functionalities that I required like Google Analytics, archive, tags, etc. All of which I was adding to it, but it was just too time-consuming. Additionally, while I was leisurely browsing GitHub (yeah I tend to do that :joy:), I found this theme called [TeXt](https://github.com/kitian616/jekyll-TeXt-theme){:target="_blank"}. It had a lot of functionality that I was adding to my original one, plus it looked pretty similar too. It was a pretty compelling offer :eyes:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Offer.gif" image_alt="Offer" image_title="Offer" %}

After a **LOT** of brainstorming, I finally decide to start over again with TeXt. Except, it wasn't really starting over as it already had most of the functionality that I had added into my original one, and then some :relieved:. So I forked it and started working on it.

### First changes

The first changes were obviously colour and font. I loved the dark theme. I didn't have to spend much time doing these changes as I had already decided which colour and font I wanted to use. 

### Logo and Favicon

Then, I decided to do my logo and favicon. I wanted some software that was easy to learn and open-source, as I was a **big fan** of the open-source ideology :raised_hands:. I decided on using [Inkscape](https://inkscape.org/){:target="_blank"}. It fit the bill perfectly, and I was happy with how my logo turned out. I used [RealFaviconGenerator](https://realfavicongenerator.net/){:target="_blank"} to generate my favicon. It did the job flawlessly. 

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Perfection.gif" image_alt="Perfection" image_title="Perfection" %}

### E-mail newsletter

Next, I wanted to add an E-mail newsletter system to my blog. I seemingly had found the perfect tool called [Buttondown](https://buttondown.email/){:target="_blank"}. It was cool, but I would ultimately end up ditching it for [Mailchimp](https://mailchimp.com/){:target="_blank"} because it had the functionality of scraping my newsletter based on my RSS feed into the design that I had made. That was **exactly** what I wanted. It would automatically do this and send it to my subscribers regularly every week. Ain't that convenient? Moreover, it also had the option for pop-ups which I thought was neat.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Neat.gif" image_alt="Neat" image_title="Neat" %}

### Lazy loading

I then decided that I want to add [lazy loading](https://en.wikipedia.org/wiki/Lazy_loading){:target="_blank"} to my blog. Lazy loading aka asynchronous loading is a design pattern in web development where it defers the loading of certain objects until it is required. In simpler words, it loads certain objects like media, etc, only when you scroll down to it and is visible to the reader. As you can imagine, it makes the website more efficient by decreasing the load times. And better load times improve your SEO. Now if you know anything about me, you would know that I chase efficiency like my life depends on it. So it was a win-win :v:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Absolute Win.gif" image_alt="Absolute Win" image_title="Absolute Win" %}

To add this, I used [Lazysizes](https://github.com/aFarkas/lazysizes){:target="_blank"}. I referred to [this guide](https://ranvir.xyz/blog/lazy-loading-your-images-in-jekyll-blog-improving-page-speed/){:target="_blank"} for help.

### SEO-tag

Next, I added [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag){:target="_blank"}. This is an amazing plugin for Jekyll that I think must be used by absolutely everybody. It even does your [OpenGraph](https://ogp.me/){:target="_blank"} and Twitter cards for you. **Brilliant!** I didn't require many references as the instructions on its GitHub was sufficient :smile_cat:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Brilliant.gif" image_alt="Brilliant" image_title="Brilliant" %}

### Math Typesetter

TeXt came with [MathJax](https://www.mathjax.org/){:target="_blank"} in-built. However, I wanted to replace it with [KaTeX](https://katex.org/){:target="_blank"} for a few reasons. Mainly, KaTeX was lighter and faster than MathJax. You can check out the comparison of speed between MathJax and KaTeX [here](https://www.intmath.com/cg5/katex-mathjax-comparison.php){:target="_blank"}. I referred to [this article](https://gendignoux.com/blog/2020/05/23/katex.html){:target="_blank"} by Guillaume Endignoux for installing it onto my website. It explains it succinctly.

### Read time

I wanted to add an indicator for showing the reading time of the articles that I post, because, of course, **time is of the essence** :hourglass:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Time.gif" image_alt="Time is of the essence" image_title="Time is of the essence" %}

I referred to [this article](https://excessivelyadequate.com/posts/ert.html#fnref:0minutes){:target="_blank"} for help.And with the help of some knowledgeable folks at [Jekyll Talk](https://talk.jekyllrb.com/t/how-do-i-get-the-content-from-my-articles/6220){:target="_blank"} (that's my query) who aided me in understanding the rather complex liquid in my website, I managed to add it to my website. You can check out the code on [my GitHub](https://github.com/ScienceToKeepAnIon/ScienceToKeepAnIon.github.io/blob/4242693e14b4f37ac60ed78642104e3306744fa6/_includes/read_time.html){:target="_blank"}.

### Hamburger menu

I did think of adding a hamburger menu but later decided against it as I had no real need for it. My header didn't have too many links to warrant using a hamburger menu. And it nicely shifted itself when the screen shrank.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Nice.gif" image_alt="Nice" image_title="Nice" %}

### Jekyll-admin

I later added [Jekyll-admin](https://jekyll.github.io/jekyll-admin/){:target="_blank"} for a CMS-style GUI. The instructions on [its GitHub](https://github.com/jekyll/jekyll-admin){:target="_blank"} were helpful.

## Optimisation of blog

Now, it's time for good ol' **optimisation** :zap:.

### Build Speed

When compared to Hugo or Gatsby, Jekyll build speed is super slow :snail:. But it is getting better slowly and steadily.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Slow.gif" image_alt="Slow" image_title="Slow" %}

So what to do to decrease build time? Simple. Don't build what's not required. Exclude files that are not required in the _config.yml.

Use the incremental build built into Jekyll. But do be careful because some stuff won't work with the incremental build option. For example, my read time option doesn't work as it has to be rebuilt every time the content of the post has changed to update the reading time. This doesn't happen in incremental build. Or else, you could just let Jekyll build only the last few posts. You can do this using `jekyll serve --watch --limit_posts 10`. This only builds the last 10 posts. Neat innit?

### Load Speed

Page load speed is arguably more important than build speed as it affects your SEO score :racehorse:. 

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Speed.gif" image_alt="Speed" image_title="Speed" %}

Images take substantial time to load. The priority for image file types should be SVG > PNG > JPEG. SVG is extremely lightweight if used correctly, and lightweight is your friend.

Minify your HTML. It means minimising the code and markup to increase webpage load speed. The comments in your code and the whitespaces are not required for the end-user, they're there only for readability and your convenience. But they take time to load. I used [this](http://jch.penibelst.de/){:target="_blank"} handy layout to minify my HTML and referred to [this](https://blog.webjeda.com/compress-html-jekyll/){:target="_blank"} article for help. Be **careful** with minifying as certain objects (like my search) might break on minifying.

I used [GTmetrix](https://gtmetrix.com/){:target="_blank"}, [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/){:target="_blank"} and [WebPageTest](https://www.webpagetest.org/){:target="_blank"} to test the loading of my webpage :chart_with_upwards_trend:.

I used the [Mobile-Friendly test](https://search.google.com/test/mobile-friendly?utm_source=mft&utm_medium=redirect&utm_campaign=mft-redirect){:target="_blank"} to check if my page was mobile-friendly and the [Rich Results Test](https://search.google.com/test/rich-results){:target="_blank"} to test for special features in Google Search results.

## Finishing touches

For some finishing touches, I added my RSS to various RSS directories. At last, the website was complete :triumph:.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/Yes!.gif" image_alt="Yes!" image_title="Yes!" %}

# Conclusion

That was my journey in creating this blog. Hope I could convince you to follow in my footsteps and create a blog using Jekyll. C'mon, if someone like me could motivate himself to go through all this to create a blog, then you can very well do it too.

{% include lazyload.html image_src="/assets/Initial Commit - Hello World!/C'mon.gif" image_alt="C'mon" image_title="C'mon" %}

What do y'all think about Jekyll? Would you choose WordPress over it? If so, why? Would you choose Hugo or any other generator over it? If so, why? Anything that I'm unaware of or I have missed in this article? Did you start a blog of your own? Tell me what's on your mind. I would **love** to talk.

{% include lazyload.html image_src="/assets/Tell Me.gif" image_alt="Tell Me" image_title="Tell Me" %}

I'm thinking of writing about 'religion' as the first part of the driving forces behind scientific advancement series next week. Stay tuned!

{% include lazyload.html image_src="/assets/Stay Tuned.gif" image_alt="Stay Tuned" image_title="Stay Tuned" %}