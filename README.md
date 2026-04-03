# Webapps

A collection of single-file web applications designed to run in your browser. Just click the links below to use the App directly in your browser.

## Apps

Just click the links below to use the App directly in your browser.

- [GanttChart.html](https://pcerf.github.io/webapps/GanttChart.html) — Interactive Gantt chart timeline builder with live editing, drag-to-resize, dependency arrows, and SVG/PNG/HTML export.
- [DocScan.html](https://pcerf.github.io/webapps/DocScan.html) — Mobile-friendly document scanner that captures pages via camera, applies perspective correction, and exports to PDF with optional OCR.

## Privacy and Security

These apps are intended to run entirely in the user's browser. **However, some apps may load third-party libraries from CDNs on demand** (see [Acknowledgments](#acknowledgments) below), which means network requests are made and standard browser information is exposed to those servers. **You are responsible for reviewing the code yourself before use.** Use at your own risk.

## Acknowledgments

DocScan.html optionally loads the following external libraries at runtime (not bundled):

- [Tesseract.js](https://github.com/naptha/tesseract.js) (Apache-2.0) — OCR engine, loaded from `cdn.jsdelivr.net` when the user enables OCR.
- [Transformers.js](https://github.com/huggingface/transformers.js) (Apache-2.0) — ML inference runtime, loaded from `cdn.jsdelivr.net` when the user enables AI title generation.
- [HuggingFace ONNX models](https://huggingface.co/onnx-community) (Apache-2.0) — Small language models downloaded from `huggingface.co` for local title suggestion.

This list is not guaranteed to be complete. **You are responsible for reviewing the code yourself before use.** Use at your own risk.

## License

MIT License

Copyright (c) 2026 Pascal Cerfontaine

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Disclaimer

This software is provided as-is with no warranties. The authors are not responsible for any damages, data loss, or privacy issues arising from the use of these applications. Users should independently verify that the applications meet their security and privacy requirements before use.
