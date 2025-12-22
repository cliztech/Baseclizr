## 2025-05-23 - Interactive Elements Semantics
**Learning:** Replaced non-interactive `span` elements used as buttons with actual `button` elements. This provides native keyboard support (Enter/Space to activate) and better screen reader announcements without complex ARIA roles.
**Action:** Always check clickable elements that are not links or buttons. If they perform an action, they should likely be `<button>`.
