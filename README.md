# 🧠 Advanced Text Analyzer

A lightweight, pluggable module to clean, enhance, and inject context into GPT prompts — ideal for any web interface or chat integration.

## 🔧 Features

- Removes noise and filler from user input
- Adds topic/intent hints automatically
- Easily extendable (toxicity filter, rephraser, etc.)
- Works in-browser or with frameworks

## 🚀 Usage

```html
<textarea id="prompt"></textarea>
<button id="submit">Submit</button>
<pre id="output"></pre>
```

```js
import { attachAnalyzerToForm } from './src/analyzer.js';

attachAnalyzerToForm("prompt", "submit", (refined) => {
  console.log("Refined Prompt:", refined);
});
```

## 📦 Install via NPM (coming soon)

```bash
npm install advanced-text-analyzer
```

## 🛠 To Build

```bash
npm install
npm run build
```

## 📄 License

MIT
