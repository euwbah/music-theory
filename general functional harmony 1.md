# Overanalyzing the perfect cadence

Deconstructing the fundamental 'axioms' of functional harmony from the perfect cadence so that we can use them to reconstruct novel cadences in any tuning system.

## Part I. Deconstruction

> In this section, we derive the 'axioms' of functional harmony by looking at a G dominant 7 to C major resolving cadence (in the tonal center of C) from various POVs. Everything in this section is just about a G7 chord moving resolving to a C major triad.

### 1. Renaissance cadence theory

> related to 'voice leading'

European classical's original conception of 'resolution'
comprised of individual voices moving by specific intervals, rather than chords.

Each cadential movement (a single monophonic voice moving from one note to another) is given a name. [See Early Music Sources's video/article](https://www.earlymusicsources.com/youtube/cadences)

Based on the one-step authentic cadence, which in present theory is known to be the basic V-I perfect cadence, we have these movements:

* D &rarr; C: Tenorizans durum
* B &rarr; C: Cantizans
* G &rarr; C: Bassizans
* (G &rarr; E: Altizans)
  * This is considered as an extraneous part in renaissance theory, and as later explained in section 2., actually does not constitute a 'movement'.

The dominant 7th resolves according to the one-step plagal cadence.:

* F &rarr; E: Tenorizans molle

> Disclaimer: Here we're forcing the dominant 7th to fit into the renaissance conceptualization, as such a cadential movement (descending diatonic semitone) would only be used in the context of a IVm-I plagal cadence (Dm resolving to A maj), so it could be seen as a period-incorrect retrofit, or borrowing the relative minor key. However, Monteverdi is known to have used this exact movement in the same context as we are seeing it in. By the Baroque period, the dominant 7th as an unprepared dissonance has been normalized.

### 2. Pitch memory

> See [Prof. Diana Deutsch's 'pitch memory'](https://deutsch.ucsd.edu/psychology/pages.php?i=209)

Before going further, we need to take a detour and understand 'pitch memory', and realise how fundamental the renaissance conception of harmony is to contemporary eurocentric music.

In short, Deutsch's work shows empirical proof of the ability of both musically trained and untrained to commit the frequencies of pitches in external stimuli to a short term memory, and how specific conditions cause an increased probability of certain pitches in the short term memory to be forgetten/reinforced.

We can extrapolate from 'pitch memory' that the precense of new pitches that are intervalically 'close' to prior pitches stored in the short term memory causes an increase in probability that the listener forgets the old pitch, and conflates the new pitch as the old one.

Specifically, 'close' can be defined as the intervals that cause increased error/forgetting in the pitch memory as shown in the following figure (Deutsch, [_Short Term Memory For Tones_](https://deutsch.ucsd.edu/psychology/pages.php?i=209)):

![](img/IntervalDistError.jpg)

Relating this back to section 1, we can see how the renaissance concept of how the 'altizans' is a non-crucial voice in the authentic cadence has empirical backing as minor thirds do not 'move' pitches in the short term memory as much as other intervals.

Now, symmetries can be drawn between the 'voice movement' concept of renaissance functional harmony and how nearby intervals can cause 'movement' in the short term memory.

From this, we can say:

* Octave-equivalence does not apply when considering horizontal resolutions of harmony. (i.e. in the context of a homophonic chordal accompaniment, chord voicings are important and octave choice is not arbitrary)

* We hear harmonic 'colour changes' in accordance to how the short term memory is affected by present stimuli.

### 3. Just intonation analysis

> Recommended prerequisite knowledge on just intonation representations of intervals.
>
> * [learn the overtone series](https://www.youtube.com/watch?v=hDLhe-NkH2A&ab_channel=mannfishh)
> * [develop an intuition for the just intonation lattice](https://www.youtube.com/watch?v=ZJfAVSVgaSI&ab_channel=mannfishh)
> * [learn to prime factorize](https://www.cuemath.com/prime-factorization-formula/)
> * [learn the math of adding and subtracting intervals](https://www.kylegann.com/tuning.html)
>   * in short, let R be the fraction that represents a particular interval, and let F be any pitch in Hz. To raise F by an interval, multiply F by R. To lower F by an interval, divide F by R.
> * Understand that 'p-limit' just intonation means that the intervals used do not contain prime factors of any primes that are greater than 'p'.
> * (Optional) [know the names & cent distances of just intervals](https://en.xen.wiki/w/Gallery_of_just_intervals)

First, let us analyze the notes of the chords G dominant 7 and C major vertically with respect to the fundamental pitch of C. Note that there are many possible choices when it comes to finding a just intonation representation of notes in 12edo (we are 'detempering' a tempered tuning system into an untempered just tuning), below we go with the just intervals that are 'closest' to the fundamental C (in terms of spatial distance in the 5-limit lattice) and constrained within the 5-limit (since present-day eurocentric music almost never assumes functional use of any higher limit intervals). Since we are vertically analyzing, we assume octave equivalence (powers of 2 in prime factorization are arbitrary)

C major:

* C: 1/1
* E: 5/4
* G: 3/2

G dominant 7:

* G: 3/2
* B: 15/8
* D: 9/4
* F: 8/3

We can also put all these frequency ratios as a compound ratio such that the notes' frequencies can be expressed as a rational multiple of any other note:

* C major: 4:5:6
* G dominant7: 36:45:54:64

Based on the vertical ratios, we can intuitively see that G dominant 7 has greater complexity as compared to C major, thus that gives us a directed resolution that makes it obvious which one of the two is the 'tension' and which one is the 'release'. These ratios can be thought of as structures present in the sound pressure waves in the air.

Note that if both chords were major triads in root position, vertical analysis would yield no difference in complexity as both chords would simply be 4:5:6. There would also be musical ambiguity in a chord progression that only alternates between C and G major triads, and tonal center cannot be fully ascertained without additional notes in the melody, phrasing, or harmonic rhythm.

> Disclaimer: This vertical analysis is slightly flawed because we assumed the just intonation interpretations of originally non-just intervals. The ideal goal would be to deconstruct the 12edo equal-tempered variant of the perfect cadence, as-is. However, that involves tetradic [harmonic entropy](https://en.xen.wiki/w/Harmonic_entropy), which to summarize, is a means of modelling cognitive discordance by taking a probabilitstic view of the auditory cortex interpreting pitch stimuli as particular interval ratios instead of any other similar interval ratios and applying concepts from information entropy to measure how much harmonic information is given by input stimuli.
> 
> Harmonic entropy can be thought of as a 'general formula' for calculating discordance of a single static chord voicing. It is beyond the scope of this writing, but it good to know that the harmonic entropy of G dominant 7 in any arbitrary voicing is certainly higher than that of C major, so the idea that G7 is objectively more 'complex' than a C triad is still valid.
>
> There are also known metrics of objectively scoring discordance between just intonated interval ratios, which are known as [height functions](https://en.xen.wiki/w/Height). When an interval is said to be relatively 'complicated' or 'discordant', the height function would yield a larger score. In number theory, height functions quantify the [complexity of objects](https://en.wikipedia.org/wiki/Height_function).
>
> Note that there is still merit to continuing the analysis in just intonation as these specifically chosen just interval representations have the highest probabilities of being perceived and detempered by the auditory cortex as the input stimuli 12edo tempered intervals.

Let us analyze the voice movements in section 1 in just intonation:

* B &rarr; C: Cantizans is ascending by a major diatonic semitone (16/15) to go from 15/16 to 1/1.
  * This is a strong movement according to 'pitch memory'. The semitone is the strongest possible intervallic movement in 12 edo.
  * B (15/16) is moves from a relatively more complicated interval with respect to the tonal center (C), to C (1/1) which is the simplest possible interval with respect to the tonal center.
* D &rarr; C: Tenorizans durum is descending by a pythagorean major second (9/8) to go from 9/8 to 1/1. According to pitch memory, this is not the strongest movement available in our present-day 12 edo tuning system.