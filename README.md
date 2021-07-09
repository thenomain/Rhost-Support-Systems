# Rhost-Support-Systems
General support systems tuned specifically for RhostMUSH

Does what it says on the tin.

Should work with the following formatters:
* UrsaMu Formatter: https://format.ursamu.io
* Muxify: https://muxify.musoapbox.net/editor.html

Always be careful when using formatters.

---

## Cross-Platform Mushlike Conversion Blues

I am trying hard to make all of of this code work on the three major current Mushlike branches: TinyMUX, RhostMUSH, and PennMUSH. There will be code to tweak the installation to the platform of your choice.

Most of this code was originally written for TinyMUX, so you may read in some prejudices if you're familiar enough with mushcode to do so. There is no bias intended.

### PennMUSH

I use the `no_parse` attribute flag quite frequently through this code in lieu of certain security checks. I don't know Penn well enough to overcome this, so please be aware if this is your codebase of choice.