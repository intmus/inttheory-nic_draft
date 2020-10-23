---
layout: chapter
title: Lesson 2e - The Overtone Series
abc: true
---

<!-- Needs HUGE OVERHAUL. Overtone Series used to be in Unit 8 while discussing harmonic function, but it makes more sense to have it here immediately following key signatures. Will also require alteration of assignments to include overtone series. All material that used to introduce these ideas from 2d Key Signature topic have been copied at the bottom of this page.

It would be best to have a unit on keys, another unit on key signatures (that includes the "tricks" for finding key signature tonics), and then a third unit on the overtone series and its determining role in intonation. You will need to move all of this around, and create a new topic for just key signatures. Unless you decide to re-incorporate all of the key signature stuff back into keys, but that seems unlikley to be the best strat. For the overtone series, keep everything here until right after the Physics of Music section starts, and then bring in your material on how the ratio between waves creates intervals, and then use that to discuss just versus equal temperment-->

You have likely heard the terms *overtone series* and *harmonic series* while discussing music, but unless you have studied them previously, you may not realize the importance of this concept in creating tonality. The overtone series occurs naturally in all non-synthetic tone production. When a person sings, a harmonic series is present above every pitch. When any woodwind, string, or brass instrument creates a pitch, a harmonic series is present above every pitch. Perhaps even more importantly for our discussions, we can study the acoustics--or the math--behind this overtone series to explain the fundamentals of Western harmony.

The overtone series can help you to understand:
- why we divide the octave into twelve parts.
- why we hear some intervals as consonant and others as dissonant.
- how we determine if an interval is in tune.
- why we use a harmonic system based on perfect intervals and thirds.

## The Structure of the Overtone Series

The overtone series is a series of intervals, or a *harmonic series*, above a given pitch. We call the lowest pitch the *fundamental*, and every tone above it is considered an *overtone*. In the example below, `C2` is the fundamental, `C3` is the first overtone, `G3` is the second overtone, and so on.

You may also describe the tones of the overtone series by labeling each overtone as a *partial*. In this system, the fundamental is considered equal to all other tones, so it is labeled as the first partial. In the example below, `C2` is the first partial, `C3` is the second partial, `G3` is the third partial, and so on.

For the example below, determine the numbering for each of these notes as both overtones and partials. Then practice transposing the entire series to other pitches.

{% capture ex1 %}X:1
T:The overtone series
M:2/2
L:1/2
K:C
V:1
x x x x E G _B c d e ^f g|]
V:2 clef=bass
C,,C,G,C x x x x x x x x|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Bernstein on the importance of the overtone series

Next, please watch this wonderful video of Leonard Bernstein explaining how the overtone series explains harmony's evolution throughout the ages. Keep in mind that each evolutionary step he discusses adds another partial from the overtone series.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Gt2zubHcER4" frameborder="0" allowfullscreen></iframe>

### The Physics of Music

The division of the octave into twelve parts is our brains' interpretations of a simple mathematical phenomenon. When the frequency of a soundwave doubles, our brains hear those two frequencies as sharing some fundamental commonality, so it interprets those two pitches as the "same" but separated by an octave. Therefore, octaves always have a 2:1 ratio. (A110, A220, A440, and A880 are all `A` separated by octaves.) The next two simplest ratios ares a 3:2 ratio and a 4:3 ratio, which create a perfect 5th and a perfect 4th respectively. 

The importance of these ratios is most easily observed in the circle of fifths. If you begin on any pitch-class and begin moving by ascending perfect 5ths (or 4ths), you will find yourself back at the beginning after cycling through all twelve pitch-classes. We call this the circle of fifths.

C - G - D - A - E - B - F-sharp - C-sharp - G-sharp - D-sharp/E-flat - B-flat - F - *C*

Perhaps more important for our discussion, though, is what happens when we introduce a diminished 5th into the pattern. Try this quick exercise:
1. Choose any starting pitch, and then write your starting pitch and the next six pitches from the circle of fifths on a separate piece of paper.
    - If you've done this correctly, you should have one pitch for every letter name. e.g. one 'A', one 'B', etc.
2. Choose any pitch within your seven pitches, and lower it by one half-step thus creating the interval of a diminished 5th between it and the previous pitch.
3. We will consider the two pitches of this diminished 5th to be our starting interval. Starting with the first pitch after your interval, begin altering the pitches to create perfect 5ths based on your altered note.
    - For example, if you chose to alter A to A-flat, you would have created a diminished 5th between D and A-flat. You will then lower all pitches after A-flat to create perfect 5ths again, starting by lowering E to E-flat.
4. Continue lowering pitches (and creating perfect 5ths) through the circle of fifths until you wrap around to your original interval.
    - If you started by altering A, you created a diminished 5th between D and A-flat. You will then lower every pitch until you get back to D, but leave D unaltered. In this example, you would end with:
    D - *A-flat* - E-flat - B-flat - F - C - G
5. If you re-arrange the seven pitches that you've created, you will notice that you have created a diatonic collection of seven pitches.
    - Continuing our example that we started by altering A to A-flat, you can see that we have three flat notes, and if you use your knowledge of key signatures, you know that the major scale with three flats starts on the tonic of E-flat. If you re-arrange these pitches, you will see:
    E-flat - F - G - A-flat - B-flat - C - D

This slight change--the addition of one diminished 5th--creates the necessary tension for keys to function diatonically, so diatonic function could be described as a slight imperfection on an otherwise perfect series of intervals. 

This can be further shown by looking at the naturally occuring intervals if we write diatonic 5ths above the notes of a major scale.

{% capture ex2 %}X:2
%%staffsep 100%
T:Diatonic 5ths in the Major Scale
M:C
L:1/2
K:C
[CG] [DA]| [EB] [Fc]| [Gd] [Ae]| [Bf] [cg]||
w:P5 P5 P5 P5 P5 P5 d5 P5{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

Because we explored harmonic function in Unit 6, the tension provided by the one non-perfect 5th and its subsequent release should now be obvious.

Key signatures reflect the importance of the one non-perfect interval. When studying the consecutive key signatures, you should focus on *which scale degree* is changed between consecutive keys.
- When a sharp is added to a key, it always raises the 7th scale degree in the new key, thereby creating the new `ti`.
- When a flat is added to a key, it always lowers the 4th scale degree in the new key, thereby creating the new `fa`. 

### Order of sharps and flats

This directly reflects how diatonic function works; if we change *where* the one non-perfect 5th occurs, we change the key. We did not need to spend time determining the order of sharps and flats, because the class was already familiar with this from previous courses. It did not surprise them that circle-of-fifths plays a critical role in defining diatonic function and key signatures. The two orders are simply the reverses of each other. 
- Order of sharps: F - C - G - D - A - E - B
- Order of flats: B - E - A - D - G - C - F

## Conclusions

The *overtone series*, often referred to as the *harmonic series*, is a series of intervals built off of a pitch. There are two ways to label the overtone series. 
- Label the the first pitch of an overtone series the **fundamental** and every pitch above it is then numbered as an **overtone**.
  - Fundamental, 1st overtone, 2nd overtone, etc.
- Label each pitch as a numbered **partial**.
  - 1st partial, 2nd partial, 3rd partial, etc.

The overtone series built off of `C2` would be:

{% capture ex3 %}X:3
T:The overtone series
T:Labeled as a fundamental with numbered overtones
M:2/2
L:1/2
K:C
V:1
x x x x E G _B c d e ^f g|]
w: _ _ _ _ 4th 5th 6th 7th 8th 9th 10th 11th
V:2 clef=bass
C,,C,G,C x x x x x x x x|]
w:fund. 1st 2nd 3rd{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

{% capture ex4 %}X:4
T:The overtone series
T:Labeled as partials
M:2/2
L:1/2
K:C
V:1
x x x x E G _B c d e ^f g|]
w: _ _ _ _ 5th 6th 7th 8th 9th 10th 11th 12th
V:2 clef=bass
C,,C,G,C x x x x x x x x|]
w:1st 2nd 3rd 4th{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

The overtone series occurs naturally and can be explained mathematically, so it is one of the few objective ways in which we can discuss the origin of music. Any interval can be viewed as a ratio comparing the frequncies of the two pitches that create the interval. The simplest ratio, other than 1:1, is 2:1. For example, `C2` has a frequency of about 65.4 hertz (hz = vibrations per second), and `C3` has a frequency of about 130.8: a ratio of 2:1. When we hear two frequencies that have a 2:1 ratio, our brains interpret this as "the same pitch separated by an octave" -- an elegant solution to interpreting a physical phenomenon. This example demonstrates that all concepts associated with music, such as pitches, dividing octaves, intonation, etc., are human creations trying to organize and interpret the physical phenomenon of soundwaves entering our ear.

The overtone series orders intervals by decreasing size but increasing complexity. The first interval of the overtone series, a P8, is the "simplest" interval of 2:1. As the overtone series moves upward, each interval becomes smaller but more complex. A P5 has a ratio of 3:2, a P4 has a ratio of 4:3, a M3 has a ratio of 5:4, and onward. 

## Concepts derived from the overtone series

The overtone series is notable because:
- The overtone series is present above every note played by a standard musical instrument or the human voice.
  - When a person sings a pitch, we hear the fundamental as the pitch name, but the strength of each overtone above that fundamental determines many qualities that we associate with the pitch such as timbre.
- The overtone series is the basis for intonation.
  - Using the ratios from the overtone series, we can determine what is "in tune". For example, an octave is a frequency that is exactly twice as high as the given pitch, and a true P5 is a frequency that is 1.5 times higher than the given pitch.
  - Fixed pitch instruments (e.g. piano) use a system of *equal temperament* to play in all twelve keys without having to re-tune the instrument every time the key changes. This means that we intentionally tune these instruments "out of tune" when compared to the overtone series ratios, because being always slightly out-of-tune is a far better compromise than being perfectly in-tune sometimes and grossly out-of-tune at others.
- The overtone series defines why the octave is divided into 12 parts, because it is from the overtone series that we derive the circle-of-fifths. Please refer to the discussion of the circle-of-fifths and tonality in Lesson 2c. 
- The overtone series provides a visual example of why we find certain intervals more consonant or dissonant. 
  - We hear simpler ratios of intervals as consonant and complex ratios as dissonant. So intervals at the beginning of the overtone series represent consonant intervals, but as the intervals decrease in size as the overtone series moves upward, the ratios become more complex and therefore more dissonant.
- The overtone series provides a good foundation for voicing chords.
  - Idealized voicing for chords often mimic the overtone series by placing each voice along the overtone series of the lowest voice.

### Remembering the overtone series

There are many ways to remember the overtone series.
- The first is to remember the intervals. This is easy at the beginning of the series, but becomes repetitive and easy to mess up as the series ascends.
  - P8-P5-P4-M3-m3-m3-M2-M2-M2-M2-m2.
- You can also think of them as a sequence of scale degrees above the fundamental.
  - 1 - 1 - 5 - 1 - 3 - 5 - b7 - 1 - 2 - 3 - #4 - 5
- And for some, it is easier to divide the series into groupings. For example, when looking at the first 12 partials
  - The first four pitches are a tripled fundamental and one fifth. 
  - The second set of four pitches is a first inversion dominant triad built off of the fundamental. 
  - The final three pitches represent `re-mi-fi-sol` or the beginning of the Lydian mode of the fundamental.

When looking at this final method for remembering the first 12 pitches of the overtone series, I find it fascinating that each group of four pitches implies a different key area:
- The first four pitches strongly imply a key that uses the fundamental as tonic.
- The next 4 partials imply a key with a tonic based on the *subdominant* of the fundamental, because the dominant seventh chord would be a V chord in the key of the subdominant.
- The third set of four paritals imply a key with a tonic based on the *dominant* of the fundamental as demonstrated by thinking of this pattern as `sol-la-ti-do` in the key of the dominant.

### FROM END OF KEY SIGNATURE TOPIC

**INCORPORATE INTO MATERIAL ABOVE now that we've moved this out of its own unit**

<!-- FIX THIS BELOW -->

The division of the octave into twelve parts is our brains' interpretations of a simple mathematical phenomenon. When the frequency of a soundwave doubles, our brains hear those two frequencies as sharing some fundamental commonality, so it interprets those two pitches as the "same" but separated by an octave. Therefore, octaves always have a 2:1 ratio. (A110, A220, A440, and A880 are all `A` separated by octaves.) The next two simplest ratios are a 3:2 ratio and a 4:3 ratio, which create a perfect 5th and a perfect 4th respectively. 

Not only does your brain's interpretation of these ratios create the ideas of consonance and dissonance, it is also the reason we divide the octave into twelve instead of a "simpler" number such as ten. You can observe this effect most easily in the circle of fifths. If you begin on any pitch-class and begin moving by ascending perfect 5ths (or 4ths), you will find yourself back at the beginning after cycling through all twelve pitch-classes. We call this the circle of fifths.

C - G - D - A - E - B - F-sharp - C-sharp - G-sharp - D-sharp/E-flat - B-flat - F - *C*

Perhaps more important for our discussion, though, is what happens when we introduce a non-perfect 5th into the pattern. If we begin on a pitch-class and begin moving through ascending perfect 5ths, each new perfect 5th will move us to a *new letter*. After the first six letters, we begin adding accidentals and then repeating letters as seen in the circle of fifths above. If, however, we alter the last perfect 5th by a half-step to create a diminished 5th, we can break the pattern and shortcut to the end with one final perfect 5th. 

C (P5) G (P5) D (P5) A (P5) E (P5) B (d5) *F* (P5) C

This slight change creates the necessary tension for keys to function diatonically, so diatonic function could be described as a slight imperfection on an otherwise perfect series of intervals. 

This can be further shown by looking at the naturally occurring intervals when we write diatonic 5ths above the notes of a major scale.

{% capture ex7 %}X:7
%%staffsep 100%
T:Diatonic 5ths in the Major Scale
M:C
L:1/2
K:C
[CG] [DA]| [EB] [Fc]| [Gd] [Ae]| [Bf] [cg]||
w:P5 P5 P5 P5 P5 P5 d5 P5{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

When we begin exploring harmonic function in Unit 6, the tension provided by the one non-perfect 5th and its subsequent release will become obvious.

Key signatures reflect the importance of the one non-perfect interval. When studying the consecutive key signatures, you should focus on *which scale degree* is changed between consecutive keys. This will likely lead to two basic principles:
- When a sharp is added to a key, it always raises the 7th scale degree in the new key, thereby creating the new `ti`.
    - You can find the new `do` by going up a half-step from the new `ti`.
- When a flat is added to a key, it always lowers the 4th scale degree in the new key, thereby creating the new `fa`.
    - You can find the new `do` by going down a P4 (or up a P5) from the new `fa`.

### Order of sharps and flats

This directly reflects how diatonic function works; if we change *where* the one non-perfect 5th occurs, we change the key. From this we can determine a permanent order of flats or sharps, which cycles to the beginning if you need to continue raising or lowering pitches. 