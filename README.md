<h1>Drop Down Sublime</h1>
A drop down window for Sublime Text.

<p>This is a modification of Jonathon Rogers's (lonepie)
<a href="https://github.com/lonepie/mintty-quake-console">mintty-quake-console</a>,
which is a drop down mintty console. He deserves all of the credit here. I
just changed things here and there to make it work with Sublime Text. :)
</p>

<p>By default, the hotkey to toggle the window is <kbd>RWin</kbd>+<kbd>Backspace</kbd>.
You can change it, as well as some other settings, in the file
<strong><a href="https://github.com/JordanTHarris/DropDownSublime/blob/master/DropDownSublime.ini">DropDownSublime.ini</strong></a>. Look at <a href="https://github.com/lonepie/mintty-quake-console">mintty-quake-console</a>
for more details on that.
</p>

<h2>New features</h2>
<ul>
    <li>The drop down window can now be "anchored" to either the left or the right side, instead of
    just the center like before. This can be applied in the DropDownSublime.ini file by setting
    <em>initial_side</em> to the side you want (left or right). For example:
    <strong>initial_side=left</strong>. Any other value will anchor it to center, like before.</li>
    <li>The window can now be moved to the left side with <kbd>Win</kbd>+<kbd>Shift</kbd>+<kbd>Left</kbd>
    or to the right side with <kbd>Win</kbd>+<kbd>Shift</kbd>+<kbd>Right</kbd></li>
</ul>

<h2>Known Issues</h2>
<ul>
  <li>When Sublime Text isn't already opened, the sizing and positioning of it's window isn't how it's
  expected to be. It loads with the size of the window that you last closed. This could be useful if you
  want to just use the left side of the screen or something, but it's not the expected behavior. If you
  want the normal behavior (like with mintty-quake-console), you'll have to first open Sublime Text, then
  open Drop Down Sublime. Either that, or reload Drop Down Sublime by right clicking the icon in the
  notification area and selecting <em>Reload.</em></li>
</ul>
