## orchestra

Orchestra is a keyboard-based instrument that I built to help me teach basic electronics using [MaKey MaKey](http://makeymakey.com). I love using sound and music to teach, but as I've learned the hard way over the years, in a group setting it can be difficult for participants with varying musical experience to collaborate and generate compositions. Orchestra helps alleviate some of that tension by allowing for multiple synced "instruments" that all produce complementary sound.

### Getting Started
Orchestra is a *really rough* tool at this point and thus you'll need to run it yourself within [Quartz Composer](http://en.wikipedia.org/wiki/Quartz_Composer). Once you have downloaded Orchestra and installed XCode / QC, simply open `orchestra.qtz` and follow the in-composition notes to configure.

If this is something that you feel you would be interested in but the interface is too rough / complex, please let me know!

### Creating Loops
In the `loops` directory are two sets (one orchestral and one "techno-y") with six discrete sound files each. These are included as an example of how to create a collection of sounds that work together seamlessly.

For example, all of the included `WAV` files have the following characteristics:
- 128 beats per minute
- 16 bars
- Key of D

16 bars of 128 bpm sound works out to exactly 7.50 seconds, as seen below:
![](https://raw.github.com/thisandagain/orchestra/master/screenshots/peak.png)

### Screenshots
![](https://raw.github.com/thisandagain/orchestra/master/screenshots/patch.png)
![](https://raw.github.com/thisandagain/orchestra/master/screenshots/viewer.png)