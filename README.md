# Elite Burp Suite HTTP History Analyzer

A robust, browser-based visualization tool that turns your Burp Suite XML exports into interactive, organized network graphs using D3.js.

## 🚀 Live Demo
**[Launch the Analyzer](https://raunaksplanet.github.io/Elite-Burp-Suite-HTTP-History-Analyzer/)**

## ✨ Key Features
*   **Smart Visualization:** View traffic as a Force Cluster, Hierarchical Tree, or Radial Graph.
*   **Gravity Clustering:** Uses advanced physics to keep nodes organized in a tight block, preventing them from scattering into the void.
*   **Auto-Fit Camera:** Automatically centers and zooms to fit your data on the screen.
*   **Granular Filtering:** Hide/Show nodes based on Host, Path, HTTP Method, Status Code, or Parameter.
*   **Privacy Focused:** 100% client-side processing. Your logs never leave your browser.

## 🛠️ How to Use
1.  **Export from Burp:**
    *   Go to **Proxy > HTTP History** (or Target).
    *   Select requests -> Right Click -> **Save items**.
    *   Ensure the file format is **XML**.
2.  **Upload:**
    *   Open the [Live Demo](https://raunaksplanet.github.io/Elite-Burp-Suite-HTTP-History-Analyzer/).
    *   Drag and drop your `.xml` file into the upload zone.
3.  **Analyze:**
    *   Use the sidebar to filter noise and switch layouts.

## 💻 Tech Stack
*   HTML5 & CSS3 (Inter Font)
*   [D3.js v7](https://d3js.org/)
