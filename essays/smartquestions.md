---
layout: essay
type: essay
title: Smart Questions Prevail
permalink: essays/smartquestions
date: 2017-01-20
labels:
  - Software Engineering
---
<img class="ui large center floated rounded image" src="../images/dilbert.jpg">
'There's no such thing as a dumb question' is a quote that I've heard get thrown around a lot lately. Though I agree that if someone has a question, no matter how 'dumb' it is, it isn't actually dumb. Questions are how we increase our knowledge, and everyone will have a 'dumb' question at least a hundred times in their life. For me, it's closer to a hundred times a week. Now, having said that, I do have to point out that there is a dumb way to get your question answered, and most of the time it has to do with lazyness. I cannot count how many times I've asked questions that, if I had just thought about it for twenty more seconds, I would have found the answer myself. I also cannot count the amount of times I've heard someone else ask a question that could have been answered by a few seconds of thought or two minutes of calculations.

In an article written by Eric Steven Raymond, the author delves deeper into the idea of a 'smart' question by applying it to technical questions specifically. In this case, he used Stack Overflow (a site for programmers and hackers alike to develop forums of discussion about computer software and hardware dilemmas) as the template to give the best advice on how to get your questions answered, get it completely ignored, or create a perfect sacrifical lamb for hackers to pour out their frustration on the "lazy programmer". His article, [How To Ask Questions The Smart Way]("http://www.catb.org/esr/faqs/smart-questions.html") becomes a beautiful "How To" for beginners and veterans alike.

# Installshield 2011 - Problem Upgrading existing software with Version format 2009.727.1365
Using Installshield 2011, we're creating a major upgrade and having problems upgrading software with this Product Version format - 2009.727.1365. We keep getting the standard 'Installed software is newer than product to be installed' message. With IS 2011, the major version has to be less than 255, from what I can gather, and I think the old format we're using is breaking the check for upgrading.

I've created a test IS project upgrading from 1.00.0000 to 2.00.0000 with no issues, so I'm thinking the issue has to be related to the format of the product version already installed.

Is there a way to use InstallScript or something to compare our old format with the new one and then do an override?

Any help would be greatly appreciated. Thanks in advance!!

---
*The first good thing about this question is the title. It has specific information about the type of software he's using, with the version of the software to top it off. This title will catch the eye of a knowledgable programmer and often they will be able to formulate hypotheses' of the problem before they read the description of the problem. The second good thing is how he describes what troubleshooting and testing he has done so far and what his though process is. This shows that the question has thought and work behind it, it's not just posted immediately after finding the error.*

*This kind of question opens the door for programmers to intelligently reply with their expertise and advice and be confident in their answer because the user that asks the question gives enough information in very little space. What a great example this guy sets!*

---
## Some advice to programmers
After reading the article by Raymond, I have some highlights that might be useful! Especially to those that are just starting out on programming.
<dl>
  <dt>1. Don't ask homework questions!</dt>
  <dd>"Hackers" can see, nay<i> smell </i>a homework question form a hundred miles away. You will get burned, badly.</dd>
  <dd>The best thing to do when you have a question about homework is google it. I assure you, the answer will be there.</dd>
  <dt>2. Do not label your questions as "urgent"</dt>
  <dd>It's only urgent for you, and it will not draw a hacker to a problem if all it says is "URGENT!! segmentation fault file won't compile!!" This, for one, is not giving any insight into what common problem this could be related to, and is a common enough question that it doesn't quite make sense why you didn't spend 5 minutes searching for the answer.</dd>
  <dt>3. Please and Thank You are sometimes the actual magic words</dt>
  <dd>There's nothing better than being a polite programmer, and especially on the internet when facial expressions are not present, we all need to make a conscious effort to be kind to those helping us. Maybe it will even be the difference between getting helped or not.</dd>

</dl>
