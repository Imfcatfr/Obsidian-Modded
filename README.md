# Obsidian UI Library
**Documentation:** https://docs.mspaint.cc/obsidian

**Source code to documentation site:** https://github.com/mspaint-cc/docs.mspaint.cc/tree/main/content/obsidian

---

### What's new?
Yo, just pushed some updates to make the UI feel sick to use. I tossed out the stiff old animations and added some bouncy physics, slick hover effects, and a bunch of cool details. Breaking it down (Break down made by me and grammar correct by ChatGPT):

- **Morphing Tabs:** When you click a new tab, the active indicator physically snaps and stretches over to it instead of just teleporting.
- **Squeeze & Glows:** Stuff actually reacts when you hover over it now. Buttons and toggles do this cool little soft squeeze, and there's a smooth radial glow that tracks your mouse underneath. It's crazy satisfying.
- **Focus Bloom:** Active toggles and tabs now pop with bold text and a subtle neon bloom shadow. Makes it super obvious what you enabled without burning your retinas.
- **Micro-Animations:** Everything runs on crispy `Quint` easing now, plus I added material ripple effects so clicking things actually has some weight to it.
- **Gradients & Ghost Mode:** I added full gradient support for sick multi-color sequences. Also rewrote the memory stuff so it doesn't lag out your game, and tossed in a "Ghost Mode" panic button (hit `Right-Alt` and the whole UI vanishes perfectly).

Have fun messing around with it!
