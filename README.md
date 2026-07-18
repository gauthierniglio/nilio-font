# Nilio

Nilio is a variable font designed for interfaces. Built with legibility and rhythm in mind, it adapts to a wide range of weights through a single variable axis — making it practical for display use.

**Axis:** Weight (`wght`) — 100 to 900  
**Formats:** `.woff2` (web), `.woff` (web fallback), `.ttf` (desktop)

---

## Web usage

```css
@font-face {
  font-family: 'Nilio';
  src: url('https://cdn.jsdelivr.net/gh/gauthierniglio/Nilio-font@v1.0/web/NilioVF.woff2') format('woff2'),
       url('https://cdn.jsdelivr.net/gh/gauthierniglio/Nilio-font@v1.0/web/NilioVF.woff') format('woff');
  font-weight: 100 900;
  font-style: normal;
  font-display: swap;
}
```

Then use the weight axis freely:

```css
h1 { font-family: 'Nilio', sans-serif; font-weight: 700; }
p  { font-family: 'Nilio', sans-serif; font-weight: 400; }

/* Or with font-variation-settings for fine-grained control */
.display { font-variation-settings: 'wght' 850; }
```

---

## Desktop installation

1. Download `NilioVF.ttf` from the root of this repository
   — or pick a specific weight from the `/static` folder (Regular, Medium… Black)2. **macOS** — double-click the file → Install Font
3. **Windows** — right-click → Install
4. **Linux** — copy to `~/.local/share/fonts/` then run `fc-cache -f`

Static versions (individual weight files) are available in the `/static` folder for apps that don't support variable fonts.

---

## License

Nilio is free to use under the **Creative Commons Attribution-NoDerivatives 4.0 International** license (CC BY-ND 4.0).

**You are free to:**
- Use Nilio in any project, including commercial work
- Share and redistribute the font files as-is

**Under the following terms:**
- **Attribution** — Credit must be given to Gauthier Niglio with a link to this repository
- **No derivatives** — You may not distribute modified versions of the font

→ Full license text: [creativecommons.org/licenses/by-nd/4.0](https://creativecommons.org/licenses/by-nd/4.0/)

---

## Contact & feedback

Questions or feedback? Reach out at [contact@gauthierniglio.fr](mailto:contact@gauthierniglio.fr)

© 2023 Gauthier Niglio
