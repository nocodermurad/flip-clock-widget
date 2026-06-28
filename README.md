# Minimalist Monochrome Flip Clock Widget

A lightweight, responsive, monochrome flip clock widget built with vanilla HTML, CSS, and JavaScript. Designed for distraction-free site integration and seamless embedding.

## Live Demo & Embed Links

* **Live Demo:** [https://nocodermurad.github.io/flip-clock-widget/index.html](https://nocodermurad.github.io/flip-clock-widget/index.html)
* **Responsive Embed Demo:** [https://nocodermurad.github.io/flip-clock-widget/embed_example.html](https://nocodermurad.github.io/flip-clock-widget/embed_example.html)

---

## Features

* **Minimal Aesthetics:** Grayscale monochrome palette, strict border radius (12px), and very thin subtle borders (1px visual weight).
* **Smooth Animation:** Custom-tailored 250ms horizontal folding transition using GPU-optimized 3D transforms (`rotateX` & `opacity`).
* **Auto-Scaling Layout:** Dynamically adjusts the base font size based on the dimensions of the parent iframe/container.
* **Pixel-Grid Alignment:** Forces even integer sizing using `Math.floor` to eliminate sub-pixel rendering gaps and text shifts.
* **Auto Theme Detection:** Automatically adapts to dark and light modes using system preferences (`prefers-color-scheme`). No toggle or setup required.
* **No Dependencies:** Self-contained vanilla codebase—zero external JS libraries or heavy packages.

---

## How to Embed

You can integrate this clock into any web page or Notion workspace via an `iframe`.

```html
<iframe 
  src="https://nocodermurad.github.io/flip-clock-widget/index.html" 
  style="width: 100%; height: 250px; border: none; overflow: hidden; display: block;"
  title="Minimalist Monochrome Flip Clock Widget"
  loading="lazy">
</iframe>
```

