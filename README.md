
# Smart Lead-Generation Contact Form

A responsive client-side lead capture form with real-time input sanitization, custom error states, and dynamic confirmation feedback.

## 🚀 Business Features
- **Zero Page Reloads:** Intercepts form submission using `event.preventDefault()` for a smooth single-page user experience.
- **Input Sanitization & Validation:** Strips accidental whitespace via `.trim()`, verifies email formatting, and enforces minimum message lengths.
- **Clear Visual Feedback:** Highlights invalid fields with red borders and field-specific warning prompts before displaying a personalized success confirmation.

## 🛠️ Tech Stack & Concepts Used
- **Semantic HTML5 & CSS3:** Clean card UI with dynamic error and success state styling.
- **Vanilla JavaScript:** `submit` event handling, string methods (`.trim()`, `.includes()`, `.length`), and dynamic DOM class toggling.
