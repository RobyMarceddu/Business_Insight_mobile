# Stats Preview Card Component (Desktop-First)

This is a solution to the [Stats preview card component challenge from Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JSN2JgK).

This project is a single-page component demonstrating a common landing page layout: a 50/50 split between text content and an image.

### Screenshot

<img width="237" height="419" alt="mobile_design_screenshot" src="https://github.com/user-attachments/assets/961ebe33-2851-45fc-87bc-6d2404d4b28e" />


---

### 🚀 Features

* **50/50 Layout:** Built with CSS Grid for a clean separation between text and image.
* **Image Filter (Overlay):** A vibrant color filter applied to the image, matching the highlighted text color (`.insights`).

---

### 🛠️ Built with (Tech Stack)

* **Semantic HTML5:** Structured with tags like `<main>`, `<section>`, and `<h1>`.
* **Modern CSS:**
    * **CSS Grid** for the main layout.
    * **Flexbox** for aligning the statistics.
    * **Pseudo-elements (`::before`)** for the overlay effect.
    * **`mix-blend-mode` property** to blend the filter color with the image.
    * **CSS Custom Properties** (Variables) for colors and fonts (optional but recommended).

---

### 💡 How the Overlay Works

The key feature is the purple filter over the image. This effect is achieved purely in CSS using:

1.  A `::before` pseudo-element on the image column.
2.  The `background-color` property set to `#aa5cdb`.
3.  The `opacity` and `mix-blend-mode: multiply` properties to blend the color with the image below, preserving shadows and highlights.
