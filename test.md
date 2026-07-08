# ✅ Accessibility Checklist (WCAG 2.2)

Use this checklist before shipping your website or application to ensure it meets accessibility best practices.

> **Target:** WCAG 2.2 Level AA

---

## 🎨 Visual

- [ ] Text contrast meets WCAG requirements (4.5:1 for normal text, 3:1 for large text and UI components)
- [ ] Information is not conveyed by color alone
- [ ] Text can be resized up to 200% without breaking layouts
- [ ] Icons and UI controls have sufficient contrast
- [ ] Focus indicators are clearly visible
- [ ] Content does not rely solely on images of text
- [ ] Layout remains usable in both portrait and landscape orientations

---

## ⌨️ Keyboard & Interaction

- [ ] All interactive elements are keyboard accessible
- [ ] Keyboard navigation follows a logical order
- [ ] No keyboard traps exist
- [ ] Skip to Content link is available
- [ ] Touch targets are at least 24×24 px (44×44 px recommended)
- [ ] Hover interactions are also accessible via keyboard
- [ ] Interactive elements have accessible names
- [ ] No interaction depends solely on gestures

---

## 📝 Forms

- [ ] Every input has an associated label
- [ ] Required fields are clearly indicated
- [ ] Placeholder text is not used as the only label
- [ ] Helper text is provided where necessary
- [ ] Error messages clearly explain the problem
- [ ] Error messages explain how to fix the issue
- [ ] Validation errors are announced to assistive technologies
- [ ] Form controls can be completed using only a keyboard

---

## 📄 Content

- [ ] Headings follow a logical hierarchy (H1 → H2 → H3...)
- [ ] Page has a single H1
- [ ] Links use descriptive text (avoid "Click here")
- [ ] Buttons have meaningful action labels
- [ ] Images include appropriate alt text
- [ ] Decorative images use empty alt attributes (`alt=""`)
- [ ] Tables include proper headers where applicable
- [ ] Language is simple and concise
- [ ] Page language is defined (`lang` attribute)

---

## 🔊 Media

- [ ] Videos include captions
- [ ] Audio content has transcripts
- [ ] Videos requiring visual context include audio descriptions when needed
- [ ] Media does not autoplay unexpectedly

---

## 🎞 Motion & Animation

- [ ] Animations are purposeful
- [ ] Motion can be reduced or disabled
- [ ] No flashing content exceeds 3 flashes per second
- [ ] Auto-rotating content can be paused or stopped

---

## ⚙️ System & Feedback

- [ ] Loading states are communicated
- [ ] Success messages are accessible
- [ ] Warning messages are accessible
- [ ] Error states are clearly communicated
- [ ] Empty states are designed
- [ ] Offline states are handled
- [ ] Edge cases have accessible designs
- [ ] Status updates are announced to assistive technologies where appropriate

---

## 🧑‍💻 HTML & Semantics

- [ ] HTML is semantic
- [ ] Landmarks (`header`, `main`, `nav`, `footer`) are used appropriately
- [ ] Buttons use `<button>` instead of clickable `<div>`
- [ ] Links use `<a>` elements with valid destinations
- [ ] ARIA is used only when necessary
- [ ] Duplicate IDs are avoided
- [ ] Document title is descriptive
- [ ] Meta viewport is configured correctly

---

## 🧪 Testing

- [ ] Keyboard-only navigation tested
- [ ] Screen reader tested (NVDA, VoiceOver, or JAWS)
- [ ] Color contrast verified
- [ ] Zoom tested up to 200%
- [ ] Responsive layout tested
- [ ] Browser accessibility audit completed
- [ ] Automated accessibility scan performed (Lighthouse, axe DevTools, WAVE)

---

## 🚀 Ready for Release

- [ ] Meets WCAG 2.2 Level AA
- [ ] Accessibility issues resolved
- [ ] Accessibility testing documented
- [ ] Developer handoff includes accessibility requirements
- [ ] Accessibility statement prepared (if applicable)

---

## Recommended Testing Tools

- Lighthouse
- axe DevTools
- WAVE Evaluation Tool
- Accessibility Insights
- NVDA Screen Reader
- VoiceOver (macOS/iOS)
- JAWS
- Colour Contrast Analyser

---

⭐ **Tip:** Accessibility is an ongoing process. Review this checklist during design, development, testing, and before every release.
