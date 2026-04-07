# Privacy Policy

**Effective Date:** 2026-04-07

## Introduction
QA Session Recorder & Report Generator ("we", "our", or "the Extension") is committed to protecting your privacy. This Privacy Policy explains how our Chrome Extension collects, uses, and protects your information while you use it.

## 1. Information Collection
Our extension is designed to act as a transparent testing and recording utility. We **do not** collect any data silently in the background. Data collection occurs **only** during an active session directly initiated by you.

During an active session, the Extension captures the following user interactions to generate test reports:
*   **Navigation Events**: URLs (including query parameters) and Page Titles.
*   **User Actions**: Click targets, element labels, check box toggles, and dropdown selections.
*   **Form Inputs**: Values typed into input fields (truncated to a maximum of 30 characters).
*   **Screenshots**: Only captured manually when you explicitly trigger the screenshot functionality.

## 2. Sensitive Data Filtering
We prioritize your privacy and explicitly filter out sensitive information. The extension is strictly programmed to **ignore and exclude**:
*   Any inputs where the field type is `password` or `hidden`.
*   Fields identifying themselves (via ID, or name) as containing passwords, secure tokens, authentication strings, or credit card information.

## 3. How We Use the Data
Any data captured is restricted to the browser session and is used *exclusively* for:
*   Generating structured QA test reports (HTML or JSON) at your request.
*   Creating formatted bug reports and sending them to your connected Jira project.

## 4. Where Your Data is Stored
*   All recorded session steps, intercepted actions, and manually logged bugs are stored strictly locally in your browser using Chrome's local storage (`chrome.storage.local`).
*   Your OAuth authentication tokens for Jira (if configured) are similarly stored securely in your local browser cache.
*   We do NOT transmit your testing data to any third-party servers, analytics providers, or external databases, outside of explicitly configured Jira environments you choose to link.

## 5. UI Transparency
During any data collection period, a visual recording indicator (**🔴 Session Active**) remains firmly visible on your screen. When this indicator disappears, all session logging abruptly stops.

## 6. Your Data Rights
Because all data resides strictly on your local machine, you have full control over it. You can clear your testing session reports instantly by clearing your browser storage, stopping a session, or uninstalling the extension.

## 7. Changes to this Policy
We may periodically update this policy to reflect changes in our tool or for legal compliance. We encourage you to review this policy whenever we update the extension.

For any questions or concerns regarding our privacy practices, please contact the developer via the support tab on our Chrome Web Store page.
