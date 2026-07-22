🎨 Pix2Pix: Interactive Image-to-Image Translation Demo

An interactive, browser-based web application designed to demonstrate the conceptual framework of Pix2Pix (Conditional Generative Adversarial Networks).

While a real Pix2Pix architecture relies on deep neural networks trained on heavy GPU compute, this single-page app uses custom client-side HTML5 Canvas pixel manipulation algorithms to simulate traditional image-to-image transformations instantly in the browser.

🌟 Key Features
Interactive Dual-Canvas Interface: Side-by-side comparison of original input and transformed output images.

Simulated Translation Modes:

🏁 Grayscale: Converts RGB channels to uniform luminance averages.

🔄 Invert Colors: Inverts pixel RGB values (photographic negative effect).

📜 Sepia Tone: Applies warmth matrices to mimic vintage photographs.

✏️ Basic Sketch: Applies a simplified Sobel edge-detection filter to mimic photo-to-sketch translation.

👾 Pixelate: Divides images into custom block sizes and averages color groups to simulate a mosaic filter.

Responsive Layout: Built with Tailwind CSS for seamless viewing across desktop and mobile browsers.

Educational Explanations: Built-in deep-dives explaining U-Net Generators, PatchGAN Discriminators, and L1 vs. Adversarial Loss functions.


🛠️ Tech Stack

Frontend Framework: HTML5 & CSS3

Styling: Tailwind CSS (via CDN)

Image Processing: JavaScript (HTML5 Canvas ImageData & Uint8ClampedArray manipulation)

Typography: Inter Font Family (Google Fonts)

📂 File Structure
This project is fully self-contained in a single file:

Plaintext
├── index.html     # HTML structure, Tailwind layout, educational cards, and Canvas manipulation algorithms
