## 2024-05-23 - Interactive Elements Semantics
**Learning:** Interactive controls like "Mute" were implemented as `<span>` tags, making them inaccessible to keyboard and screen reader users.
**Action:** Always use `<button>` or `<a>` for interactive elements, or provide full ARIA roles and keyboard handlers if using other elements is unavoidable.
