## 2024-05-23 - Accessibility of Custom Interactive Elements
**Learning:** Using `<span>` or `<div>` for interactive elements (like the mute button) without `role="button"`, `tabindex="0"`, and `aria-label` makes them inaccessible to screen readers and keyboard users.
**Action:** Always use semantic `<button>` elements for actions. If custom styling requires a different tag or structure, ensure `role`, `tabindex`, and `aria-label` are present, and keyboard events (Enter/Space) are handled. Using semantic HTML is preferred as it handles keyboard interaction out of the box.
