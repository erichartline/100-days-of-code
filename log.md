# 100 Days Of Code - Log

### Day 16: Saturday, June 24, 2017

**Today's Progress** I spent a good eight hours learning React.

**Thoughts:** I wanted to get a better understanding of React so I decided to finish up the timer/countdown project from Andrew Mead's Udemy course. There was *a lot* of content to digest (and definitely some stuff I will need to go back and revisit), but overall I feel I learned quite a bit. Perhaps most interesting was how we added in testing using Karma/Mocha/Expect. Doing test-driven development is something I have been wanting to learn about for a while now, so it was really cool to see it implemented in real-time for a major project like this. This app seems like a strong basis that I can use when I rebuild my own Pomodoro clock with React in the future.

**Link to work:** [React Timer App](http://fast-springs-17349.herokuapp.com/#/?_k=wwrh7b) & [React Boilerplate 3](https://github.com/wildlifehexagon/react-udemy/tree/master/ReactBoilerplate3)

### Day 15: Friday, June 23, 2017

**Today's Progress** I updated my personal portfolio, watched most of the videos from week 4 of M101JS, read some YDKJS, worked on my team project and had an interview with a recruiter.

**Thoughts:** Feel like I did a little bit of everything today. I had been meaning to update my personal website ever since finishing my Simon game project, so I finally went ahead and did that. I also added some skills and a "currently learning" line, much like my LinkedIn profile. I made some small changes to components in my team project, but I feel I still need to get a better understanding of `state` and passing around props.

**Link to work:** [Components branch](https://github.com/wildlifehexagon/draw-dash/tree/components) & [Personal Portfolio](http://www.erichartline.net)

### Day 14: Thursday, June 22, 2017

**Today's Progress** I worked on my Chingu team project. and had an interview with a recruiter.

**Thoughts:** I spent a lot of time on this today but didn't get nearly as far as I had hoped. I decided to focus on adding our components and making sure that everything would be linked together properly. What should have been so simple -- importing one component into another -- ended up being a major process. I spent hours trying to figure out why it wasn't working, rewriting my `const` statement to a `class` and vice versa, changing my routing patterns, trying new components. Nothing worked. It wasn't until my partner happened to change the file and folder reference from `./containers/Canvas` to `./Canvas` that it all worked. Of course it was so simple after all! On the plus side, thinking it was an issue with upgrading to React Router v4, we both read the docs and learned the differences between the new and old versions. Wasn't the problem but still good info to know.

**Link to work:** [Components branch](https://github.com/wildlifehexagon/draw-dash/tree/components)

### Day 13: Wednesday, June 21, 2017

**Today's Progress** I went to my first presentation-style meetup: "Beautify your async flow with generators/async+await & Koajs".

**Thoughts:** To be honest, a lot of the presentation material went over my head, but I did have a good time at the meetup. I met my cohort partner in person and discussed a more detailed gameplan for our project, got some Node.js swag and checked out Braintree's really cool office. Seeing their decked-out location has me even more excited to get my first dev job! Tomorrow I will have a lot of coding time available, so I'm aiming to get a lot done.

### Day 12: Tuesday, June 20, 2017

**Today's Progress** I worked on adding some Foundation styling to my team project, and submitted my first `pull request` for it.

**Thoughts:** This was definitely trickier than it seems, and it took me an hour plus to get everything implemented correctly. The Udemy course I have been following along with is great, but it is so, so dated, and the discrepancies between it and the new boilerplate we have been working with are jarring. I had to install additional modules, add in some stuff (brand new to me) to webpack.config.js, and adjust the package.json start line to work correctly with Windows. There are a ton of moving pieces already, and we haven't even started adding components. This is a HUGE learning experience, but it is totally going to be worth it.

### Day 11: Monday, June 19, 2017

**Today's Progress** I finished the second book of YDKJS and attempted to start working on my team project.

**Thoughts:** I was hoping to get in a good coding session this afternoon for my Chingu team project, but I ended up spending most of my time debugging. I couldn't figure out for the life of me why our React boilerplate wasn't working. Eventually I figured out that some files got lost in the transition, including the ever-crucial .babelrc, and that was causing all sorts of errors. We have a functional boilerplate now, however, so it's time to get coding.

### Day 10: Sunday, June 18, 2017

**Today's Progress** I read some YDKJS, went through a Canvas guide on JavaScript 30, and learned about testing with Expect.

**Thoughts:** Didn't get as much coding done today as I hoped, but at the very least I am almost finished with book 2 of YDKJS. The Canvas guide I went through was really cool -- that's going to come in handy for my upcoming Chingu collaboration.

### Day 9: Saturday, June 17, 2017

**Today's Progress** I finished week 3 of M101JS, started the React Timer app in Andrew Mead's React course and read some YDKJS.

**Thoughts:** This week's homework was a bit of a drag. There was a lot to take in with little in the way of quiz breaks, so it was hard to retain some of the features that were discussed. The homework only had two real challenges, and they only involved writing a few lines of code. On the plus side, there were a few videos about using Twitter's API, and those showed a side of MongoDB's capabilities that I didn't know about. I'm about 1/4 through the React Timer section in the Udemy course. Mostly review so far, but it did bring up some cool points about SCSS (namely that you can use partials with _ at the beginning of the filename and then bring them altogether with one stylesheet). I think tomorrow I'm going to do more reading and try to finish the second YDKJS book.

**Link to work:** [React Timer on Heroku](https://fast-springs-17349.herokuapp.com/) & [M101JS](https://github.com/wildlifehexagon/M101JS/tree/master/wk3)

### Day 8: Friday, June 16, 2017

**Today's Progress** I finished the weather app (through section 7) in Andrew Mead's React course. I also watched the first few videos in week 3 of M101JS.

**Thoughts:** In the final section of the weather app, the instructor had us add in some pretty cool features -- Foundation, custom CSS and SCSS. I was pretty happy about that because I was wondering how the styling could be included in a React app. We also added in some error modal popups and got the nav bar search to work properly. All really useful stuff, and I'm excited to dig into Foundation more. It looks like a good alternative to Bootstrap, which I was kind of getting tired of.

I thought about taking a break from the course to rebuild my old FCC weather app, but I think I'm going to push through and continue learning more about React. I do plan on rebuilding the weather app afterward, however.

**Link to work:** [ReactWeather on Heroku](http://dry-scrubland-92983.herokuapp.com/#/?_k=zi9cto)

### Day 7: Thursday, June 15, 2017

**Today's Progress** I worked all the way through the first six sections of Andrew Mead's React course.

**Thoughts:** The React weather app is coming along nicely! It still looks crude, but styling is coming soon. Everything is functional as of now, including working subpages. The content is very basic -- you can only get temperature by typing in a city -- but I'm very pleased to have a working app. I feel like I've been learning a lot from the course, and I'm glad that the instructor added in some ES6 content after all. I'm starting to get used to writing out fat arrow functions, and definitely getting the appeal of them.

**Link to work:** [ReactWeather on Heroku](http://dry-scrubland-92983.herokuapp.com/#/?_k=zi9cto)

### Day 6: Wednesday, June 14, 2017

**Today's Progress** I worked on my React course.

**Thoughts:** I got the early stages of the React weather app done. It's nice to finally have Webpack working properly, and today's coding was mostly error-free. One nice surprise in this course was a section on ES6 promises, which served as a good complement to last night's workshop. I have tomorrow wide open, so I plan on maximizing my coding time as much as possible.

I also spoke to a recruiter today about a junior dev role that I might be a good fit for. Talking more about it next week, here's hoping!

**Link to work:** [ReactWeather](https://github.com/wildlifehexagon/react-udemy/tree/master/ReactWeather)

### Day 5: Tuesday, June 13, 2017

**Today's Progress** I went to a NodeSchool meetup!

**Thoughts:** I didn't get to do any React work done during the day, but I went to my first NodeSchool meetup tonight. It was actually a lot of fun! I worked on the 'promise-it-wont-hurt' workshop, and was able to finish half of the challenges while teaming up with someone else. Overall, it was a great time since I feel I learned a lot, and I got to meet some cool people. Apparently there is another Node.js meetup next week, so I am going to try to do that as well.

**Link to work:** [NodeSchool](https://github.com/wildlifehexagon/nodeschool)

### Day 4: Monday, June 12, 2017

**Today's Progress** I worked on fixing that Webpack bug from yesterday.

**Thoughts:** It took a while, but I solved the problem! A fellow Chingu in my Slack #chingu-central channel pushed me in the right direction. We discovered that the dev dependencies weren't installing, and a bug in NPM5 was wiping out my regular dependencies when I ran `npm install --only=dev`. I rolled back to  NPM4, ran `npm install` then `npm install --only=dev` and voila, `webpack` worked! Although I was frustrated with all of the error messages, the debugging process ended up being very enlightening. I'm going to try to work on the React some more during the day tomorrow, then it's off to a NodeSchool event at night!

**Link to work:** [React Udemy Repo](https://github.com/wildlifehexagon/react-udemy)

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
