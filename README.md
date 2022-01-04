# Measuring Software Engineering

> You Get What You Measure

## Contents

1. [Software Engineering Metrics](#software-engineering-metrics)
2. [Platforms For Data Processing](#platforms-for-data-processing)
3. [Data Computation](#data-computation)
4. [Ethical and Moral Issues](#ethical-and-moral-issues)

## Software Engineering Metrics

Before we can measure the software engineering productivity of a developer, we must first decide what to measure.
It is extremely important to consider what metrics you are going to use to examine the productivity of a developer,
as many issues can arise with your analyses. In this section, I am going to outline a couple of commonly used metrics
and discuss their individual advantages and disadvantages.

A decent criteria for judging the effectiveness of a metric is if is easily measurable, actionable and reflects value
added to the business. By measurable, I mean the metric can be extracted from the activity of the developer without
interfering with their workflow or impeding their productivity. If a metric is actionable then the value of that metric
can be actively improved by the developer. Finally, a metric should be related to value added to the company, be this
an increase in revenue or improvement to a company's commercial product.

Finally, we must also consider an important factor which always come up when discussing software engineering measurement:

> You Get What You Measure

This simple line might seem fairly innocuous but actually presents a major problem when trying to measure software engineering productivity.
In fact, this issue arises when you attempt to measure productivity anywhere. When you begin to measure aspects of a developers workflow
to determine their productivity, the developer may then go out of their way to artificially inflate this specific aspect in order to raise
their preserved productivity. This practise is called gamification of metrics and can pose a difficult challenge to productivity analysts.

### Lines of Code

Probably the most trivial metrics that can be measured involves lines of code, or LOC.
We can count either the total number of LOC belonging to a developer currently in the project or count the LOC that have been
changed by the developer.

While easy to do and might provide a superficial understanding of a developers productivity, this method should not be used in
almost any scenario. It's widely understood that a good programmer will try to write concise and simple code that is easy to
maintain. By introducing this metric, you would be encouraging overly verbose code. Additionally, such a metric doesn't actually
provide much insight into how much work the developer might actually be doing. Boilerplate and trivial code can be excessive in
some projects so it would be unfair to consider all LOC of equal value.

### Commits

An extension of the above metrics is to instead measure the number of commits to a repository a user has made. This suffers from
many of the issues discussed as well. A developer can choose to try boost their commit count by making many small commits when
a single commit would suffice. However, this is actually a beneficial aspect to increase (Commit early, commit often) but is still
an example of gamification which should be avoided.

Similarly, a single commit cannot be regarded to have the same value as another commit. As such, judging a developers performance
on their rates of committing is not advisable. It could serve as a supplementary metric along with LOC in each of these commit.

### Issues

Another abstraction of the above metrics is to instead record issues. Metrics involving the number of problems with the code base raised
and resolve is actually quite a good indication of productivity. Here, we can measure how often a developer finds and communicates an issue
to the team, the rate they resolve issues at and the time taken to complete an issues.

As with the previous metrics, these also suffer from treating every issue raised and resolve as the same. Issues can have widely different
scopes and work to resolve so this metric would encourage developers to take on small and easy issues while avoiding larger projects.
However, that being said, it may be possible to instead encourage larger issues to be split up into many smaller issues, which is a key
tool in all engineering fields.

### Testing

One more example of metrics that may be measured is to do with code testing. Testing your code should be part of any project anyway but
is it feasible to use this work as an indication of productivity? The most obvious value that can be measured is the number of tests
the developer passes. This is clearly a very flawed metric to base productivity off of as whether a developers contribution passes
tests does not have much bearing on if the contribution has much value. Additionally, test-driven development advises to write tests
before writing an implementation. This approach would conflict with this metric.

Another more reasonable metric to consider is test coverage. We can record how much of a developers code is being covered by their own
tests. This actually does at least do a good job at encouraging useful contributions - Having higher test coverage is a step in the right
direction. It is also a good indication that the code that is being tested is well-written and does what it's meant to.
However, this metric does not consider the quality or effectiveness of these tests. Again, I would imagine this metric would be best used
within a collection of other metrics as individually this does not provide a huge amount of value.

## Platforms For Data Processing

TODO

### GitHub API

TODO

## Data Computation

TODO

## Ethical and Moral Issues

TODO

*Ted Johnson\
TCD 19335618*
