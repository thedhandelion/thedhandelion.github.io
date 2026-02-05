---
layout: post
title: "Improve Gaming Laptop's Battery Life or:"
subtitle: "How to make a gaming laptop actually usable for work"
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [otherComputeryStuff]
comments: false
mathjax: true
author: Dhani White
---

# The Boring Bit Where I Have a Chat

I think one of the most humiliating feelings is being sat in a lecture hall, minding my own business and taking notes on my laptop, when, suddenly, the laptop's fans ramp up to max speed and I watch, in a state of awe (alongside all the other students), as the laptop just takes off towards the ceiling...

<center><img src="https://github.com/thedhandelion/thedhandelion.github.io/blob/main/assets/img/2026-02-02-Make_Gaming_Laptop_Usable/WW_Fly.gif" alt="Breaking Bad - The Fly" width="300" height="170"></center>

...Only for the battery to die after 6 seconds and crash back onto the desk, all my peers pointing and laughing as I run out of the room, laptop clutched under my arms, blinded by the tears in my eyes, then I slip on a banana peel and suddenly all my clothes are gone and my teeth are falling out and I try screaming but I can't make any noise and I'm trapped and everything is dark and scary and I ask myself "what sort of nightmare is this?!"...

Alas, it was no nightmare, but the average Monday feeling during my university lectorials (well, for the first few months anyway). Never a day went by when my £430 HP Pavilion gaming laptop decided _not_ to imitate a [TU-95](https://en.wikipedia.org/wiki/Tupolev_Tu-95) and then proceed to call it a day after 20 minutes of note-taking, punishing me for not bringing the bulky charger. Then, I sit there mindlessly (I mean eagerly, of course...) listening to the lecturer preach their magical technical words I pretend to understand, wondering how on earth everyone else's £150 notebooks can just breeze through a full day of lectures and still have enough juice for a midnight Netflix-binge before it packs up and demands a recharge. 

Look, I get my bargain (especially in 2023) gaming laptop has a 15.6" 144hz display, a Ryzen 5 5600H 6C/12T 3.3GHz processor, a GTX 1650 and 16GB 3200MHz RAM, not to mention an LED keyboard (green, of all colours, but it's okay because I colour-themed it to [Zygarde](https://bulbapedia.bulbagarden.net/wiki/Zygarde), and they have a baby little laptop with no specs and no personality ([Eevee](https://bulbapedia.bulbagarden.net/wiki/Eevee) in comparison), so of course the battery will last longer, but surely, when my laptop is running Word, it shouldn't be sat using up all its resources for it, right? I'll illustrate with a graph I made using MS Paint (it took roughly 80% of my laptop's battery life to make this):

<center><img src="https://github.com/thedhandelion/thedhandelion.github.io/blob/main/assets/img/2026-02-02-Make_Gaming_Laptop_Usable/Amazing_Graph.png" alt="Performance-Resource_Usage" width="300" height="300"></center>

(stuff like running VMs and Games)

Thankfully, however, I'm a nerdy nerd and I did some silly techy stuff to get it to actually last a few hours when i needed it to, while still being able to switch to 'game mode' when I'm back home with the charger in, ready to spend the next 2 hours mindlessly scrolling through games, realising they don't excite me the way they did when i was younger and life was easier, then opting to watch a movie instead... £500 well spent I reckon.

# The Less Boring Bit Where Stuff Actually Gets Done




{: .box-success}
This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/tables/etc.<br/>I also encourage you to look at the [code that created this post](https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/_posts/2020-02-28-sample-markdown.md) to learn some more advanced tips about using markdown in Beautiful Jekyll.

**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

You can use [MathJax](https://www.mathjax.org/) to write LaTeX expressions. For example:
When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
