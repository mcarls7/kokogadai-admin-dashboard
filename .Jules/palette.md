## 2026-06-27 - Balancing Scannability and Clutter in Minimal Docs
**Learning:** In very short documents (less than a page), "Back to top" links can introduce more visual noise than utility. However, explicit HTML anchors with `id` attributes remain superior to auto-generated ones for long-term navigation stability.
**Action:** Prioritize a horizontal navigation bar for scannability, but omit vertical "Back to top" links unless the document exceeds two viewport heights. Always use `id` over deprecated `name` for manual anchors.
