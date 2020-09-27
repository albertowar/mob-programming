# PSA Mob Programming Session

Mob programming (informally mobbing) is a software development approach where the whole team works on the same thing, at the same time, in the same space, and at the same computer.
> -- <cite>[Wikipedia][1]</cite>

## Start with WHY
Inspired on Woody Zuill's talk, I decided to run a Mob Programming in PSA as an experiment in case we wanted to adopt this for any future **product** work.

[![GOTO 2019 • Mob Programming and the Power of Flow • Woody Zuill](https://img.youtube.com/vi/28S4CVkYhWA/0.jpg)](https://www.youtube.com/watch?v=28S4CVkYhWA)

There are many benefits observed when putting mob programming in practice:

- **Work never stopped.** Someone home sick? Someone leaving early? Not a problem. The mob was always there, ever moving on, like a scary blob creature.
- **Knowledge sharing increased by bounds and leaps.** After a ridiculously short while we all had access to the total shared knowledge of the team members, since we all had to go through each other’s motions. We knew all the quirks of someone’s newly built service, we extended our knowledge of nifty shortcuts, we learned to deploy. Our testers learned to code and script beyond what they had done before, and our developers learned to adapt a much more test driven way of thinking. When you yourself have to performance test your service, you build a more testable service.
We no longer have different ways of deploying to production, writing tests, exploratory testing, or most other things you can think of, instead we are all doing it together. What’s more, this means that we get to hear all those little smart ideas and tricks that were contained in people’s heads in the past, and they become part of a new and improved way of doing everything.
- **The overhead got removed.** All of those little sync things are no longer an issue. You have in issue you need to bring up with your team? Instead of waiting for a standup or calling a meeting, you just open your mouth. Chances are good that your team members were just about to do the same thing, since you stumbled on the issue together. Everything gets resolved as it is brought up, saving you both time and emotional effort.
- **Anyone could go to any meeting.** Since we all knew exactly what was going on with everything we did, any member of the team could represent in any meeting.
- **Our tooling improved.** When working together like this every minute is precious, and laborious manual procedures that you just buckle down and get done as an individual can no longer be tolerated.
- **Individual weaknesses could be overcome.** When you all have to think and work through each other, your weak points become exposed very early on. Instead of hiding them from your team members, they become obvious to everyone, and thus dealt with. We found that we very quickly evened out the playing field of individual shortcomings.
- **Interpersonal issues and friction had to be resolved.** When interpersonal issues happened they get brought up much more quickly. In a ”normal team” when there are these types of interpersonal issues they are often allowed to fester. People who have issues only need to deal with each other for limited periods of time, so they just grin and bear it. This isn’t really possible inside of the mob because you would go completely insane.
- **Stress levels dropped.** When responsibility was suddenly explicitly shared across the team, individuals no longer felt as guilty for the entire team failing. Weaknesses were exposed very early, and handled before they could fester.
- **We became more daring and forward.** When you are facing obstacles together rather than individually, it is a lot more easy to make brave decisions. You decide to override a rule or kill off a service together, and as such you know that it is defendable and that your team members will always have your back.
- **We became friends.** Well, we were friends earlier as well. But having to actively work on a close relationship with a group of people forges friendship, and in the long run we found ourselves closer than we had been before.

> -- <cite>[Source][2]</cite>

## How?
There are two different roles within the mob:
- **The navigators.** They will be doing the thinking about the direction we want to go and then verbally describes and discusses the next steps of what the code must do.
- **The driver.** The person in charged of transforming the navigator ideas into code. They are not allowed to think, just type :)

We will rotate the driver every 10 minutes and will do so for 4 full rotations. Not everyone will get to drive but everyone will get to contribute!

## The rules
Today's goal is to refresh our TDD skills, hence we will be following the **Red, Green, Refactor** strictly.

![Red Green Refactor](https://s3.amazonaws.com/codecademy-content/programs/tdd-js/articles/red-green-refactor-tdd.png)

In order to smooth the handover to the next driver, we will create a commit with a meaningful message every time the build is **green**. The build **MUST** be **green** before a handover.

## The problem
https://katalyst.codurance.com/string-calculator


## Join the mob!
This first mob programming session will be done in Java, so you will need:
- [Maven](https://maven.apache.org/)
- [JDK 11](https://aws.amazon.com/corretto/)
- [IntelliJ](https://www.jetbrains.com/idea/)
- [Git](https://git-scm.com/downloads)

[1]: https://en.wikipedia.org/wiki/Mob_programming
[2]: https://underthehood.meltwater.com/blog/2016/06/01/mob-programming/