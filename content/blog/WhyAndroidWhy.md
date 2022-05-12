---
title: "WhyAndroidWhy"
date: 2022-05-12T17:29:39-04:00
draft: false
---

#Why Android, why?

It’s no secret that the Android Development ecosystem is in a state of flux with its many changes. These changes, in turn, have made learning it a challenge for me. I found myself sifting through opinions explaining how any coding task could be accomplished. On top of that, I faced another problem: should I even use this approach? To illustrate my point, take something like `ViewBinding`. It’s unclear, even after reading tutorials, if it’s worthwhile to use it in a small demo app?
 
When I step back and debug why it’s taken me so long to learn, all the above reasons played a role. There was, though, a larger issue at play which I only realized after some soul searching. In a nutshell, I was learning *‘how’* to do something but not learning the underlying *‘why’*. Relating this back to Android dev, I would learn how to wire up a RecyclerView. I wouldn’t, however, understand the underlying reasons explaining why it is done that way. I brought this up to fellow Android developers, and discovered I’m not the only person noticing this pattern.
 
Here’s another example related to Android development. The internet has plenty of tutorials explaining how to do networking. Many, if not all, recommend using the popular library Retrofit by Square. The only time Retrofit isn’t recommended is when the API isn’t a REST API in which case, OkHTTP is recommended.
 
These tutorials also don’t get into the details of why Retrofit is so widely used? After doing some digging, I found that Google released a networking library called Volley back in 2013. I looked over Volley documentation, and compared it to Retrofit. In a word, Volley was complex, and was recently deprecated by Google.
 
Another reason is that Retrofit cuts down on the amount of boilerplate code needed. It’s straightforward to write an interface, add annotations, and call said interface. This pattern of libraries created to avoid writing boilerplate explains the popularity of both Glide and Picasso too. Figuring this pattern out, though, took me some time.
 
The pattern of answering *‘how’* and not *‘why’* is not limited to the world of Android Development. I discovered this while setting up this blog. I found myself researching having to look up NPM is (used for managing packages) or Git Submodule (it helps keep your site up to date).
 
Back to Android, why is this the case? To answer the question I asked experienced developers. A possible reason is that the official Android documentation by Google is often incomplete. To fill in the gaps, developers have to rely on unofficial (not by Google) tutorials available on the web. For an experienced developer using these tutorials work but not for a beginner. When I first started I did not have the contacts (or a senior developer) to rely on to have this ‘insider knowledge’. I often had to guess what or use the opinions of YouTubers which isn’t ideal.
 
Despite my frustrations, doing detective work has been beneficial for me. Understanding the why’s has helped me recognize the pros and cons of using an approach. I know if it’s worth using a specific library in my app and how this can impact development down the line. Another benefit is when making architectural decisions for building out features.
 
That being said, I’d love to see these complexities explained and documented better, going forward. It would empower developers, of any skill level, to make better decisions.
