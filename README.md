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

Once we know what we want to measure, where do we get this data from and what hardware do we use to process it into useful information?
This is particularly difficult to answer when the data being considered is generated from a large body of developers who may be spread across
the globe. Large multination corporations or dealing with open-source projects could involve huge amounts of data which couldn't simply be
handled by a single personal computer.

### GitHub API

One easy to access source of developer data is GitHub. They provide an API to access user data such as repositories, contribution history and
collaboration between users. The shear number of publicly available user repositories provides an incredible amount of software engineering
data. This data can be analysed to better understand developer behaviour and testing various approaches to measuring software engineering.
Improving your understanding of developer behaviour is crucial when working with and planning for professional developers on your team.
Intelligently balancing workload and assigning tasks to members of your development team can really help with overall productivity.

### Distributed Computing

When dealing with large volumes of data, one possible approach is to use distributed computing. As a vast majority of the tasks associated
with processing software engineering metrics are unrelated, it is very effective to split up these tasks between multiple computers.
This network of computers should scalable if more processing power is required. Additionally, by spreading this network across the globe,
we can take advantage of locality of data to speed up access via the Internet. Finally, storing processed data provides redundancy in
case of critical device failure or disconnection.

### Cloud Computing

A similar concept is cloud computing. Companies manage and rent their online services which provide hardware to perform various kinds of data analysis.
This makes it easy for organisations to perform large data processing tasks without handling the associated hardware. Additionally, such services can
prove to be cheaper alternatives than running your own as these companies take advantage of virtual server instances. Such a system allows many users to
be allocated their own resources on huge, scalable machines.

## Data Computation

With access to all this developer data and hardware to handle it, we now need to figure out how to process it into a presentable and easily digestible form.
When simply examining the raw data without first processing it can be difficult to understand and compare, especially between many individuals.
We can perform computation on this data with various techniques in order to generate overall pictures and pick out trends which may be useful.

An obvious computation of some metrics is to simply tally the data entries up. It can be useful to count the total number of commits made by a developer or the how many
repositories a user has contributed to in a specific programming language. Similarly, we can compute ratios between data points using basic division. Some examples
include average number of lines per commit and issues resolved per day. Both of these methods convert easily to graphical representation which
can prove vital in presenting understandable information. This can then also be extended to examine how these values change over time, which can be useful for identifying
trends to correlate with past events and help predict future changes.

Another data computation technique used today is by utilising artificial intelligence, or AI, to find patterns in data. Such examples include machine learning algorithms which attempt
to improve upon themselves with something akin to trial and error and expert systems which try to simulate the knowledge of a human who has expert experience in data.
Both of these approaches are used widely today for a variety of uses. In the context of software engineering productivity, AI can be used to find relationships in data that would otherwise
have been missed by a person. This pattern finding ability can be scaled to cover huge amounts of data. These relationships are extremely useful when trying to identify trends and
factors which affect developer productivity. Unfortunately, AI also introduces complications with spurious correlation and false identification. Such errors can be hard to recognise
and may lead to misinformed decisions. Additionally, there is a worry that modern research into artificial general intelligence poses a threat to human existence through technological singularity.

## Ethical and Moral Issues

There has been a lot of outcries about privacy issues and personal data collection over the last decade, particularly in regards to social media corporations.
Does the practise of gathering and processing of developer's activity and personal data go against ethical and moral standard?
Here, there is no objective answer because the answer depends on your opinion and personal beliefs.

In my opinion, such data collection is only acceptable if it is justifiable to the developers themselves.
While I agree the gathering of such metrics will help in overall productivity through better resource allocation and planning, I would be against such a practise if the developers
didn't see any advantage from the analyses of their own data. My reasoning is that personal data "belongs" to the person who made it and has some arbitrary value.
If you want to take that data and use it to produce something of real value, then some form of trade must be negotiated with the owner.
While it's not reasonable to expect every individual to actually value their own data, I believe everyone is entitled to at least some of the value extracted
from the gathering of their personal data. In terms of software engineering, the collected data could be used to assist a developer with problems previously
encountered by open-source developers (see GitHub Co-Pilot), identify weak areas of knowledge with recommendations of improvement and connect developers together
who would benefit from mutual collaboration. Alternatively, developers could simply be rewarded monetarily.

A practical solution is for collection and analyses of personal activity data to be an opt-in choice for developers with an explanation of how the data will
be used to benefit the company. Developers should have the choice to access and remove this data at any time. Additionally, an option to appear anonymised in
this data would be greatly appreciated so that general trends and patterns can be identified but no single individual can be held accountable for their activity.
Finally, the security and privacy of this data is paramount and cannot be allowed to leak publicly.

*Ted Johnson\
TCD 19335618*
