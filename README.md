# Depricated in favor of The Law of Information Locality

Current Version of this Information: [Howland's Law of Information Locality](https://github.com/ghowland/LawOfInformationLocality)

I wrote this up to explore and publicize this idea, to find prior art.  I didn't find any prior art, so in order to create a label for it, I created a law.

# Original Exploratory Article...

# Statistics, And Other Non-Local Data Sources, Are Invalid When Population Size Is One And Accuracy Matters

This is a logical essay to assert that all statistics, and other sources of non-local data, are invalid when the population size is one and accuracy is important.

By accuracy being important, I mean:

- That it is critical that the decisions made from whatever information gathering methods are used...
- ...Provide the highest chances to succeed with the specified goals...
- ...Yielding the best results possible...
- ...Under the realities of the situation.

In short, when you really want whatever it is you are going to do, to work.

My assertion is that:

- When the population size is one...
- ...And you care about the accuracy of your data to be as precise as possible...
- ...Only local information is valid...
- ...And no external data can determine anything about this single unit's single instance (now)...
- ...Because all it's state data is unique and local to that single unit's single instance's current state.

To lay out the requirements for this to be true:

- You have a single unit at a single instance in time.
- You need to make a decision about this unit that requires accurate data, because it's important that whatever it is that you are going to do needs to provide a result that meets your goals.

Another way to say "Statistics are invalid", might be to say "No external data is valid, only local data is valid".  Statistics are frequently the form that external data is presented in, so I have prefixed the title with this assertion accordingly, but all external data is the issue, since external data has no correlation to the current state of a single unit.

This assertion is not to take anything away from any of the areas where statistics is valid, but only to cover a point where statistics and other external data is being used invalidly, as the situation requires only using local data.

I have created a thought experiment to create a real-world-style scenario for this situation, to hopefully provide a way to visualize why only local data is useful in a situation where there is a single instance of a single unit being inspected:

## Initial Scenario

1. You are in a car, in the center of a wide one-way road, with no obstacles or other cars around you, and no turns or other decisions to be made for a long time.
2. You are going straight, there is no reason to change direction.  The initial situation is stable, and without obstacles.  It's legal and OK to be driving in between lanes for this example.
3. No other options are available, such as "Slow down", "Stop" or "Transform and Fly Away".  Only "Turn Right" and "Turn Left" are available options for this example scenario.

![Initial Scenario](images/stats_invalid_00.PNG)

## Problem Introduction

1. From the Initial Scenario...
2. An obstable is introduced ahead of the car's path.
3. There are 2 options available in this scenario:  "Turn Right" or "Turn Left"
4. Can you determine, through use of statistics, for this given problem, whether one should statistically "Turn Right" or "Turn Left"?
5. Given unlimited resources, could you design an experiment and create a set of statistical data that would allow you to determine whether you should statistically "Turns Right" or "Turn Left" for this specific case?

![Problem Introduction](images/stats_invalid_01.PNG)

## Assertion

1. Because the data available is local to the single problem case (an obstacle in front of your car, right now), the only valid data is local to the situation.
2. No amount of data about other situations will tell you whether you should "Turn Right" or "Turn Left" in this situation, because that information would be based on data from different situations, where those obstacles and those cars had different relationships between them, than your car and the obstacle currently in front of it.
3. Only this unique situation will have the exact data that you need to determine a correct action, which is based on the data local to your situation:  Where the obstacle exists in relation to your car.
4. The only data relevant to making this decision will come from the local data, which is:  If the obstacle is closer to the Right Side of the car, you should "Turn Left" to better avoid it, and conversely if the obstacle is closer to the Left Side of the car, you should "Turn Right" to better avoid it.  If the obstacle is directly in the center of your car, then either option is equally valid, so you can "Turn Left" with the maximum available safety.
5. No amount of non-local data that could be analyzed would be able to give anything but pure chance as to the location of the obstacle in relation to your car, to determine which direction is best to avoid the obstacle.
6. Additionally, external information has the potential to be biased through assumptions in test formulation, which are unrelated to the physical location of your car and the obstacle, in this moment in time.


## Summary

There are many situations today where statistics and other external data are applied to critical single case scenarios, without the acknowledgement that the comparisons may be invalid as the external data bears no correlation to the precise immediate state of the subject matter.

My hope, if this assertion is not falsified, is this the improved information that comes from further discussion will provide another tool when evaluating changes to help provide increased efficiencies.

If you can provide a falsification for this assertion, I am happy to ammend it or rescind it accordingly.  Feedback is very welcome, as I am looking for a solution to a problem I have found, and I think this assertion gets things moving that direction, but if I am wrong I am happy to change direction to be less-wrong.

## Related Information

The below sections contain material related to this problem.  I am looking for existing art that already describes this problem, as I am not trying to invent something new, but simply come up with a single rule for why non-local data cannot be applied to some problems.

### Criterion is Independent of Predictors

Criterion is independent of the predictors: P(Y) = P(Y|X)

This might explain this situation, looking into whether this covers the same cases as the problem I am trying to solve.

### Comparison to the Ecological Fallacy

The [Ecological Fallacy](https://en.wikipedia.org/wiki/Ecological_fallacy) is a description of a problem where you are trying to get information about an individual from the group's information.

This fallacy has a similar to the problem I am presenting here, but does not align to the problem in a super-set manner, and does not account for many of the problems that are related to uniqueness of information.

The Ecological Fallacy says, to paraphase, that you cannot infer data from a group for an individual, even if the individual is in that group.

This is similar to the problem I am stating, in that one is trying to take information out of external data and apply it validly to an individual, and the external data is simply not going to represent this single unit, because they are all different and contain their own local state.

The Ecological Fallacy does not match up because it is not focused on the uniqueness of the individual's data directly.  The reason that I am asserting "Statistics and External Data Are Invalid If You Care About Decisions Around A Single Population Unit's Accuracy" is that it relates to a real-world problem that we have, which is that we have single instances where we need to make an accurate decision, based on the best information, which must be local information.  Using non-local data means we are not basing our decision on the facts at hand (local data), but data that is certainly not the facts at hand (external or non-local data).

If you would like to see the discussion on Reddit about this, you can find it here:

https://www.reddit.com/r/statistics/comments/4299px/statistics_are_invalid_when_population_size_is/
