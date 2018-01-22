## Tools that can help
Bear in mind this advice from Government Digital Services (GDS):
> You must not solely rely on using automated tools to check accessibility - they can only find 20% to 30% of issues.

and from WebAIM:
> No automated evaluation tool can tell you if your site is accessible, or even compliant. Human testing is always necessary because accessibility is about the human experience.

So be savvy when you use the following tools. They are no substitute for learning your craft. But using a variety of tools to test different aspects can at least help you while you're learning:

### HTML checkers
[HTML validator](https://validator.w3.org/nu/) (website) - fairly comprehensive  
[HTML Code Sniffer](http://squizlabs.github.io/HTML_CodeSniffer/) (website)

### All in one - [see a summary of what these tools check for](#what-these-tools-check-for)
[Tenon.io](https://tenon.io/) (website) - nice visual representations, and fairly thorough  
[Wave - the chrome extension](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh/related) - not as visually appealing, but does contain more thorough description that is directly related to W3C's advice, with links
[Wave - the website, in case you don't want to download yet another extension](http://wave.webaim.org/)  
[Tota11y](https://chrome.google.com/webstore/detail/tota11y-chrome-extension/jbhkjcigeionejpngkcdccblocdnjini?hl=en) (chrome extension) developed by Khan Academy  
[a11y](https://addyosmani.com/a11y/) (command line tools) - especially useful once you're writing backend code and running scripts using your command line, you never have to leave the terminal

### The ones you will have downloaded during the workshop  
[Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en) (chrome extension) - sits inside your dev tools rather than the toolbar, so easy to switch between the accessibility audits and changing your code  
[HTML 5 outliner](https://chrome.google.com/webstore/detail/html5-outliner/afoibpobokebhgfnknfndkgemglggomo?hl=en) (chrome extension) - nothing fancy, just a quick visual check of your DOM ordering & semantics  
[ChromeVox](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en) (chrome extension) - it's good to remind yourself what it's like once in a while, a nice interactive way of seeing if your code does what you want it to  

#### What these tools check for
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
