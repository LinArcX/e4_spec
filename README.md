# e4

- expectations: your daily tasks.
- essentials: input(prerequisites) of each expectation.
- experiences: output(result, outcome) of every expectation.
- expansions: your future wishes that someday can be your daily tasks.

A personal approach to managing time.
	- If you can manage time, you can manage your thoughts.
		- By managing your thoughts, you can manage your life in a better way.

Tip: This is an improved version of [memento](https://github.com/LinArcX/memento).

## Quote
> “Memory’s not perfect. It’s not even that good. Ask the police. Eyewitness testimony is unreliable. The cops don’t catch a killer by sitting around remembering stuff. They collect facts, they make notes and they draw conclusions. Facts, not memory.”

Leonard Shelby

![Demo](./assets/memento.jpg)

## Definitions
- In normal life we strongly believe that we should separate time into different categories: _past_, _present_ and _future_.
- But time is more rebel that we can imagine. So we should trap it in more short-period boundaries. I call these boundaries: **TimeBoxes**
- For simplicity, we assumes each day is a separate TimeBox.
- You want to plan for your next project? It takes 12 days? No problem. Just reserve some hours of each day(Sequential or non-sequential) for 12 days.
- In the beginning of each day(or a night before), you define your expectations(Daily schedule)
  - expectations have two aspects: 1. essentials, 2. experiences
  - expectations can have **Priorities**.
  - expectations can have reminders.
  - expectations can have estimated duration or fixed start-end time.
  - by forcing yourself to specify your expectations daily, you always have this chance to review yourself and your progress, so you can improve your methods.
- Before the end of day(or after ending each expectation), you should write what did you get from each expectation (outputs or results)
  - These are become your knowledge center. You can write them as single notes, as diagrams. You can use techniques like MindMapping or Zettelkasten to store your experiences.
  - Experiences are treasures that you can use in your future timeboxes.
  - Each experience can have some inputs.(You will use them to achieve the outputs)
  - You can rate your expectations and explain why you are/aren't satisfy for the result.(It'll help you for future timeboxes planning)
- With this approach, you are forced to re-organize your mind every day!

## Results
- Past are just timeboxes that are less than current timebox.
  - **Experiences** are the outcome of timeboxes in the past.(that you can use for your future timeboxes)
- You are always planning. Either for your current timebox(today) or for future timeboxes.
- **Expansions** are just your pure ideas that you wish to do in future. They can be transform to **Expectations** if you just assign them to timeboxes.
	- You can prioritize your Expansions.

## Caveats
- But time is not always manageable. Right?
- You can get sick. There may be an earthquake in your city. Or any other accidents that are beyond your control. How deal with them?
  - I call these things: **Accidents**.
- So you should have **Buffers** in your timeboxes to deal with **Accidents**.
- Assign a portion of your day to buffers.(something between 5% and 20% of day is reasonable. It's up to you!)

## Keywords
- Expectations
- Experiences
- Expansions
- TimeBox
- Day
- Outcome
- Priorities
- Plans
- Accidents
- Buffers

## Implementations?
Maybe the simplest way is to write your own timeboxes on a paper and start following them :)

But the better way is to transform this approach to a software. So if you're a programmer, you're free to implement this specification
in any kind of software form that you like. (A console app, an android app or a desktop app)

### Console app
- e4: a script to create/manage/search expectations/essentials/experiences/expansions.
- zk: a script to manage zettelkasten stuff.
- spr: a script to work with SpacedRepetition.
- mm: a script to implement MindMapping technique.


## Challenges
Q: How to integrate Zettelkasten approach with this model?

A: Zettelkasten is about gathering knowledge in an efficient way. So it's related to your "Experiences".

Q: How to integrate SpacedRepetion with this model?

A: You can SpacedRepetition technique as one of your expectations in your daily routine.

Q: How to integrate mind-mapping approach with this model?

A: MindMapping is all about understanding a subject better. So you can use it as a tool to enrich your experiences.

## Contribution
- If you have any idea to improve this approach, please let me know :)
