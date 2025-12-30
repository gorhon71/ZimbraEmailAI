# Privacy Policy for Zimbra Email AI

**Last Updated:** December 30, 2025

Zimbra Email AI ("we", "our", or "us") is dedicated to protecting your privacy. This Privacy Policy explains how our Chrome Extension handles your data.

## Data Collection and Usage

**We do not collect, store, or share any of your personal data, email content, or usage data on our servers.**

The extension functions entirely as a client-side interface between your browser and an AI service that **you configure**.

### How Data is Processed
1.  **Email Content**: When you use the "Generate Reply" or similar features, the content of the email you are viewing is temporarily read by the extension.
2.  **Transmission**: This content is sent directly to the AI API endpoint that **you have specified** in the extension's options (e.g., your local Ollama instance or your private server).
3.  **No Intermediaries**: The data goes directly from your browser to your configured endpoint. It does not pass through our servers or any third-party analytics services controlled by us.

## User Responsibility
You are responsible for ensuring that the AI endpoint you configure (e.g., the Ollama server URL) handles your data in accordance with your own privacy expectations and security requirements.

## Permissions
The extension requests the following permissions for specific purposes:
-   **Storage**: To save your configuration settings (e.g., your customized AI server URL) locally in your browser.
-   **Scripting**: To inject the assistant interface into the Zimbra Web Client tab.
-   **Host Permissions**: To communicate with the Zimbra server you specify and the AI API endpoint you specify.

## Changes to This Policy
We may update this Privacy Policy from time to time. If we make material changes, we will notify you by updating the date at the top of this policy.

## Contact
If you have questions about this policy, please contact the developer via the Chrome Web Store support page.
