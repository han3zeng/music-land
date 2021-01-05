## Understanding Digital Audio
* Record Flow
    * sound wave -> micro phone -> audio interface -> computer
        * sound wave
        * micro phone: transfer sound wave to analog electronic signal
        * audio interface
            * has ad/da converter
                * convert analog to digital
                * convert digital to analog
        * computer receive the digital signal

## The "resolution" of Sound
    * Bit Depth
    * Sample Rate


## Recording Equipment
* Studio Microphone
    * advantage
        * flexible? add microphone, change it with same XLR Cable
    * steps
        1. Microphone
            * capture sound and transfer it to electronic signal
        2. XLR Cable
            * transfer signal to AI
        3. Audio Interface
            * A to D
        4. USB Cable
            * pass signal to computer
        5. Computer
        6. DAW

* USB Microphone
    * advantage
        * convenient, low price
    * disadvantage
        * not flexible
    * steps
        1. Microphone
            * Capture sound wave -> electronic signal -> digital signal
        2. USB Cable
        3. Computer
        4. DAW


* Speaker
    1. DAW
    2. Computer
    3. Audio Interface
    4. Balanced Audio Cables(XLR, TRRS)
    5. Speakers

* Headphone
    1. DAW
    2. Computer
    3. Audio Interface || USB Microphone
    4. Headphone

* TRS, TRRS, TRRRS
    * TRS
        * distortion
        * mono
    * TRRS
        * without distortion
        * stereo
    * TRRRS
        * without distortion
        * stereo (output)
        * plus record (input)

## Song
* an idea, a melody...
* melody, chord, bass, rhythm
* combination of multiple mono/stereo sounds
* mixing
    * eq
    * compressor
* get single track


## Frequency Spectrum
* application: EQ
* bass, mid, treble
* audible frequency to human
    * 20 - 20,000
    * treble: 5k - 20k
    * mid: 100 - 500, 500 - 1k, 1k - 5k
    * bass: 20 - 100
* instruments
    * bass: 50 - 100
    * male vocal: 100 - 200
    * female vocal: 300
    * guitar: 150 - 200

* environment

* room acoustics
    * the sound waves bounce around in the room until it run out the energy then you can not hear the sound

## Decibels
* are not absolute value
    * are reference point
* subtypes
    * dBSPL, (sound pressure level)
        * 120 dBSPL is uncomfortable
    * dBVU (decibels volume unit)
        * analog equipment
        * a sweet spot from 0 - 3 dBVU
        * 0 dBVU === 1.228 volt
    * [dBFS](https://www.youtube.com/watch?v=Djz8kaKqxyQ) (decibels relative to full scale)
        * a unit of measurement for amplitude levels in digital systems
        * digital equipment
        * 0 dBFS
            * 0 is ceiling of dBFS
                * above it -> clipping
        * -18 dBFS === 0 dBVU
            * recording, mixing in this setting

## Mixing
* choice
    1. volume
    2. EQ
    3. pan
        * final stage to tune
        * only works on stereo

* EQ
    * adjust the volume of individual frequency

* compressor
    * control the dynamics
        * lower the dynamic range
    * problem:
        * vocal sometimes too loud or too quiet in single track
            * solution
                1. user compressor to limit the loudest part
                2. bring the all volume up
    * more
        * attacks
        * tone...

## refs
* [balanced v.s unbalanced](https://www.epiphan.com/blog/audio-cables-balanced-vs-unbalanced/#:~:text=Balanced%20cables%20have%20three%20wires,wires%20from%20external%20electronic%20interference.)
* [TS, TRS, TRRS](https://monopricesupport.kayako.com/article/102-what-is-the-difference-between-ts-trs-and-trrs)
