# Quire & Thread: the bindery example

The worked example from chapter 6 of *The Cinematic Web*: one self-contained HTML file, no build step. Quire & Thread is a fictional bindery.

- **Signature moment:** a code-drawn plate of a spine under repair pushes in on scroll while the headline lifts away; chapter I is laid over it like a sheet of paper and holds still.
- **Desktop with a fine pointer:** pinned for 300vh. Transform and opacity only, one `requestAnimationFrame` scroll clock, layout read only on resize.
- **Touch or narrow screens:** no pin. The layout stacks, the plate drifts on a lerped parallax and sections reveal as they enter.
- **Reduced motion, no JavaScript, or a failed script:** static composition with every word visible. Text is never hidden by default.
- **Checks:** cinematic-doctor 100/100. page-proof is clean at 1440×900, at 390×844 mobile, with reduced motion and with JavaScript off.

Open `index.html` in a browser, or view it live at https://mustbesimo.github.io/the-cinematic-web/examples/bindery/. Fonts load from Google Fonts. Code is MIT.
