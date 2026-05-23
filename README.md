# TryIt Suite | Developer Hub

A lightweight, high-performance suite of interactive web utilities built entirely with semantic HTML5, modern CSS3, and vanilla JavaScript. Designed for developers, designers, and data analysts, this dashboard provides standalone tools that run entirely client-side in the browser—requiring zero server overhead, external API dependencies, or build processing.

---

## Live Demo
Deploy your live Netlify link here: **tryit-playground.netlify.app**

---

## 🧰 Core Utilities Included

### 💻 Compilers & Playgrounds
* **HTML Compiler (`html-compiler.html`):** Real-time HTML preview and render canvas.
* **JS Compiler (`js-compiler.html`):** Client-side JavaScript evaluation environment.
* **Python Compiler (`python-compiler.html`):** Browser-based Python script workspace.
* **Markdown Compiler (`markdown-compiler.html`):** Live markdown-to-HTML translator.
* **SQL Sandbox (`sql-sandbox.html`):** Client-side query evaluator and database workspace.

### 📊 Data & Token Processing
* **CSV Converter (`csv-converter.html`):** Formats raw cell lists into structured JSON scripts.
* **JSON Viewer (`json-viewer.html`):** Formats, minifies, and inspects complex object strings.
* **JWT Debugger (`jwt-debugger.html`):** Decodes and reviews JSON Web Token payload layers.
* **Token Generator (`token-generater.html`):** Generates cryptographically secure keys and authorization strings.
* **URL Handler (`url-handler.html`):** Encodes, decodes, and parses complex web parameters.

### 🎨 Design & Animation Sandboxes
* **Animation Studio (`animation-studio.html`):** Timeline and visual configuration layout engine.
* **Box Model (`box-model.html`):** Interactive visual guide for margins, borders, paddings, and element widths.
* **Color Sandbox (`color-sandbox.html`):** Palette selector and color code scheme generator.

### 🔧 Text & Regex Debuggers
* **Diff Checker (`diff-checker.html`):** Side-by-side text parsing tool to isolate file differences.
* **RegEx Tester (`regex-tester.html`):** Real-time regex pattern validator with custom string highlighting.
* **Core Tool template (`tool.html`):** Standard blueprint boilerplate for future dashboard extensions.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** Vanilla HTML5, CSS3 Custom Properties (CSS Variables) for cohesive dark-theme UI components.
* **Engine Logic:** Pure ES6+ JavaScript (Client-side execution only).
* **Brand Assets:** Clean, custom square logo configuration natively linked through the document heads.
* **Hosting Optimization:** Engineered for friction-free hosting configurations (optimized for manual static asset drops on Netlify).

---

## 📂 Local Directory Structure

This matches your workspace layout exactly:

```text
📁 tryit-suite-hub/
 ├── 📄 animation-studio.html
 ├── 📄 box-model.html
 ├── 📄 color-sandbox.html
 ├── 📄 csv-converter.html
 ├── 📄 diff-checker.html
 ├── 📄 html-compiler.html
 ├── 📄 index.html              # Main Dashboard Entry Point
 ├── 📄 js-compiler.html
 ├── 📄 json-viewer.html
 ├── 📄 jwt-debugger.html
 ├── 📄 logo.png                # App favicon & brand logo element
 ├── 📄 markdown-compiler.html
 ├── 📄 python-compiler.html
 ├── 📄 regex-tester.html
 ├── 📄 sql-sandbox.html
 ├── 📄 token-generater.html
 ├── 📄 tool.html
 └── 📄 url-handler.html
