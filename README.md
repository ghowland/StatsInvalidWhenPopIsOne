# Statistics Are Invalid When Population Size Is One

This is a logical essay to prove that all statistics are invalid when the population size is one.

My assertion is that when the population size is one, only local information is valid, and no external population statistical values can determine anything about this single unit of population, because all it's data is unique and local.

Let's start with a problem example.

## Initial Scenario

1. You are in a car, in the center of a wide road, with no obstacles or other cars around you, and no turns or other decisions to be made for a long time.
2. You are going straight, there is no reason to change direction.  The initial situation is stable, and without obstacles.  It's legal and OK to be driving in between lanes for this example.
3. No other options are available, such as "Slow down", "Stop" or "Transform and Fly Away".  Only "Turn Right" and "Turn Left" are available options for this example scenario.

![Problem Introduction](images/stats_invalid_00.PNG)

## Problem Introduction

1. From the Initial Scenario...
2. An obstable is introduced ahead of the car's path.
3. There are 2 options available in this scenario:  Turn Right or Turn Left
4. Can you determine, through use of statistics, for this given problem, whether one should statistically "Turn Right" or "Turn Left"?
5. Given unlimited resources, could you design an experiment and create a set of statistical data that would allow you to determine whether you should statistically "Turns Right" or "Turn Left" in this specific problem case?

![Problem Introduction](images/stats_invalid_01.PNG)

## My Conclusion

1. Because the data available is local to the single problem case (an obstacle in front of your car, right now), all the data is local to the situation.
2. No amount of data about other situations will tell you whether you should "Turn Right" or "Turn Left", in this situation, because that information would be based on data from different situations.
3. Only this exactly single (one) case will have the exact data that we need to determine a correct action, which is based on the data local to our situation:  Where the obstacle exists in relation to your car.
4. The only data relevant to making this decision will come from the local data, which is:  If the obstacle is closer to the Right Side of the car, you should "Turn Left" to better avoid it, and conversely if the obstacle is closer to the Left Side of the car, you should "Turn Right" to better avoid it.
5. No amount of non-local data that could be analyzed would be able to give anything but pure chance as to the location of the obstacle in relation to your car, to determine which direction is best to avoid the obstacle.
6. Additionally, external information has the potential to be biased through the test formulation or any frames of reference in creating the test, which are unrelated to the physical location of your car and the obstacle, in this moment in time.

My assumption is that this type of transition between stastics ability to be used validly would be something like an exponential curve at the point where the population becomes large enough to be statistically signficant.  This may actually be more like an S-curve though.  I will leave that as an exercise for other people, but here are some simple example exponential graphs just to add a visual-style explanation of this validity curve.

Note that I write "Possibly Valid" as Validity approaches 1.0, as there are other reasons for statistics not to be valid.  For example, it was created out of data that does not align to the current data, or there are known demographical or other differences which will invalidate the comparison.  Population Size of 1 only ensures invalidity, and having a large population allows for possible validity.

### Normal Y-Scaling

![Problem Introduction](images/stats_validity_normal.png)

#### Logarithmic Y-Scaling, since Normal Y-Scaling is almost completely at 0.0 until the very end

![Problem Introduction](images/stats_validity_log.png)

## Further Thoughts

To go into completely logical space, populations of 0 are also always invalid.  But if you could have a negative population, would all population sizes be invalid?  I would assert that at least a population of -1 would be invalid, due to the same reasons as positive 1 population: specificity and local information.

## Scope of Change

There are many situations that are currently using statistics to apply to single case scenarios.

Every time someone applies a statistical value to a single case, they are ignoring all the local data available to them, and instead choosing to use external data instead of the local data to make a decision.

Just like in the case of the car with an obstacle in front of it, which is specifically meant to be a very limited situation with a single axis of choice (right or left), and a single problem (obstacle position in relation to right or left side of car), most problems have many additional data points which create a complex network of total working data to make a decision.

However, it does not matter how many data points there are in a problem, or how complex the network of relationships between those data points are, when you are working with a population size of one, it has a 100% unique set of data, which can only be applied to a large population of data in a statistical way, but cannot be reversed from a stastitical population result into a valid comparison with a single unit.

Statistics takes individual data points, and creates a new single aggregate data point, which can be validily compared to other populations, and individuals can be compared to the statistical results to determine how they match up to the statistical population set, always going from more-specific to less-specific.

When trying to use statistics against a population of one, then we are trying to use less-specific information to get more-specific information, is not possible, because that is creating accurate data from nothing.  Statistics is a lossy operation, and cannot be reversed to get better results than looking at the single case.

I believe we need to study this more thouroughly, as it should be provable with the correct kinds of studies that the efforts to treat problems (of individuals) with statistics yields worse results (because they are invalid) than making decisions based on local data.


