# Cheerlights Lightsaber

## Installation
I used a Arduino Mega 2560 r3 (others may work thou - with minor changes to the code (software serial))
A strip of 30 neopixels (ws2812) leds (you can find these reasonable on eBay)
connected to pin 3.
A ethernet shield 
A TTL (serial) MP3 (found on eBay: This is the one I used http://www.ebay.com/itm/201436015473?_trksid=p2060353.m1438.l2649&ssPageName=STRK%3AMEBIDX%3AIT)
and a Speaker.
I found the "lightsaber" at a Family Dollar store for $5.00.
it has 6 screws in it, so it was easy to pull apart. I removed the "electronics" that were in it (I use that loosely, it was a couple of leds, a speaker, a button, and a chip).
extend the "saber" full, I cut off the top tip of it just to make it a little easier to feed the neopixel strip in. The strip is a little longer than needed, but fits pretty easy in the handle. I also cut a hole in the base to get power and connections from Arduino. (Orignally I wanted to put the arduino and MP3 player inside of it.) Doing it this way thou was easier.
Loaded code on the Mega, hooked up MP3 to serial 1, found "saberon.mp3" "saberoff.mp3" and "saberhum.mp3" by doing a google search.
Depending on how the files go on your SD card you may need to change the order they play in the sketch (beyond the scope of this.)
That is pretty much it.

## Things To Do

Build a box for my MP3/Arduino/speaker to hide the wires.

## Usage

TODO: Write usage instructions

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

LeRoy Miller (2015) and Catalex (unknown data)
most of the software is for the mp3 and based off the Catalex sketches.

## License

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses>

### 1.8.9 June 2019
