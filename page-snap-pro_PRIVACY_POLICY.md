# Privacy Policy for PageSnap Pro

**Effective Date:** September 22, 2026  
**Last Updated:** September 22, 2026  

Thank you for choosing **PageSnap Pro** ("we", "our", or "the extension"). PageSnap Pro is a Google Chrome browser extension designed to capture full-page and visible-area screenshots and export them locally as PNG, JPG, or PDF files.

We believe that your privacy is a fundamental right. This Privacy Policy outlines our practices regarding data collection, usage, storage, and disclosures.

---

## 1. Zero Data Collection & Transmission

**PageSnap Pro does NOT collect, store, transmit, or sell any personal information, browsing history, or user data.**

- **No Remote Servers:** The extension operates without an external backend or database.
- **No Analytics or Trackers:** We do not include any tracking pixels, telemetry, Google Analytics, or third-party monitoring scripts.
- **No Account Required:** You do not need to register, create an account, or log in to use the extension.

---

## 2. How Data & Screenshots Are Processed

All operations are performed **100% locally in your browser**:

- **Screenshot Processing:** When you capture a webpage, image slices are rendered and stitched in your browser's local memory using the HTML5 Canvas API and bundled client-side libraries.
- **Exporting Files:** When you download a PNG, JPG, or PDF, the file is generated entirely within your local browser environment and saved directly to your device's Downloads directory.
- **Clipboard:** If you choose to copy an image to your clipboard, the data is written directly to your operating system's clipboard using standard browser APIs.

**At no point are your screenshots, captured URLs, or page contents ever uploaded or transmitted across the internet.**

---

## 3. Chrome Extension Permissions

PageSnap Pro requests only the minimal permissions required to provide its core screenshot functionality:

| Permission | Purpose |
|---|---|
| **`activeTab`** | Enables the extension to access the active tab only when you click the extension popup to measure page dimensions and capture screenshots. |
| **`scripting`** | Allows the extension to execute temporary scrolling commands on the active tab to capture full-page content. |
| **`downloads`** | Required to save your exported screenshot files (PNG, JPG, PDF) directly to your local computer. |
| **`storage`** | Used solely to save your chosen preferences (such as default export format, JPG quality setting, and scale multiplier) locally on your device. |

---

## 4. Third-Party Services

PageSnap Pro does not integrate with any third-party advertising networks, cloud storage providers, or analytics platforms. All libraries (including jsPDF) are bundled locally inside the extension package.

---

## 5. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect improvements or changes in our extension. Any updates will be posted to this page with an updated "Last Updated" date.

---

## 6. Contact Us

If you have any questions or concerns regarding this Privacy Policy or the PageSnap Pro extension, please feel free to reach out via our GitHub repository or support email.
