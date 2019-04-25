---
layout: essay
type: essay
title: Problem Solving with Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2019-04-24
labels:
  - Software Engineering
  - Design Patterns
  - Learning
---
<img src="../images/Design-Pattern.png" width="600" height="266">

In the most general sense, design patterns are well known and trusted templates for solutions to a class of problems.  In life, we naturally pickup these solutions because its human nature to mimic what we see and the solutions to problems we see most often are the ones that are known to be successful.  In software development, we do much the same when we look for working code and then implement it ourselves.  If we approach problem solving by consciously thinking of these design patterns, we can easily implement the best designed solution to our problems.

## Learn from your seniors
The concept of design patterns is important to the field of software development because of the size, complexity, and cooperative nature of development.  Why bother reinventing the wheel when you can just use a wheel?  As long as you know about the wheel, then solving transportation problems becomes easy.  This is why learning the design patterns common to software development are so important.  Large and complex programs can be separated into smaller design patterns that work together.  Need a way to handle events or be reactive? Use the observer model.  If your developing a web page, you should be familiar with MPC and segregate your frontend and backend.  Singletons are great if you need a lazy global variable but lack the support for it.  The more design patterns you know, the faster you can design software.

## Common perspective
Design patterns also benefit from common knowledge.  Team members working on the same piece of software have a shorthand and implicitly understand the underlying design of what they are working on.  When working with my team on our final project, we know that meteor uses a publish subscribe system.  So when one of us creates a collection, all anyone needs to know to use it in their own code is the name of the publication and the schema.  We also design our UI purely for user interaction with the backend as a black box that passes us what we need to display to the user and visa versa, so we can work on them completely separately following the MPC design pattern.  Overall, recognizing and implementing design patterns is a valuable skill for software development.
