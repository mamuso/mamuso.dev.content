---
title: Imperfection
slug: imperfection
category: note
date: '2026-09-28'
---

Sometime around 2008, maybe 2009, I spent a lot of time on the YayHooray forum. I vividly remember a thread about the [My Famicase Exhibition](https://famicase.com/chronicle/index.html), an event run by a retro game shop in Tokyo called [METEOR](https://super-meteor.com/). Designers from all over were making labels for games that didn't exist, hoping to get picked for the show.

I never submitted one. But for years, Famicase labels kept popping up on Dribbble and Behance. Almost twenty years later, [the exhibition is still going](https://famicase.com/).

<figure>
  <img src="/assets/posts/imperfection-myfamicaseexhibition.png" alt="Sixteen My Famicase Exhibition entries: colorful Famicom cartridges with labels for games that do not exist" width="2398" height="1634" loading="lazy" />
  <figcaption>A few Famicase entries</figcaption>
</figure>

A few months ago, I pitched a couple of friends on a personal site made out of fake cartridges. They were very supportive, which didn't help. I knew it would be a lot of work and a lot to learn, and when I did the math, I had to put it away.


---

Not long after, I hit a slow patch. I needed to stay busy, and there was a perfectly good idea sitting on a shelf. So every night, I gave it thirty minutes, sometimes an hour. Less to build a site, more to get some of the muscles back. Physical therapy, but with shaders.

Those nights added up, and one day I had a proof of concept. It was technically lacking and rigid as fuck, but it was "done," and naturally, I lost interest again. Instead of fixing it, I went back to the labels, just to learn a bit more about light and materials. I even tried animating them, which sounded way cooler in my head. Around the same time, I started a new job, and the cartridges finally had a real use: announcing it.


<Gallery layout="row" columns="2" caption="Labels, labels, labels">
  <img src="/assets/posts/imperfection-blender.png" alt="The model in blender" width="1920" height="1080" loading="lazy" />
  <img src="/assets/posts/imperfection-labels.png" alt="Famicom cartridges with labels for past jobs" width="1920" height="1080" loading="lazy" />
  <video src="/assets/posts/imperfection-labels.mp4" alt="Label mocks" width="1920" height="1080" loading="lazy"></video>
  <video src="/assets/posts/imperfection-animated.mp4" alt="Animated labels" width="1280" height="720" loading="lazy"></video>
</Gallery>

Something about Cursor.

<Gallery layout="row" width="text">
  <video src="/assets/posts/imperfection-cursor.mp4" alt="Joining Cursor" width="1920" height="1080" loading="lazy"></video>
</Gallery>


About a month later, I made peace with the idea that the cartridges would make a good hero for the site. It worked, but it felt very rigid. I even joked about prototyping it in real life, and the analog version already had better spacing.

The joke stuck. Real life isn't perfect. My site was, and that was the problem.

<Gallery layout="row" caption="">
  <img src="/assets/posts/imperfection-analog.jpg" alt="Analog version" width="1920" height="1280" loading="lazy" />
  <img src="/assets/posts/imperfection-magenta.jpg" alt="First Hero draft" width="1890" height="1404" loading="lazy" />
</Gallery>


So I started breaking it on purpose. The cartridges became an accordion, and every time it opens, they land at a slightly different angle. Then came stickers. Anyone who has stuck a sticker on top of another one knows it never lines up. Now it never does, and it misses differently every time. Then I spent an unreasonable number of evenings on frosted plastic. Nobody asked for frosted plastic.

Along the way, I also answered the question of where "mamuso" comes from: Manuel Muñoz Solera, squished together. And yes, all of this was still happening in short sessions, thirty-five minutes at a time.


<Gallery layout="row" columns="2">
  <img src="/assets/posts/imperfection-frosted.jpg" alt="Frosted materials" width="1920" height="1080" loading="lazy" />
  <img src="/assets/posts/imperfection-xai.png" alt="xAI imperfection" width="1164" height="1164" loading="lazy" />
  <video src="/assets/posts/imperfection-famicordion.mp4" alt="The Famicordion" width="800" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-mamuso.mp4" alt="Hero" width="1330" height="720" loading="lazy"></video>
</Gallery>

---

Once the hero was roughly where I wanted it, I moved on to the photo gallery and brought the same rule with me: if it's a photo, it should act like one. Prints pile up, slide around, and never sit perfectly straight. Goncy suggested that the top photo of a stack should follow your cursor, like running a finger over a real pile of prints. I stole that immediately. I also got so into view transitions that I publicly asked someone to take them away from me. Then I opened the site on my phone, had a small crisis, and spent a few more nights making it work there too.

<Gallery layout="row" columns="2">
  <video src="/assets/posts/imperfection-mobile.mp4" alt="Mobile" width="720" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-mobile-2.mp4" alt="Hero" width="1280" height="720" loading="lazy"></video>
</Gallery>



After that, it was mostly small stuff, my favorite kind. A few people pointed out that you should be able to blow on the cartridges, like with the real ones. They were right, so now you can: long-press a cartridge, allow the microphone, and blow. The results are about as scientific as they were in 1988. The photos on the homepage took a few tries. I started with something big and interactive and landed on something flatter, but still playful. Even the "more" links got some attention.

Splitting photos and notes also exposed something: I hadn't written anything in two years. The least I could do was make the gap look intentional.



<Gallery layout="row" columns="2">
  <video src="/assets/posts/imperfection-stack.mp4" alt="Photo stacks" width="1630" height="1400" loading="lazy"></video>
  <video src="/assets/posts/imperfection-view-transitions.mp4" alt="Gallery transitions" width="1040" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-photo-module-v1.mp4" alt="Photo module home exploration" width="1190" height="720" loading="lazy"></video>
  <video src="/assets/posts/imperfection-photo-module-final.mp4" alt="Photo module home final" width="1762" height="720" loading="lazy"></video>
</Gallery>

---

At that point, the only things left were the OG images and this post. So, obviously, I took another detour and used Apple MusicKit to build something silly and completely unnecessary.

<Gallery layout="row" columns="2">
  <img src="/assets/posts/imperfection-og-images.png" alt="OG images" width="2396" height="1332" loading="lazy" />
  <video src="/assets/posts/imperfection-music.mp4" alt="Hero" width="1200" height="720" loading="lazy"></video>
</Gallery>


Making things imperfect turned out to be so much fun that I was a little sad to finish. But the OG images are done, and you're reading the post.

Thanks for reading.

---

<details>
  <summary>The whole build, in tweets</summary>
  <ol>
    <li>Jul 6 · <a href="https://x.com/mamuso/status/2073980800723538214">work / play</a></li>
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
