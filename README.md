# Web Safe Image Converter

**Web Safe Image Converter** is a high-performance, privacy-focused web tool designed to batch-convert, resize, and smart-crop images into the WebP format. Unlike other converters, all processing happens locally in your browser — your images never touch a server.

---

## 🚀 Key Features

### Batch Processing
Drop dozens of images at once and convert them in seconds.

### Smart Center-Crop
Automatically scales and crops images to fit your target dimensions without squishing or stretching the subject.

### Privacy First
100% client-side. No data is uploaded to any cloud, making it safe for sensitive or private photos.

### Metadata Stripping
Automatically removes EXIF, GPS, and other hidden metadata to ensure the smallest possible file size.

### ZIP Export
Bundles all optimized images into a single `.zip` file for easy downloading.

### Quality Alerts
Visual **LOW RES** warnings appear if your original image is smaller than your target size, helping prevent blurry results.

### Drag & Drop
Intuitive interface with native drag-and-drop support.

---

## 🛠️ How It Works

The tool uses the modern **HTML5 Canvas API** to redraw pixels at the target resolution and the **JSZip** library to package the results.

By using `image/webp` encoding, it typically achieves a **50–80% reduction in file size** compared to standard JPEGs.

---

## 📦 Installation & Deployment

Since this is a static single-page application (SPA), you can host it for free on GitHub Pages.

### GitHub Pages Setup

1. Create a new repository on GitHub.
2. Upload `index.html` (the project file).
3. Go to **Settings → Pages**
4. Set **Source** to **Deploy from a branch**
5. Select `main` (or `master`)

Your tool will be live at:

```text
https://theweboliciousway.github.io/websafe-image-optimiser
