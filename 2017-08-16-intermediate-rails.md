---
title: Intermediate Rails
date: '2017-08-16 12:04'
time: '12:04'
tags:
  - Rails
  - Ruby
category: development
---

In my journey of developing rails, I always found it difficult to move from being an "Advanced beginner" to being an intermediate or mid-level developer. While that has been my title for a while I always had this feeling like I had not really mastered the concepts or moved on from that beginner stage. I always found it to be that there were so many beginner tutorials that explained ruby or rails at a 101 level and explained what OOP or MVC were but then you were on your own as a so-called "journeyman." Then there were all kinds of resources about how to do either super specific or advanced things with Ruby on Rails. There was kind of nothing to bridge the gap between the two sets of ideas except experience it seemed.

To my surprise I feel like my journey led me to a few big "AHA!" moments that I felt made everything click so I was better able to understand the more advanced topics and how everything connected. My goal for the next few months is going to be bringing these missing puzzle peices together for other developers and see if it really is an individual thing that clicks with expierence or if there is a missing chapter of the manual that could help many other developers.

## Where does this code go?

* Lookup all new vehicles
  * controller
  * model
  * test
  * View (Lazy)
  * Outside of activerecord?
  * Service Object
  * 12,000 line functions.php file
* Check if user is logged in
  * controller (or application controller)
  * view
  * User Model
  * Outside of app (3rd party api?)
* Import a CSV into database
  * service object

### Service Objects

Service Objects were a big part of the puzzle for me. This novel idea that if it doesn't belong in a model/view/controller or a helper or a config file, maybe you shouldn't put it there. Service objects are generally Plain Old Ruby Objects that do a specific task. ???


### Gems

### Engines

## There's a gem for that, too!

### Too much?

## Conclusion

For me, one of the biggest hurdles to reaching the next level of rails development was learning when it is appropriate to not use Rails at all. Use Plain Old Ruby Objects whenever it doesn't make sense for them to be Rails objects. Using a less is more approach to gems helps a lot too.

----

## examples:

### Quote
> "I need to clean it up a little first."

### P

I can't tell you how many times I've heard some variant of this when asking why doesn't a newer developer open source a project or why their Github is so empty. Just upload it. If you think it is messy or you are embarrassed of the code, one of three things will happen. 

### links

[google](http://google.com)

### lists

* unordered
* unordered

1. ordered
1. ordered
