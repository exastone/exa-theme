# Exa Theme Pack

*What Exa theme pack offers*

A set of great looking themes created for eye comfort and consistency.

**Eye Comfort**
- The themes provided were created with [WCAG - Web Content Accessibility Guidelines](https://www.w3.org/TR/WCAG21/) in mind to provide a minumum level of *AA* contrast (>6.0 contrast ratio) for syntax highlighting and UI text components.
- 4 themes created with the purpose of accomidating lighting conditions throughout the day 
  - Glacial (light)
    - Partical semantic highlighting support (WIP)
    - Created with intended use in bright lighting conditions such as early and mid-day
  - Azure Dawn (med blue theme)
    - Semantic highlighting support
    - Created with intended use in medium lighting conditions such as late afternoon and early evening
  - Tundra Dusk (dark blue theme)
    - Semantic highlighting support
    - Created with intended use in less intense lighting conditions such as evening and night
  - Woodland Eventide (foresty-green theme)
    - Limited semantic highlighting support (SH will be added at somepoint)
    - Created as a happy accident that ended up being a middle-ground between Azure and Tundra 
 
**Consistency**

What does consistency mean for syntax highlighting and UI?

Because the theme pack was created with the purpose of switching the active theme based on lighting conditions, I wanted to maintain visual reference models of code regardless of the theme.

This was done (still a WIP) by creating a quazi-standard* set of color rules e.g. function names are always blue, control flow (e.g. `if`, `else`) is green, keywords (e.g. `fn`, `def`) are yellow, etc.


*Color rules are not hard set because of the difficulty to achieve minimum *AA* contrast levels on some screens for certain foreground/background colour combinations. In general the color ruling aims to provide familar visual context marker for the themes in the pack, regardless of language.  

## Preview

![Combined Theme Preview](https://github.com/exastone/joegrammer-theme/blob/main/screenshots/combined.jpg?raw=true)

![Glacial](https://github.com/exastone/exa-theme/blob/main/screenshots/theme-glacial.jpg?raw=true)

![Tundra Dusk](https://github.com/exastone/exa-theme/blob/main/screenshots/theme-dusk.jpg?raw=true)

![Azure Dawn](https://github.com/exastone/exa-theme/blob/main/screenshots/theme-dawn.jpg?raw=true)

![Woodland Eventide](https://github.com/exastone/exa-theme/blob/main/screenshots/theme-woodland.jpg?raw=true)

**previews may not be updated between patch versions

---

### Something doesn't look right?

**Let me know!**

Some of the vscode UI colour specifiers are Windows only (which I don't typically run) so any attention brought to oddly coloured UI is appreciated.

Make sure you have semantic highlighting enabled in your settings.

Three of the four themes rely largely on LSP to provide semantic highlighting but there should be resonable defaults for traditional textmate scope coloring. If you know notice poor contrast (all themes aim to provide a minimum contrast ratio of <6.5), raise an issue and I'll have a look at correcting.
