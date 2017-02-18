# Web Accessibility
1. [What does accessibility mean?](#what-does-accessibility-mean)
2. [How do I know whether my site is accessible?](#how-do-i-know-whether-my-site-is-accessible)
  + [Web Content Accessibility Guidelines (WCAG)](#web-content-accessibility-guidelines-wcag)
  + [WAI-ARIA](#wai-aria)
3. [But who is this really going to impact?](#but-who-is-this-really-going-to-impact)
4. [Workshop](#workshop)
5. [Designing for full inclusivity, not for the majority](designing-for-full-inclusivity-not-for-the-majority)
6. [Tools that can help](#tools-that-can-help)
  + [What they're looking out for](#what-theyre-looking-out-for)


## What does accessibility mean?
Good old [wikipedia](https://en.wikipedia.org/wiki/Web_accessibility):
> Web accessibility refers to the inclusive practice of removing barriers that prevent interaction with, or access to websites, by people with disabilities. When sites are correctly designed, developed and edited, all users have equal access to information and functionality.

Actually this definition is slightly limiting. Because accessibility is not just about the disabled. But considering this group while you are writing your apps can help to ensure _inclusive design_.

Remember, no content that you ever create is exclusively for you. _Everything you make should have your users at heart._

### How do I know whether my site is accessible?
#### Web Content Accessibility Guidelines (WCAG)
You should follow the guidelines that have been developed by the Worldwide Web Consortium (W3C) - the governing body of the web.

[WCAG 2.0](https://www.w3.org/TR/UNDERSTANDING-WCAG20/) has seen wide international adoption into [governmental law](https://www.powermapper.com/blog/government-accessibility-standards/), and its guidelines follow these principles:
+ **Perceivable:** Available to the senses (vision and hearing primarily) either through the browser or through assistive technologies (e.g. screen readers, screen magnifiers, etc.)
+ **Operable:** Users can interact with all controls and interactive elements using either the mouse, keyboard, or an assistive device.
+ **Understandable:** Content is clear and limits confusion and ambiguity.
+ **Robust:** A wide range of technologies (including old and new user agents and assistive technologies) can access the content.

_If any of these are not true, users with disabilities will not be able to use the Web._

WCAG have different compliancy levels: A, AA and AAA. By reaching the AA standard, a company can call itself "WCAG 2.0 AA" compliant. Depending on who the company is, they may need to comply with a certain standard by law.

#### WAI-ARIA
The Accessible Rich Internet Applications specifications were developed by the Web Accessibility Initiative (WAI) of W3C.

It provides a set of widgets and new CSS attributes to use in your HTML, which allow your web application to be interpreted by assistive technologies such as screenreaders.

Learn the beginnings of Aria by looking at the links in [resources](https://github.com/foundersandcoders/master-reference/blob/master/coursebook/week-1/resources.md)

### But who is this really going to impact?
Most of the time when people talk about accessibility, they're talking about people with the following disabilities (permanent or temporary):
  + visual
  + hearing
  + motor
  + cognitive

Assistive technologies for these users include, but are not limited to:
+ screen readers
+ screen magnifiers
+ braille terminals
+ braille keyboards
+ subtitles
+ sign language videos
+ keyboard overlays
+ eye trackers
+ speech recognition software
+ mouth wand
+ sip & puff switches
+ single-switch access

## Workshop
[Enough talking, let's get interactive](./workshop.md)

## Designing for full inclusivity, not just for the majority
It's worth remembering that accesibility in the broader sense can also refer to a wider variety of situations. For example, accessiblity affects users who:
+ have a low level of fluency in [the most prevalent languages on the web](http://www.internetworldstats.com/stats7.htm)
+ are new to technology
+ experience low internet speeds
+ use old hardware/software
+ only have web access via mobile

_Designing for inclusivity invariably ends up having a positive impact on able users too._

By considering those with disabilities, you are forced to make applications that cater for the use all of your senses.

Think about whether your site caters for these users' scenarios:

`"Power users" often prefer to use the keyboard because it is faster than using the mouse.`

`Subtitles can be helpful for any users who are in a public space and unable to turn on their sound, or users whose speakers are not powerful enough.`

`Screen magnification is frequently used during presentations`

`Speech recognition software is so widely used, it's barely worth highlighting`

`Navigation devices operate with a kind of "screen reader" for people who are driving (or cycling)`

`High contrast and larger text can help users with screen glare from bright sunlight`

## Tools that can help
Bare in mind this advice from Government Digital Services (GDS):
> You must not solely rely on using automated tools to check accessibility - they can only find 20% to 30% of issues.

and from WebAIM:
> No automated evaluation tool can tell you if your site is accessible, or even compliant. Human testing is always necessary because accessibility is about the human experience.

So be savvy when you use the following tools. They are no substitute for learning your craft. But using a variety of tools to test different aspects can at least help you while you're learning:

[HTML validator](https://validator.w3.org/)
[Tenon.io](https://tenon.io/) - website  
[Wave - the chrome extension](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh/related) - more convenient  
[Wave - the website](http://wave.webaim.org/) - if you don't want to download yet another extension   
[Tota11y](https://chrome.google.com/webstore/detail/tota11y-chrome-extension/jbhkjcigeionejpngkcdccblocdnjini?hl=en) - chrome extension, developed by Khan Academy  
[HTML Code Sniffer](http://squizlabs.github.io/HTML_CodeSniffer/) - website

Here are the ones you will have downloaded during the workshop:  
[HTML 5 outliner](https://chrome.google.com/webstore/detail/html5-outliner/afoibpobokebhgfnknfndkgemglggomo?hl=en) - chrome extension  
[ChromeVox](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en) - chrome extension  
[Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en) - chrome extension

### What they're looking out for
There are many things that these tools don't cover. Generally, they're looking at a high-level overview of the things you should be considering:
+ Provide appropriate alternative text
+ Provide appropriate document structure
+ Provide headers for data tables
+ Ensure users can complete and submit all forms
+ Ensure links make sense out of context
+ Caption and/or provide transcripts for media
+ Ensure accessibility of non-HTML content, including PDF files, Microsoft Word documents, PowerPoint presentations and Adobe Flash content
+ Allow users to skip repetitive elements on the page
+ Do not rely on color alone to convey meaning
+ Make sure content is clearly written and easy to read
+ Make JavaScript accessible e.g. your page does not rely on JavaScript to function & event handlers are device independent
+ Design to HTML5 & CSS3 standards i.e. separate content from presentation

When you first learned how to style basic elements using CSS, you had no idea how to do the huge variety of things it has to offer. Think of this in the same way. We've barely scratched the surface, but that's the fun part!
