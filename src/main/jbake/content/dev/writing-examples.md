Title: Writing Presentable Examples

Writing an example is easy.  Any example is a good one.  The more the better.

Writing examples that can be used in a presentations is hard.

Some basic guidelines of writing examples:

 - focus on one idea per example
 - keep examples short
    - one test case
    - minimal code to make the point
 - avoid showing an entire API in one example, if possible
 - be conscious of the cost of "setting the stage"
 - if examples get too big, split it

# Noise vs signal

It takes time to learn the example scenario (noise).  You need to learn the scenario before you can start to see the important parts (signal).

Be very mindful of your noise to signal ratio.

Example scenarios do not need to be believable and should not be elaborate.  Get to the point in as few classes as possible.

You should be able to explain the entire example in two minutes.

# Five ways to do the same thing

If there are five ways to do the same thing, avoid making five different scenarios.  Copy the example to a new directory, and tweak it to show the variation.

So say you used objects `Green`, `Square` and `Checkers` to show the basic concept and you wish to show the next variation of that same concept.  It is tempting to add to the same
example objects `Yellow`, `Triangle` and `PolkaDots`.

Avoid that.  Copy `Green`, `Square` and `Checkers` to a new example, change the package name, and update the few lines needed to show the difference.

Where does your eye focus?

 - 934 + 55 = 989
 - 513 - 19 = 494
 - 468 * 44 = 20592
 - 708 / 89 = 7
 - 401 % 63 = 23

How about now?

 - 102 + 35 = 137
 - 102 - 35 = 67
 - 102 * 35 = 3570
 - 102 / 35 = 2
 - 102 % 35 = 32

The intent of the second set of numbers can be easily guessed.  An explanation that it is about the math operators confirms that and locks it in your brain.

When presenting, you only get so much time to show people ideas.  If they have to learn a new set of names and understand their relationship on each tiny variation, it severely
impacts their ability to see what is supposed to be the same and what is supposed to be different.  As a presenter this means you must show less and what you do show will be shown
less clearly.

When names and scenarios are consistent, the variations jump out quickly and with impact.

If there are five ways to do the same thing, show the same thing five different ways.

# Short Class Names

You don't need to document the example with the class name.  Class names that are a mouthful cannot be effectively used in presentations or screencasts.

Try to stick with one or two word class names.  Three tops.

Avoid:

 - `BeanWithTwoDecoratorsAndOneProducerMethod`

Try instead:

 - `BlueBean`

Shorter names can be easier for all sorts of reasons.  Less words to keep "floating in the head" when trying to truly see an example.

Using the numbers from the previous section, which is easier?

 - 102 + 35 = 137
 - 102 - 35 = 67
 - 102 * 35 = 3570
 - 102 / 35 = 2
 - 102 % 35 = 32

Or:

 - 12 + 3 = 15
 - 12 - 3 = 9
 - 12 * 3 = 36
 - 12 / 3 = 4
 - 12 % 3 = 0

There's a finite amount people can keep in their head, save space for the important stuff.

