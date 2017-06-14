# 100 Days Of Code - Log

### Day 4: Tuesday, June 13, 2017

**Today's Progress** test

**Thoughts:** test

### Day 4: Monday, June 12, 2017

**Today's Progress** I worked on fixing that Webpack bug from yesterday.

**Thoughts:** It took a while, but I solved the problem! A fellow Chingu in my Slack #chingu-central channel pushed me in the right direction. We discovered that the dev dependencies weren't installing, and a bug in NPM5 was wiping out my regular dependencies when I ran `npm install --only=dev`. I rolled back to  NPM4, ran `npm install` then `npm install --only=dev` and voila, `webpack` worked! Although I was frustrated with all of the error messages, the debugging process ended up being very enlightening. I'm going to try to work on the React some more during the day tomorrow, then it's off to a NodeSchool event at night!

### Day 3: Sunday, June 11, 2017

**Today's Progress** More React Udemy work.

**Thoughts:** I ran into some issues with Webpack, and they severely derailed my course progress. I had copied over my React boilerplate to get started on the new weather app, but I kept getting `Cannot resolve module 'babel-loader'` errors every time I would run `webpack`. I spent a couple hours trying to figure this out, but none of the 'fixes' I found worked. I had to leave for the evening but I was still in the coding mood, so I went through the entire JavaScript section in the SoloLearn phone app.

### Day 2: Saturday, June 10, 2017

**Today's Progress**: I finished Week 2 of M101JS, did a couple sections of my React Udemy course and read a chapter of the second YDKJS book.

**Thoughts:** I feel like I had a very productive day today -- basically a full work day of coding. I started off by doing everything required in Week 2 of M101JS. I enjoyed this quite a bit since it focused on what commands are needed for CRUD in MongoDB. The homework questions were especially helpful since they required a lot of trial and error in finding the right syntax to look things up in their movie database. I'm digging this class so far.

After finishing that, I started venturing back into my React learning. I went back to Andrew Mead's "The Complete React Web App Developer Course" on Udemy and finished the HelloReact and ReactBoilerPlate projects. I'm liking his teaching style more than the other React Udemy course I picked up, but it is a little disappointing that it doesn't use as much ES6. I suppose it doesn't hurt to learn the old syntax, too, though.

The next project in the course involves building a weather app, and I'm really excited to see how that goes. I already built a weather app using JavaScript and jQuery, so it would be fun to update it to use React instead.

Finally, I started re-reading You Don't Know JS: Scope & Closures. I read this a few months ago but got sidetracked on the third book. This time I plan on finishing the entire series in order.

**Link to work:** [React Udemy Repo](https://github.com/wildlifehexagon/react-udemy)

### Day 1: Friday, June 9, 2017

**Today's Progress**: I finished Week 1 of M101JS.

**Thoughts:** I have been coding a ton lately, but I felt I needed to start writing about my experiences again. What better way to do that than start up #100DaysOfCode once again? My goal this time around is to be more active with other developers while also learning more about React and Node.js. I finished my front end certificate from freeCodeCamp last month and I'm ready to start digging into some heavier stuff. I also plan on finishing the YDKJS books this month.

Next Tuesday I'm going to a NodeSchool event, so I figured I should brush back up on Node.js. I noticed that MongoDB University's M101JS class started a new session, so I joined that. Even though the grading period for week one is over, I still went ahead and finished the homework and extra credit assignment. I also created a repo to store my assignments.

I'm not sure that I love the teaching style of the class -- they just give you ZIP files of the material and go too fast so you can't really code along yourself -- but the extra homework assignment really helped lock things in for me. I'm starting to feel a bit more familiar in navigating through MongoDB using the command line, and I'm getting up to speed with basic Node.js syntax.

It also seemed fitting to start this journal back up again since today is the first day of the June Chingu cohort. I'm in the Chameleons group this time, and I plan on joining one of the team projects. Not sure yet if I want to do the Slackbot one or an open project.

**Link to work:** [M101JS](https://github.com/wildlifehexagon/M101JS)
