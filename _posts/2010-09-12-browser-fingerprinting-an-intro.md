---
title: 'Browser Fingerprinting: An Intro'
author: leah
layout: post
permalink: /2010/09/browser-fingerprinting-an-intro/
categories:
  - security/privacy
---

This idea of browser fingerprinting has been bouncing around the web, so I figured you might be interested in a summary. The buzz mostly started with an Electronic Frontier Foundation [experiment ][1]and is pretty shocking if you are interested in anonymous browsing, for whatever reason. My explanation here may not be perfect – please feel free to contribute any corrections in the comments.

**Background**  
Basically, when you visit websites, they want to be able to track who you are and what you are interested in. Sites usually/historically do this by setting simple cookies (small text files, basically) or more recently super cookies through Flash, which cannot be deleted with the regular browser options you may be using to clear cookies. (Side note: [Reports ][2]about the privacy implications of these persistent super cookies abound as well.) Until now, we mostly focused on cookies and IP addresses when worrying about basic anonymous browsing.  

**That's All Changing**  
Enter browser fingerprinting. Based on the browser you are using, how recently you upgraded it, the settings you have selected, the plug-ins you have installed in your browser like flash and java, your fonts, and a few other factors, the browser you use likely has a very unique fingerprint that can easily pinpoint you as an individual. If you don’t have flash or java, this gets slightly more difficult (but not by much, and come on, who doesn’t have Flash other than iPhone and iPad users?).  

**Key Takeaways**  
According to the EFF Study ([full PDF available here][3]):  
1. If you have Flash and Java installed on your browser, you can be identified uniquely 94.2% of the time and to yourself and one other browser 99% of the time.  
2. But wait, you say? What if I change settings or anything else from time to time? Yes, fingerprints do change pretty rapidly. However, using a simple algorithm, EFF was able to correctly identify the same browser after a fingerprint change 99.1% of the time.  
3. Most anti-fingerprinting or privacy-protecting tools are self-defeating, as their presence is easily detected and this only makes you more unique.

**My Analysis**  
1. This could be used to identify groups as well. For example, if your organization does not allow users to customize features or install plug-ins and rarely updates browsers and other software, I think it would be very easy to identify a range of characteristics that could flag its users.  
2. Even if you fall into that 1% of not-especially-unique browsers, doesn’t that, by itself, flag you as unique?  
3. In our approach to browsing anonymously, we should be trying to hide in the noise, not tip toe anonymously.  
4. My guess is the best solution is to come up with a way to make your system match the most common browser fingerprints. Back to the drawing board&#8230;

 [1]: http://www.eff.org/press/archives/2010/05/13
 [2]: http://www.eff.org/deeplinks/2009/09/new-cookie-technologies-harder-see-and-remove-wide
 [3]: https://panopticlick.eff.org/browser-uniqueness.pdf
