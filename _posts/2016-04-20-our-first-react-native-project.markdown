---
layout: post
title:  "React Native, Take One"
date:   2016-04-20 00:00:00 
categories: react reactnative javascript mobile iOS
---

At Spartan Systems, we get to work on a LOT of green-field projects, primarily
web based software. We have done quite a bit of mobile work as well in the past,
and as 2016 is gaining in momentum, we already have 3 mobile projects on the
horizon. For many shops this might not seem like a large number, but for team of
14 engineers split across the spectrum of server to design, this means that
almost everyone will touch a mobile project in the upcoming 4 months.

In the past, we've worked with Objective-C, Android, ionic and swift and haven't
really been able to settle on a tool that can be each of the following

- quick to iterate on
- easily testable
- in a common language to the entire team

As of Jan 2015, Facebook released React Native, which if you haven't heard of
it, is essentially React Bindings to the underlying native components for both
Objective-C and Android studio. Unfortunately, the code isn't quite write once,
run anywhere, but there is a considerable amount of work that can be reused
cross platform. Additionally, as the name suggests, writing in react native lets
you use the same component structure & data flow that you would expect from a
typical React app. There are a few gotcha's that I will get into later, but for
the most part, the projects _should_ be navigable to an experienced front end
developer. Big Win. Additionally, all of the code actually interacts with native
features, so there's no more unnecessarily messing around with web views. You
can arrive at a very similar look and feel to that of a true, native app.

### Necessary Education

Despite what you might hope, React Native is still a far cry from your standard
front end application. You still use npm to install the majority of your front
end dependencies, but you will also have to be ok with interacting with XCode on
a regular basis. We had quite a bit of heartache early on when getting the
intial project set up, dealing with fun linker issues, repeatedly having to
delete XCode's wonderful derived data directory, etc. Here's a great video from
the RN docs that gives a good overview on what you'll need to know coming from
primarily a web background. More awesome content can be found in the [RN
Documentation](https://facebook.github.io/react-native/docs/videos.html)

<div style="width: 100%; float: left; text-align: center">
  <iframe style="margin: 0 auto;" width="560" height="315" src="https://www.youtube.com/embed/-XxSCi8TKuk" frameborder="0" allowfullscreen></iframe>
</div>
