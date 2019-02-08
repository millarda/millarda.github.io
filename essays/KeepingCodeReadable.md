---
layout: essay
type: essay
title: Keeping Code Readable
# All dates must be YYYY-MM-DD format!
date: 2019-02-07
labels:
  - Professionalism
  - Etiquette
  - Standards
---
<h2>Keeping Code Readable</h2>
Coding readability is something that I have found a couple different opinions on. Some people don't care at all about coding standards or readability and simply focus on function. Others may go out of their way to ensure their code is unreadable by anyone to ensure their job security. Some heavily value coding standards as it allows for efficient collaboration as well as allowing future edits to the work to be as efficient as possible.

I have begun using an integrated development environment (IDE) called IntelliJ IDEA that allows one to set coding standards for themselves. In particular I have enabled a set of standards from the ESLint linter. A linter is essentially a tool that is able to analyze code for errors. These errors are intended to keep the developer in good coding practice. A majority of these errors are stylistic, meaning that they have no real effect on the code's functionality. They serve to keep the code readable and help set a uniform look to the overall code. This makes going back to fix or change work a less taxing experience. Another common error is to correct inefficient or potentially misleading code. A good example of this would be declaring a variable that actually is never modified at any point. This would prompt an ESLint error requesting the developer to have the element declared as a constant (rather than a variable).

<img class="ui image" src="{{ site.baseurl }}/images/intellij.png">

I did have some issues with properly setting up ESLint that I was able to troubleshoot through. But otherwise I do find ESLint as a good way to force myself to adopt modern and professional code structure. I often teach myself how to code certain languages or use certain programs, but I always find myself missing a little bit of something important. For example, until recently I didn't realize that code wrapping was a common feature for most IDE's. This is now something that I have enabled on all IDE's that I use. In fact this essay was typed on an editor with it enabled. Now that I have a better grasp on using coding standards, I do consider it something to appreciate.
