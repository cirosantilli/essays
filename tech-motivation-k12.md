# Tech motivation K12

What you can say to K12 people to motivate them to learn Math, Physics and the other "hard" sciences.

## Control the future

Technology is the art of controlling the future to make it better.

Stop and think: if you could control the future, what you do? Wouldn't that be great?

Examples:

-   I want to get to work faster.

    If I walk it takes 30 minutes.

    If I take a car, it takes 15 minutes.

    Therefore the car (technology) allowed to change my future: one I have it I will take 15 minutes less every day.

    My future improved!

-   I want a cheaper newspaper.

    If I go to a newsstand, I pay 1 dollar.

    If I subscribe to a website, I pay 50 cents.

    Therefore the website (technology) allowed to change my future: I will gain 50 cents every time I read the newspaper.

    My future improved!

## Simple and cool technological questions

To understand why, see:

- will my airplane fly? <http://www.youtube.com/watch?v=-lDbseYB7Sc>

- will my car protect its passengers? <http://www.youtube.com/watch?v=NrvuFiDqn5A>

- will my motor spin? <http://www.youtube.com/watch?v=QZOZw7bV534>

- how will I move all those heavy pieces? <http://www.youtube.com/watch?v=-_SxW_7v9is>

- what should I take on my trip? <http://en.wikipedia.org/wiki/Knapsack_problem>

- what is the shortest path to deliver those goods? <http://valis.cs.uiuc.edu/~sariel/research/CG/applets/tsp/TspAlg.html>

## Holy triad

Technology is based on the holy triad:

- [model](#model)
- [mathematics](#mathematics)
- [computer](#computer)

## Model

A model is a piece of information that predicts the future.

It takes inputs:

- what is the current state? What was the past state?
- what is the action?

It gives the output

- then the new state in the future shall be XXX

The question is then:

> If I am on a given state, what action should I take to go to the best state possible?

This called *optimization*!

### Example: girlfriend

- Current and past state: You have a girlfriend. You two are not very happy together.
- Action: you kiss another girl.
- Future state: you don't have a girlfriend anymore.

If we change the action however, the future state changes!

- Action: you give your girlfriend flowers and chocolate
- Future state: You two are very happy together!

If we change the current state, the future also changes:

- Current and past state: You have a girlfriend. You two are very happy together.
- Action: you kiss another girl.
- Future state: You two are not very happy together.

### Example: car on road

- Current state: You are in a city A.
- Action: you drive at 100 km/h during one hour.
- Future state: you are 100 km from city A.

If we change the action however, the future state changes!

- Action: you drive at 200 km/h during 2 hours.
- Future state: You are 400 km from city A.

If we change the current state, the future also changes:

- Current state: You are 100 km from city A.
- Action: you drive at 100 km/h during one hour in the direction oposite from A.
- Future state: you are 200 km from city A.

### Precise models

If you forget preciseness, all things we do in life counts as technology:

- boyfriends and girlfriends model people and what are the effects of their actions.
- drivers model car speeds and road lengths
- lawyers have a model for society and the law system
- artists have a model of what humans think is beautiful and a model for paints and brushes.;

So how is technology different from art?

The question is subjective and imprecise, but the answer criteria is simple: how good is your model, and how fast does it change with time.

What is understood to be technology is based on models that give very good results, and change very little with time. All of those methods can be seen as sub-branches of physics:

- mechanics
- thermal
- fluids
- electromagnetism
- quantum
- chemistry: same as very complicated physics

    Because of complications, our models are not perfect.

- biology: same as very complicated chemistry

    Because of complications, our models are not perfect.

It seems that physics never changes!

For some areas of physics, our models are close to perfection.

### How to write a model down

Models can be written in many languages such as English.

Unfortunately, English is too imprecise for certain models (position of a robot arm)

The best way to write models is [mathematics](#mathematics).

### How to create a model

Do one million experiments with different inputs which you can control.

Measure the output.

Write an equation that predicts the output given the input.

## Mathematics

Mathematics is precise, this is why it is good to write models with it.

What does precise mean?

Precise means that if mathematics is writen properly on a computer, proofs can be checked on that computer.

To understand this precisely, you must understand *formal proof systems*.

But the implication is simple: there is no ambiguity or impreciseness possible.

The problem with mathematical models: sometimes you write an equation but solving it would take millions of stupid operations.

This is why we need [computers](#computer): computers can do those millions of operations for us!

### Approximation

For some mathematical problems it is impossible to precisely write down a solution. Ex: differential equations.

For other problems, find the exact solution would take too much time, but an approximation is *much* easier to find. Ex: discrete optimization problems.

The solution: find an approximation of the solution, which is good enough for practical purposes!

## Computer

Computers can manipulate information (copy, transfer, delete) in a way that is *very*:

- fast
- cheap
- robust, i.e. without few errors

As long as we can write our problems into lots of very simple operations, such as sums or subtractions.

This allows us to:

-   solve our models.

    The solution of many models comes down to making a huge number of stupid operations. Ex: solving differential equations.

    Computers are perfect for that.

-   act on a physical systems.

    To modify the future we some physical systems, we have to do

    - lots of operations
    - very quickly
    - at very precise times

    in a way that would be impossible for humans to do.

    Just think about how you hard disk head moves thousands of times per second to precise disk locations!

    This is another major application of computers: control physical systems precisely.

### Kids

Hardware or not? I'd rather not, too much complication + cost.

Which language? JavaScript because everyone has the interpreter + GUI (browser JS engine + HTML renderer + canvas). Yes, stdout is harder to see... but so be it.

- https://thejournal.com/articles/2013/10/23/6-tips-to-get-your-kids-excited-about-coding.aspx?=THE21
- https://www.quora.com/What-is-the-best-way-to-get-your-kids-interested-in-coding
