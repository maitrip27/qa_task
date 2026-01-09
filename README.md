 Overview

This README describes the **Low Severity UI bug related to cross-browser compatibility** identified during QA testing of the SellSharp website.

* **Website Tested:** [https://sellsharp.co/](https://sellsharp.co/)
* **Module:** Home Page UI
* **Browser Affected:** Mozilla Firefox
* **Browser Working Fine:** Google Chrome, Microsoft Edge
* **Bug Severity:** Low
* **Bug Type:** UI / Cross-Browser Compatibility

---

##Bug Summary

Minor UI misalignment is observed on the SellSharp homepage when accessed using **Mozilla Firefox**. The issue affects visual alignment and spacing but does **not impact functionality**.

---

## Steps to Reproduce

1. Open **Mozilla Firefox** browser
2. Navigate to **[https://sellsharp.co/](https://sellsharp.co/)**
3. Observe the homepage CTA section and input form

---

## Expected Result

* Buttons and input fields should be properly aligned
* Spacing between UI elements should be consistent across all browsers

---

## Actual Result

* "Get Started" button appears slightly misaligned
* Inconsistent spacing between input field and "Generate Email" button
* UI layout differs from Chrome and Edge

---

##
---


## Recommendation

* Apply CSS cross-browser compatibility fixes
* Test UI using Firefox developer tools
* Use consistent flexbox/grid styling for alignment


