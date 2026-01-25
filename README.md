# StartHub Email Templates

## Overview
This repository contains high-quality, responsive HTML email templates converted from Figma designs. These templates are engineered to ensure pixel-perfect rendering across all major email clients while maintaining a consistent "Corporate Standard" design language.

## Templates

### 1. Live Notification (`index.html`)
*   **Purpose**: User notification for account activation and setup completion.
*   **Key Sections**: membership details, account overview, extensive contact info, and multiple calls-to-action (Set Password, Access Dashboard).

### 2. Welcome Email (`second.html`)
*   **Purpose**: Onboarding email introducing core services and office locations.
*   **Key Sections**: Service highlights (Mail Handling, Live Answering, Meeting Rooms) presented in a card layout, office location map, and dashboard access.

---

## Technical Features

These templates have been built with industry-leading best practices to ensure robustness and visual fidelity.

### 📱 Fluid Hybrid Design
*   **Desktop-on-Mobile Experience**: Unlike traditional responsive emails that stack everything into a single column, these templates use a **Fluid Design** approach.
*   **Smart Scaling**: Multi-column layouts (like 2-column info blocks or 3-column service cards) remain side-by-side on mobile devices.
*   **Fluid Typography**: Font sizes (`h1`, `h2`, `p`) and padding automatically scale down on screens narrower than 600px to fit the content comfortably without breaking the layout.

### 🌙 Dark Mode Support
*   **Smart Adaptation**: Includes `color-scheme` meta tags and `@media (prefers-color-scheme: dark)` overrides.
*   **Professional Look**: Instead of raw color inversion, the dark mode uses specific "Dark Grey" tones (`#1a1a1a`) and white text to maintain a premium, readable aesthetic while preserving brand integrity.

### 📧 Cross-Client Compatibility
*   **Outlook Optimized**: Extensive usage of `<!--[if mso]>` conditional comments and VML (Vector Markup Language) ensures gradients, widths, and tables render correctly on Outlook 2019, 2021, and Office 365.
*   **Gmail Ready**: All critical styles are written inline or supported by Gmail's rendering engine.
*   **Apple Mail**: Enhanced with specific webkit font smoothing and spacing.

### ⚡ Performance
*   **Width Constraints**: content is constrained to a standard **600px** width for optimal readability on all screens.
*   **Retina Images**: Images are styled with `max-width: 100%; height: auto;` to look sharp on high-density displays without breaking layouts.

---

## Usage Instructions

1.  **Editing**: Open the files in any code editor (VS Code, Sublime Text).
2.  **Images**: All images are currently hosted. For production, ensure image paths are absolute URLs pointing to your CDN.
3.  **Sending**:
    *   **Copy/Paste**: You can copy the raw HTML directly into email marketing platforms (Mailchimp, SendGrid, HubSpot, etc.).
    *   **Inline CSS**: The templates already use inline styles for maximum compatibility. No external stylesheets are required.

## Compatibility Checklist

| Client | Status |
| :--- | :--- |
| **Microsoft Outlook** (Windows/Mac) | ✅ Supported (via MSO tables) |
| **Gmail** (Web & App) | ✅ Supported |
| **Apple Mail** (iPhone/iPad/Mac) | ✅ Supported |
| **Yahoo! Mail** | ✅ Supported |
| **Android Mail** | ✅ Supported |
