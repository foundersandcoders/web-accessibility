# Web Accessibility
1. [What does accessibility mean?](#what-does-accessibility-mean)
2. [How do I know whether my site is accessible?](#how-do-i-know-whether-my-site-is-accessible)
  + [Web Content Accessibility Guidelines (WCAG)](#web-content-accessibility-guidelines-wcag)
  + [WAI-ARIA](#wai-aria)
3. [But who is this really going to impact?](#but-who-is-this-really-going-to-impact)
4. [Workshop](#putting-yourself-in-someone-elses-shoes)
  + [Tools that can help](./putting-yourself-in-someone-elses-shoes.md#tools-that-can-help)
5. [Designing for full inclusivity, not for the majority](designing-for-full-inclusivity-not-for-the-majority)


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
+ high contrast mode
+ subtitles
+ sign language videos
+ keyboard overlays
+ eye trackers
+ speech recognition software
+ mouth wand
+ sip & puff switches
+ single-switch access

## Workshop
Getting into good habits early-on always makes you a better developer. Baking accessibility into the way you write code should be thought of in the same way as proper indentation - it's a given, not a "nice to have".

Start putting this into practice by [putting yourself in someone else's shoes](./putting-yourself-in-someone-elses-shoes.md)

## Designing for full inclusivity, not just for the majority
It's worth remembering that accesibility in the broader sense can also refer to a wider variety of situations. For example, accessiblity affects users who:
+ have a low level of fluency in [the most prevalent languages on the web](http://www.internetworldstats.com/stats7.htm)
+ are new to technology
+ experience low internet speeds
+ use old hardware/software
+ only have web access via mobile

**_Designing for inclusivity invariably ends up having a positive impact on able users too._**

By considering those with disabilities, you are forced to make applications that cater for the use all of your senses.

Think about whether your site caters for these users' scenarios:

`"Power users" often prefer to use the keyboard because it is faster than using the mouse.`

`Subtitles can be helpful for any users who are in a public space and unable to turn on their sound, or users whose speakers are not powerful enough.`

`Screen magnification is frequently used during presentations`

`Speech recognition software is so widely used, it's barely worth highlighting`

`Navigation devices operate with a kind of "screen reader" for people who are driving (or cycling)`

`High contrast and larger text can help users with screen glare from bright sunlight`
