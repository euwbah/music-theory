# Overanalyzing the perfect cadence

Deconstructing the fundamental 'axioms' of functional harmony from the perfect cadence so that we can use them to reconstruct novel cadences in any tuning system.

## Part I. Deconstruction

> In this section, we derive the 'axioms' of functional harmony by looking at a G dominant 7 to C major resolving cadence (in the tonal center of C) from various POVs. Everything in this section is just about a G7 chord moving resolving to a C major triad.

### 1. Renaissance cadence theory

> related to 'voice leading'

European classical's original conception of 'resolution'
comprised of individual voices moving by specific intervals, rather than chords. These were known as 'clausula' but we shall refer to them as 'movements' in this writing.

Each cadential movement (a single monophonic voice moving from one note to another) is given a name. [See Early Music Sources's video/article](https://www.earlymusicsources.com/youtube/cadences)

Based on the one-step authentic cadence, which in present theory is known to be the basic V-I perfect cadence, we have these movements:

* D &rarr; C: Tenorizans durum clausula
* B &rarr; C: Cantizans clausula
* G &rarr; C: Bassizans clausula
* (G &rarr; E: Altizans clausula)
  * This is considered as an extraneous part in renaissance theory, and as later explained in section 2., actually does not constitute a 'movement'.

The dominant 7th resolves according to the one-step plagal cadence.:

* F &rarr; E: Tenorizans molle clausula (plagal cadence)

It could also be seen as the altizans of the tenor cadence, though the 'altizans' was normally attributed to being 'filler':

* F &rarr; E: Altizans clausula (tenor cadence)

> Disclaimer: Here we're forcing the dominant 7th to fit into the renaissance conceptualization, as such a cadential movement (descending diatonic semitone) would only be used in the context of a IVm-I plagal cadence (Dm resolving to A maj), so it could be seen as a period-incorrect retrofit, or borrowing the relative minor key. However, Monteverdi is known to have used this exact movement in the same context as we are seeing it in. By the Baroque period, the dominant 7th as an unprepared dissonance has been normalized.

> To put these into perspective: these were the origins of eurocentric functional harmony and were, in a sense, discovered a priori by means of experimentation and the spreading and rebutals of treatises. During this period, there were no notions of chords, nor any present day assumptions of the notion of scales, keys, tonality, nor a consensus on tuning system.

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

First, let us analyze the notes of the chords G dominant 7 and C major vertically with respect to the fundamental pitch of C. Vertical analysis is ultimately an analysis of [harmonic entropy](https://en.xen.wiki/w/Harmonic_entropy) and 'color' (i.e. intervals that are not solely composite of powers of 2). Note that there are many possible choices when it comes to finding a just intonation representation of notes in 12edo (we are 'detempering' a tempered tuning system into an untempered just tuning). We shall use just intervals that are 'closest' to the fundamental C (i.e. gives the lowest _height_ score, explained later) and constrained within the 5-limit (since present-day eurocentric music almost never assumes functional use of any higher limit intervals). Since we are vertically analyzing for color, we assume octave equivalence (powers of 2 in prime factorization are arbitrary)

> Side note: detempering involves undoing the [mathematical coincidences](https://en.wikipedia.org/wiki/Mathematical_coincidence#Concerning_musical_intervals) we exploit between irrationals and rationals.
>
> For more information, see [tempering](https://en.xen.wiki/w/Tempering_out) and [detempering](https://en.xen.wiki/w/Detempering) on the xenwiki.

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

We can already make the observation that the simplest vertical structures would arise from choosing intervals that are part of the same overtone series; if notes were chosen from varying overtone series, the compound ratio would have to accomodate for common factors that are missing between selected fundamentals of the varying overtone series.

Note that if both chords were major triads in root position, vertical analysis would yield no difference in complexity as both chords would simply be 4:5:6. There would also be musical ambiguity in a chord progression that only alternates between C and G major triads, and tonal center cannot be fully ascertained without additional notes in the melody, phrasing, or harmonic rhythm.

> Disclaimer: This vertical analysis is slightly flawed because we assumed the just intonation interpretations of originally non-just intervals. The ideal goal would be to deconstruct the 12edo equal-tempered variant of the perfect cadence, as-is. However, that involves tetradic [harmonic entropy](https://en.xen.wiki/w/Harmonic_entropy), which to summarize, is a means of modelling cognitive discordance by taking a probabilitstic view of the auditory cortex interpreting pitch stimuli as particular interval ratios instead of any other similar interval ratios and applying concepts from information entropy to measure how much harmonic information is given by input stimuli.
> 
> Harmonic entropy can be thought of as a 'general formula' for calculating discordance of a single static chord voicing. It is beyond the scope of this writing, but it good to know that the harmonic entropy of G dominant 7 in any arbitrary voicing is certainly higher than that of C major, so the idea that G7 is objectively more 'complex' than a C triad is still valid.
>
> There are also known metrics of objectively scoring discordance between just intonated interval ratios, which are known as [height functions](https://en.xen.wiki/w/Height). When a just interval is said to be relatively 'complicated' or 'discordant', the height function would yield a relatively larger score. In number theory, height functions quantify the [complexity of objects](https://en.wikipedia.org/wiki/Height_function).
>
> Note that there is still merit to continuing the analysis in just intonation as these specifically chosen just interval representations have the highest probabilities of being perceived and detempered by the auditory cortex as the input stimuli 12edo tempered intervals. However, a full analysis would require one to perform these observations on all other possible just interval representations (e.g. 21/16 instead of 4/3 for the note F in G dominant 7), though it would yield identical conclusions.

Now let us analyze the horizontal voice movements in section 1 in just intonation. Recall that octave-equivalence does not exist here.

* B &rarr; C: Cantizans (authentic) ascends by a classic diatonic semitone (16/15) to go from 15/16 to 1/1.
  * This is a strong voice movement according to 'pitch memory'. The semitone is the strongest possible intervallic movement in 12 edo.
  * B (15/16) moves from a relatively more complicated interval (greater [_height_](https://en.wikipedia.org/wiki/Height_function)) with respect to the tonal center (C), to C (1/1) which is the simplest possible interval with respect to the tonal center.
  * 15/16 is the (octave-reduced) 15th harmonic of the overtone series of the fundamental.
  * Note: the original clausula around the 13th century involves perceiving the semitone as the difference between the perfect fourth (4/3) and the pythagorean ditone/maj 3rd (81/64), yielding the pythagorean limma (256/243), however in the modern context this movement is more often tuned from the classic major third of the fifth (5/4 * 3/2 = 15/8).

* D &rarr; C: Tenorizans durum (authentic) descends by a pythagorean major second (9/8) to go from 9/8 to 1/1.
  * This is a weaker movement in 12 edo compared to the semitone
  * D (9/8) moves from a relatively more complicated interval to unison (1/1) w.r.t. the tonal center (C)
  * 9/8 is the (octave-reduced) 9th harmonic of the overtone series of the fundamental.

> Note that there are two ways of viewing the tenorizans molle. We can see it the 'modern'/Monteverdi way which would be moving from the P4th to M3rd scale degree, or in the original context it was used in, which would be moving from the classic minor 3rd of the fourth (6/5 * 4/3 = 8/5) to the P5th.

* F &rarr; E: Tenorizans molle (plagal)/Altizans (tenor) ('modern' POV): descending by a classic diatonic semitone (16/15) to go from F (4/3) to E (5/4).
  * strong movement
  * F (4/3) is simpler than E (5/4), w.r.t. the tonal center (C)
  * 4/3 is not in the overtone series of the fundamental.
  * From this POV, the tenorizans molle is an outlier - the resolved note is technically more 'complex' than the 'tension' note. However, this discrepancy is congruent to the argument of why (and when) the Perfect 4th interval was considered to be a dissonance in the Common Practice Era. We can now rationalize it as the note F (4/3) is not contained in the overtone series or 'tonality' we are trying to resolve to. More about 'tonality' later.

* F &rarr; E: Tenorizans molle (renaissance plagal POV): descending by a classic diatonic semitone (16/15) to go from F (8/5) to E (3/2), with implied fundamental being A (1/1)
  * strong movement
  * F (8/5) is more complex than E (3/2) w.r.t. the tonal center (A)
  * 8/5 is not in the overtone series of the fundamental.
  * From this POV, it makes sense why this particular movement is formalised in renaissance theory in this context rather than the 'modern' context above. However, primodal tonality (explained later) allows us to 'borrow' these 'prime-modes', so they can be perceived from either viewpoint depending on context. (Not to be confused with the arbitrarily and vaguely defined 'modal interchange')

* G &rarr; C: Bassizans: descends by a pythagorean fifth (3/2) to go from G (3/2) to C (1/1).
  * This is not considered a movement as both G and C can live concurrently in pitch memory without additional error/forgetting above the baseline.
  * G (3/2) is more complex than C (1/1) w.r.t. C.
  * 3/2 is the (octave-reduced) 3rd harmonic of the fundamental.
  * Fulfils the function of sounding the relative fundamentals of each vertical chord. Note that by the psychoacoustic phenomenon of [combination tones](https://en.wikipedia.org/wiki/Combination_tone), [virtual fundamental](https://en.wikipedia.org/wiki/Virtual_pitch), [the dynamic nature of pitch perception](https://www.pnas.org/doi/10.1073/pnas.081070998), and [the emergent entrainment](https://www.biorxiv.org/content/10.1101/2021.10.20.465101v1) of [stochastic resonance](https://academic.oup.com/ptp/article/102/6/1057/1923010), these fundamental notes are already psychoacoustically present when harmonics (or sufficiently close approximates of harmonics) of them are sounded.
  * The perfect 5th is the simplest non-octave interval. As a nice number theory coincidence, the primes 2 and 3 are also fundamental in symmetrical structures of lie algebras, showing up in Chevalley bases' characteristic (which can be used to represent 5-limit just intonation in 3-dim vector multiplication systems)

### 4. Tonality

> Disclaimer: since we experience music spread across time and through conscious being, there is statefulness that cannot be modelled in tonality, the result of having to perceive through the lens of human perception, which boils down to intrinsic and extrinsic physiological/psychological factors. The intrinsic factors can all be modelled with the math stuff (height functions, entropy, circular maps, dynamic resonance, bayesian statistics etc) but the extrinsic factors involve cultural entrainment (long-term memory) and the fact that the listener has free will to direct attention to particular frequencies over others, which then ultimately contributes to the looser terms like being 'melodic' or having strong 'phrasing'.
>
> No matter the method of modelling, one has to take into account additional cultural factors that affect perception of tonality (e.g. ears from the eurocentric culture will not be able to discern intended dissonance in a raag when the characteristic gamakas of the raag is not adhered to; when note/tuning substitutions are made within a makam; when the rhythmic downbeat is incorrectly interpreted causing listeners to hear a different tonality/resolution than intended)

So far there is an evident pattern of resolving to note choices with lower complexity relative to the 'tonal center'. We can then looesly define tonality as whatever set of notes that allows the resolution to a simpler structure (less harmonic entropy/lower height score).

Ignoring extrinsic factors, we can define the fundamental tonality of everything to be the overtone series, since it is merely the set of positive integers, which can create all rational intervals, where all prior numbers are contained within the prime limit of the next prime. It is the majorest major. The perfect cadence is an example of the particular bias that western tonal harmony has towards the overtone series, which in fact originally stems from the tuning theory of the Greek Genus, which etymologically contributed to the Byzantinian liturgical chant, and evolved into European classical and maqam independently.

However, we can also choose to tonicise any subset of the harmonic series, starting any 'artificial fundamental'. This is similar to the idea of [the theory of primodality](https://www.youtube.com/watch?v=KKxXdD-lkwI&ab_channel=ZheannaErose).

For example, a resolution to a minor tonality in 12edo could be perceived as resolution to primemode-10 (10:12:15 5-limit minor triad) or even the 19-limit 16:19:24 which 12edo very accurately approximates.

Ultimately, tonality depends on what frequencies are being reinforced in the short term memory, and the reinforcement of frequencies are seen through the filter of intrinsic factors (objective concordance and ease of perception of intervals), but also through cultural reinforcement of patterns and 'cliches'.

### Final list of 'axioms' from deconstructing the perfect cadence.

* 'Voice leading' = 'movements' = 'pitch memory'
* height function, harmonic entropy = 'complexity'
* conforming to a single overtone series = the simplest tonal structure
* 