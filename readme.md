# Resources

## NESdev wiki: 
- [Main page](https://www.nesdev.org/wiki/Nesdev_Wiki)
- [APU overview](https://www.nesdev.org/wiki/APU)
### Super deep dives, god bless the early aughts internet...
- [NES APU Sound Hardware Reference by Blargg, 2003](https://www.nesdev.org/apu_ref.txt)
- [2A03 Technical Reference by Brad Taylor, 2004](https://www.nesdev.org/2A03%20technical%20reference.txt)

## Rodrigo Coppetti's NES architecture series:
- [Has many helpful visualizations](https://www.copetti.org/writings/consoles/nes/)

## NESHacker youtube channel
- [Setting up an NES development environment from NesHacker on yt](https://www.youtube.com/watch?v=RtY5FV5TrIU)

## OneLoneCoder NES emulator series
- [NES Emulator Part #1: Bitwise Basics & Overview](https://www.youtube.com/watch?v=F8kx56OZQhg&list=PLrOv9FMX8xJHqMvSGB_9G9nZZ_4IgteYf&index=2)
    - Maybe you can make sense of the "data structures" section? (cpp "bitfield")
- [NES Emulator Part #2: The CPU (6502 Implementation)](https://youtu.be/8XmxKPJDGU0?si=Hk7__LOkrzxNJV76&t=3419)
    - The "Testing" section that begins at the timestamp is basically the UI I was imagining

## Background
### [Koji Kondo - 2001 Composer Interview](https://shmuplations.com/kojikondo/)
- How did you compose songs in those early Famicom days?
- Kondo: *Back then, there was no MIDI or other protocol that could directly convert your keyboard playing to data. Everything was composed directly on the computer, entering notes manually.* I did practice on my Electone at home and sketch out ideas, which I’d then take to the office and enter into the computer. I would do the arrangement on the computer there, adjusting things as I went.

- Did the new sound staff also have to do any programming?
- Kondo: We did. We all started studying programming once we were hired.

- The music of Super Mario Bros. has a latin feel to it. I think this genre of music is particularly suited for the Famicom, don’t you?
- Kondo: *The Famicom uses square waves, which have a richer harmonic content than normal instruments. This means that when you’re writing chords, its better to use wider intervals rather than shorter ones. For example, take a 1-3-5 (do-mi-so) C-major chord… with the Famicom, open voicing (ie. wider intervals between the notes in a chord) sounds much clearer.* That was a principle I discovered before I made Super Mario Bros, which is why I think Mario’s songs use chords with an open, wide feel to them. The Famicom only has three channels for sound, but using this technique, I was able to make it sound more like 5.

- Now that you were on the Super Famicom, did you still have to struggle with limited space and memory?
- Kondo: Yeah, always. To me it was just the way things were. *I used to do some sound programming, too, and I came up with various programming tricks to get around the memory limitations, which I did in fact use in the music. On games like Shin Onigashima, for instance, the amount of memory we had available was tiny, but because I was both the programmer and the composer, I knew how to compose the songs in such a way that they’d be easy to compress.* It’s a bit different from the normal music recording process, where the musician and the engineer are two different people.



### [Interview: Final Fantasy’s Nobuo Uematsu](https://daily.redbullmusicacademy.com/2014/10/nobuo-uematsu-interview)
- Was it tough to make music for the NES?
- The NES days were tough. *I had to type in every little thing by myself, like for an 8th note in C, C8, for a 16th note in E, E16 and so on. I used a goto statement to repeat and such, and had to do that endlessly, so it was really tough.*

- What kind of tools and gadgets did you use during the NES days?
- I think the machine I used during the NES days was an MSX. I’d say I was using it up until Final Fantasy III.

- Did you discover any tricks for overcoming the limitations of the hardware?
- When making music for the NES, they were all electronic sounds. It only made sounds like “peee,” “booo,” “paaa,” so expressing emotions was definitely tough. So, instead of just having “paaa,” I’d do a “pwaoo” sound by changing the way it faded in and out. *For example, for playing a melody, I’d play one sound at a proper frequency, and another sound with the same melody. But I’d shift the frequency a little for that one, and the timing of it*. By doing that, even though they were electronic sounds, it created kind of shimmer, and a sound that was full of emotion. I tested various things like that day after day.

- How long did it take you to get accustomed to the new working environment when the SNES was introduced?
- When we switched to *the SNES, I don’t think there was any time to study before starting work for real. So, they put a sound programmer with me, and together with him, we made music every day while sampling tones and testing them out.* But even then there wasn’t enough time. I wouldn’t have been able to make it even working at the pace of a regular person. So, we went to work at 6 AM, and tried out what we could before people arrived.

# WARNING
- [Looks like NES roms need to have header files to be played by emulators?](https://github.com/OpenEmu/OpenEmu/issues/4049)
