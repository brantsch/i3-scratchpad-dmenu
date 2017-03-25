# i3wm's Scratchpad
There's an invisible workspace you can't switch to, but move windows to and
from.  That's the so-called
[scratchpad](http://i3wm.org/docs/userguide.html#_scratchpad).

Unfortunately, i3 itself does not provida a convenient way to choose which
window to restore from the scratchpad. Thus, this script was written.

# Usage
Just run this script. It will create a list of titles of windows currently in
i3's scratchpad and run a dmenu with that list, to allow you to select a window
to bring back from the scratchpad.
