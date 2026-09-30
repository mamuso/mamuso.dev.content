---
title: Imperfection
slug: imperfection
category: note
date: '2026-09-30'
---

If you're reading this, I regret to inform you that I finally published an update to my personal site. I guess I made it.

This is a personal site, and I've seen the traffic. Nobody was waiting for this. And I had a blast anyway.

Fair warning, this is a long one. I needed something to space out the images.

---

### The Shelf

A few months ago, I pitched a couple of friends this idea of turning my site into a shelf of fake game cartridges, one per job. They were very supportive, which is exactly what you don't want when you're trying to talk yourself out of something.

None of this is original. Around 2008, maybe 2009, I spent a lot of time on the YayHooray forum, where I found the [My Famicase Exhibition](https://famicase.com/chronicle/index.html). A retro game shop in Tokyo called [METEOR](https://super-meteor.com/) invites designers to make labels for games that don't exist, and picks the best for a show. I never submitted anything, so technically I'm undefeated. Still, for years, every time a Famicase label popped up on Dribbble or Behance, I had to stop and look, like running into an ex who's doing really well. [The exhibition is still going](https://famicase.com/).

<figure>
  <img src="/assets/posts/imperfection-myfamicaseexhibition.png" alt="Sixteen My Famicase Exhibition entries: colorful Famicom cartridges with labels for games that do not exist" width="2398" height="1634" loading="lazy" />
  <figcaption>A few Famicase entries</figcaption>
</figure>

Anyway, at the time I was too busy, so the cartridges went on the shelf where I keep the ideas I'll never work on. It's a big shelf.

---

### Creative therapy, but with shaders

Then it was the end of June, my last day at what I considered the best job I'd ever have. I was in London, surrounded by family and friends who were thrilled for me, and I was the only one in the room not having a great time. I felt like I was walking out on an incredible team. I kept replaying months of decisions in my head, and I couldn't shake the feeling that I'd let a bunch of folks down.

And to be clear, I was (am!) extremely lucky. I had an incredible job waiting for me, and I knew it. My brain just didn't care, and I couldn't feel any of it yet.

I had time on my hands and a perfectly good idea collecting dust on a shelf. So I started giving it thirty minutes every night, sometimes an hour. Mostly, I wanted to clear my head and remember what making something for fun felt like.

---

### Felt cute, might share later

Those nights added up, and one day the cartridge escaped Blender and landed on a web page. It was technically lacking and about as stiff as a LinkedIn post, but it was "done."

I tried to make a fun label for each job. Some were easy. I'm very proud of the [Windows 95 floppy disk reference](https://archive.org/details/windows-95_202208). Then there was Azure DevOps, which is not a phrase that sounds fun in any font.

I spent a lot of nights trying to make plastic look like plastic. I even tried animating them, which in my head was a Pixar short and on screen was very much a PowerPoint transition.

None of it was exceptional, which made it very fun and easy to share. Nobody expects anything from a work in progress, including me.

<Gallery layout="row" columns="2" caption="Labels, labels, labels">
  <img src="/assets/posts/imperfection-blender.png" alt="The model in blender" width="1920" height="1080" loading="lazy" />
  <img src="/assets/posts/imperfection-labels.png" alt="Famicom cartridges with labels for past jobs" width="1920" height="1080" loading="lazy" />
  <video src="/assets/posts/imperfection-labels.mp4" alt="Label mocks" width="1920" height="1080" loading="lazy"></video>
  <video src="/assets/posts/imperfection-animated.mp4" alt="Animated labels" width="1280" height="720" loading="lazy"></video>
</Gallery>

Staring at the same little idea every night for two weeks makes it a lot less exciting (I think this is true of most things). I also knew that making it actually run well on a real website, on a real phone, for real people, was going to take way more nights than I had in me.

On the other hand, a fake Famicom cartridge is a pretty good way to announce a real job. All that work finally had somewhere to go.

<Gallery layout="row" width="text" caption="Joined Cursor!">
  <video src="/assets/posts/imperfection-cursor.mp4" alt="Joining Cursor" width="1920" height="1080" loading="lazy"></video>
</Gallery>

---

### Tilted

If you overshare long enough and your friends are kind enough, you eventually run out of excuses. So I gave in and started turning the cartridges into the hero of the site.

This part was not glamorous. Most nights went into making the model smaller and fighting the renderer, which fought back harder than I expected and, honestly, won most rounds.

I opened and closed those cartridges so many times (to test something, to debug something, to test the fix for the thing I'd just debugged) that I started to resent them, which is a weird way to feel about your own homepage.

<Gallery layout="row" caption="The analog version already had better spacing">
  <img src="/assets/posts/imperfection-analog.jpg" alt="Analog version" width="1920" height="1280" loading="lazy" />
  <video src="/assets/posts/imperfection-famicordion.mp4" alt="The Famicordion" width="800" height="720" loading="lazy"></video>
</Gallery>

So I added a little random rotation, just enough that every click landed a bit differently, mostly so I could stand to look at them. That was supposed to be it. Instead, I started to obsess over giving everything a slightly different angle, a little wobble. Death to the straight line. Make it random.

Then Cursor joined SpaceXAI, which, among many more important things, meant new stickers! Have you ever tried to place a sticker on top of another? It's always a little off. On the cartridge, the black sticker never quite covers the colorful one underneath, it misses differently every time, and I LOVE it.

The more imperfect it got, the more it felt like mine (and like me).


<Gallery layout="row" columns="2">
  <video src="/assets/posts/imperfection-mamuso.mp4" alt="Hero" width="1330" height="720" loading="lazy"></video>
  <img src="/assets/posts/imperfection-xai.png" alt="xAI imperfection" width="1164" height="1164" loading="lazy" />
  <img src="/assets/posts/imperfection-frosted.jpg" alt="Frosted materials" width="1920" height="1080" loading="lazy" />
</Gallery>

---

### Laptop first, laptop second, laptop third

I'd love to tell you I designed this mobile first. I did not. Then one night, weeks into the project, I opened it on my phone and had a small, private crisis.

The composition that looked so good on a laptop did not survive being turned vertical. And it had to work with thumbs, which are a lot less precise and a lot more impatient than a mouse. Tap to open, swipe to the next one, and please, whatever you do, don't hijack the scroll.

Once it worked, the most obvious feature in the world became impossible to ignore. If you grew up with a Nintendo, you know the ritual. The game doesn't start, you pull the cartridge out, you blow on it like it's a birthday cake, you put it back in, and you believe. Everybody did it, nobody remembers who taught them, and it (probably) never helped. [A few people](https://x.com/johnbai/status/2097368445616591278) pointed out that the site should let you do it too, and they were right.

So, on your phone, open a cartridge, long-press it, allow the microphone (nothing gets recorded or sent anywhere, I promise), and blow. Maybe not on the train. The cartridge tilts back and shakes in the wind. Yelling at it works too, which is more than you can say for most software. The results are about as scientific as they were in 1988.

<Gallery layout="row" columns="2">
  <video src="/assets/posts/imperfection-mobile.mp4" alt="Mobile" width="720" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-mobile-2.mp4" alt="Cartridges on mobile" width="1280" height="720" loading="lazy"></video>
</Gallery>


---

### Paper cuts

I'm obsessed with photography, so naturally I started the photo gallery the way I start anything I'm a little nervous about, which is by making it extremely boring. A grid, some stacks. Very respectable. It looked like the photo section of a hotel website.

But then I got drunk on view transitions. And while I was at it, I worked on yet another shader so the little info card next to each photo feels like actual paper. A bit of grain, a crease here, a folded corner there, a dent from who knows what, all slightly different for every photo. Nobody will ever notice it, and I think about it daily.

When I shared it, the feedback was clear. It needed to feel [more tactile](https://x.com/mamuso/status/2097550338878513302), like a pile of real prints. Now you can pick the prints up, drag them around, and leave them wherever you want.

It was a really good time.

<Gallery layout="row" columns="2">
  <video src="/assets/posts/imperfection-stack.mp4" alt="Photo stacks" width="1630" height="1400" loading="lazy"></video>
  <video src="/assets/posts/imperfection-view-transitions.mp4" alt="Gallery transitions" width="1040" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-photo-module-v1.mp4" alt="Photo module home exploration" width="1190" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-photo-module-final.mp4" alt="Photo module home final" width="1762" height="720" loading="lazy"></video>
</Gallery>

---

### Bike shedding and yak shaving

You've probably figured this out by now, but this site has been done for a while.

I started to work on it to stretch some creative muscles and keep my head busy, and it worked a little too well, because once it was done, the fun part was over. It's like getting to the last two episodes of a show you love and starting to ration them. One a week, max, and only if you've earned it.

So I did what any reasonable person would do, which is invent reasons to keep going.

Splitting photos and notes into their own pages exposed something embarrassing. I hadn't written anything on this site in two years. Two! The notes section looked like an apartment where someone had clearly moved out and left the lights on. The least I could do was make the gap look intentional.

<Gallery width="text" layout="row">
  <img src="/assets/posts/imperfection-left-blank.png" alt="intentionally left blank" width="2004" height="344" loading="lazy" />
</Gallery>

Then the "more" links needed to be funnier, so I made them funnier.

The footer looked a little sad, so now it shows the last song I listened to. You can judge my design and my music taste without clicking a thing.

<Gallery width="text" layout="row">
  <video src="/assets/posts/imperfection-music.mp4" alt="Footer showing the last song I listened to" width="1200" height="720" loading="lazy"></video>
</Gallery>


And then, of course, OG cards, the little preview image that shows up when you share a link. No respectable site ships without proper OG cards, right? Right?

<img src="/assets/posts/imperfection-og-images.png" alt="OG images" width="2396" height="1332" loading="lazy" />

Eventually, I ran out of excuses. Again.

Making things imperfect was so much fun that I'm a little sad it's over. The cartridges finally came off the shelf, which means there's an empty spot on it now, and I'm trying very hard not to look at it.

If anything on this site stops working, you know what to do.

---

<details>
  <summary>The whole build, in tweets</summary>
  <ol>
    <li>Jul 6 · <a href="https://x.com/mamuso/status/2073980800723538214">work / play</a></li>
    <li>Jul 7 · <a href="https://x.com/mamuso/status/2074347034753339804">I may have been a little too excited for this one 😂</a></li>
    <li>Jul 8 · <a href="https://x.com/mamuso/status/2074877542407033270">Trying something a little different for AzDo</a></li>
    <li>Jul 9 · <a href="https://x.com/mamuso/status/2075173680825724960">Old game! 10/10, would absolutely play again.</a></li>
    <li>Jul 12 · <a href="https://x.com/mamuso/status/2076206249927139444">A few labels still need work, but it’s really starting to come together.</a></li>
    <li>Jul 13 · <a href="https://x.com/mamuso/status/2076521410651128255">Animated labels sounded way cooler in my head…</a></li>
    <li>Jul 14 · <a href="https://x.com/mamuso/status/2077081103475900591">Joining Cursor</a></li>
    <li>Aug 19 · <a href="https://x.com/mamuso/status/2089971237812568274">nothing says wip like a trusty magenta border</a></li>
    <li>Aug 21 · <a href="https://x.com/mamuso/status/2090592499811459127">the analog version already has better spacing</a></li>
    <li>Aug 21 · <a href="https://x.com/mamuso/status/2090830808902942973">the famicordion</a></li>
    <li>Aug 24 · <a href="https://x.com/mamuso/status/2091917464171159796">sticker on sticker</a></li>
    <li>Aug 28 · <a href="https://x.com/mamuso/status/2093381716484538724">Frosted materials</a></li>
    <li>Sep 2 · <a href="https://x.com/mamuso/status/2095184248466772114">getting my website ready 35m at a time</a></li>
    <li>Sep 7 · <a href="https://x.com/mamuso/status/2096995450201292855">page transitions and stacks</a></li>
    <li>Sep 8 · <a href="https://x.com/mamuso/status/2097364642800787532">it needs to work on mobile</a></li>
    <li>Sep 9 · <a href="https://x.com/mamuso/status/2097550338878513302">Goncy’s stack idea</a></li>
    <li>Sep 9 · <a href="https://x.com/mamuso/status/2097720505587601623">take the view transitions API away from me, please</a></li>
    <li>Sep 10 · <a href="https://x.com/mamuso/status/2098090420752531791">the QA department hard at work</a></li>
    <li>Sep 14 · <a href="https://x.com/mamuso/status/2099641931102101990">adding this photo module so you can immediately undo my design decisions</a></li>
    <li>Sep 15 · <a href="https://x.com/mamuso/status/2099901814108008549">intentionally left blank (twice)</a></li>
    <li>Sep 16 · <a href="https://x.com/mamuso/status/2100257933217181892">say more</a></li>
    <li>Sep 21 · <a href="https://x.com/mamuso/status/2102069120519090357">I think this is the one</a></li>
    <li>Sep 23 · <a href="https://x.com/mamuso/status/2102793887006024167">you can now* judge my design and music taste in a single scroll</a></li>
    <li>Sep 27 · <a href="https://x.com/mamuso/status/2104278087093682638">1200×630 png has been achieved internally</a></li>
  </ol>
</details>
