# Homework-4-MBSE

Jordan Fernandes
May 1, 2022
I pledge my honor that I have abided by the Stevens Honor System. 

HW4: Reflection

Design
Overall, I would consider a lot of the design process helpful. From the initial workshop, my team and I had decided that we wanted to create a Discord “meme-bot”: one of us brought it up, and the group loved the idea. But still, it needed fleshing out, and the design exercises we did did a great job at that. Starting with a basic description, we started using Agile methods that we learned: use cases, storyboard, flow diagrams. Of these, I would say that the use cases, storyboard, and description were most helpful. These were the most intuitive ways of understanding the bot, in my view. The initial description helped us plan our high-level flow, then the use-cases and storyboard helped us solidify our vision. From there, I could picture us easily launching into architectural activities, or even setting up process, such as workflow, overall project blueprint, and issues. 

I would say that the hardest part of our design tasks was UML, specifically the sequence diagram. The task gets credit from me for demanding specificity: naturally, UML fits well for defining architecture. The sequence diagram helped us define precisely what parts of our bot were intended to do what, and when they were to do it. However, by that same virtue (and by the very well-defined syntax that UML demands), working out this part of the design was rather cumbersome. It was helpful for defining architecture, but I could imagine that it would be hard to change later: i.e., not very “agile” in a world of programming that has largely become “agile”. I wouldn’t say we would do anything differently in this task, but we may have preferred to use a different form of sequence diagram that did not demand so much exact syntax, which made this take longer to make than it could have. 

As I mentioned earlier, I would love to continue using Agile design methods in future projects. These techniques both defined our bot and really helped us think about where our bot was going. They were the most engaging, and most collaboratively-powered, forms of design, and in turn, that groundwork (both in a design and “project culture” sense) should be a great setup for the future of the project. 

Implementation
By far, one of our greatest assets in implementation was our hosting system. Early in the project, we were able to set up Heroku in order to host our bot. This service allowed us to constantly have our bot online in our Discord server, which allowed us to constantly, actively test our bot. Another helpful asset in integration was actually one of our team members: Adrian! He had prior experience with Discord bots, and he was able to set up an initial boilerplate for our bot. Just having that boilerplate in place was an instant start to our architecture: it set up the framework for me to work on command parsing, and for us to set up our local-side file system. Lastly, Node and npm were helpful for implementation, although I often take those for granted nowadays! The asynchronous model works naturally with Discord messages, and I couldn’t imagine developing this bot (or any project nowadays, really) without a package manager in the form of npm. 

By the same virtue, implementing our bot had some difficulties. Because we were developing a meme-bot, which randomly generates memes, trying to test our bot was largely manual. A lot of time was spent setting up meme formats to correctly add text. Mind you, having a JS library to edit images was incredibly helpful, but we had to set the places where the text appeared. In the end, we were still proud of our final product, but if only we had some more time aside from this setup, I would love to see where this bot could head. (Trying a different approach, or streamlining this one, would be something I would definitely do differently the next time around.)

As for future use, Heroku was helpful, so next time I’m developing a bot, I’d take a look there. The knowledge I gained from this first go at bot development was also helpful, so I’d certainly use that again! Lastly, of course, I’d use Node and npm again. But also, I’d want to try lots of new things in my future work. First, I’d want to try to set up some form of automated testing. Although this would be difficult for a project like this one, it could’ve been implemented for some basic things like message parsing. It would certainly lead to a cleaner project, I think. I’d also want to think of a less intensive process to set up this project. Given more time and development, we would have looked forward to setting up a more automated backend instead of having to manually process so many meme formats. 

Process
The Kanban board was amazing for this project. Along with the rest of Github (branching, pull requests, etc.), the board helped us keep track of the tasks remaining in the project, and it helped us coordinate our effort levels and workflow for each specific task. In other words, the Kanban board helped us see through the potential chaos of developing a large project. Code reviews were another great asset for this project. The most essential part of code reviews, in my view, is that they ensure that the code you built works in all cases, and doesn’t break on another machine for some reason. Reviews also help sleuth out bugs, and, given a conscientious-enough reviewer, can also keep code cleanliness and style in-tact (and hunt down code smell). All of these effects came into fruition from our reviews, which was another great help to maintaining order in the development space. 

Of course, the consequence of having this process is that the process, itself, takes some time. Sometimes, code reviews were left hanging for a bit, and we had to poke each other to move in on them. In the end, ultimately, they were reviewed, but we could’ve been more motivated to take initiative in this space. But this is more a flaw on our part, and less so on the model here. Merging was also a bit difficult at times. When conflicts arose, we often needed both the reviewer and creator on deck to make sure that merging occurred correctly, and that nothing was fried in the process. This process was a bit more cumbersome than we would’ve liked, but it was ultimately for good reason. 

Needless to say, I would want to use both Kanban and code reviews, and perhaps more, in future projects. Kanban is effectively a better version of Github issues, and it slots in with Agile design and planning. Meanwhile, code reviews are pretty much essential for not just less bugs in code, but for various stylistic, human factors. (Aside from eslint’s help, that is!) I would like to use both in future projects. I would also want to expand with further process philosophies, including scrum and better management of the greater project backbone (milestones, etc). This could even extend into Github automation, if it supports it. 

Overall
As I’ve alluded to in this response, I am generally in favor of the agile philosophy. Design techniques like storyboards and use cases provide an intuitive way of understanding the project ahead, and they’re more abstract and dynamic in practice. In contrast, although UML grants greater specificity and more solid architecture, setting it up is expensive in terms of time and commitment, and it can be a beast to edit later on. Second, for implementation, having Heroku hosting and package management was a great asset on the project. I would go further next time with a more solid (and hopefully automated) testing infrastructure, although it fell through on this project. (In fact, one famous development combo is to break down use cases into specific program-side scenarios, then develop initial tests based on them: test-driven development. In an Agile development environment, I could easily see this practice taking root: at least, as far as the code can be easily tested automatically.) Finally, Agile has incredible power on the process side through Kanban, project weighting (i.e. “planning poker), scrum meets, and code reviews. I’d want to use all of these in future projects, hopefully with as much Github (or other program) support as I can find. 

So, in total, most of what we covered in this project can combine together into a powerful Agile stack (aside from some exceptions, like UML). I’m not only eager to utilize this stack in the future, but to perhaps execute it in future workplaces where Agile has become so popular. 
