# Privacy Policy – AI Code Reader

Last updated: March 2026

AI Code Reader is a Chrome extension designed to help users understand code by generating explanations using AI models.

## Information We Collect

This extension does **not collect or store personal information**.

The extension may process the following data temporarily:

* Code snippets selected by the user
* User email addresses for authentication (when users choose to sign in)
* Usage statistics (token counts) for rate limiting

## How Information Is Used

When the user requests a code explanation, the selected code snippet is sent to the AI service to generate a response.

Supported AI service:

* Custom AI service endpoint (https://ai-code-explainer-new.ai-code-explainer.workers.dev/)

The code snippet is transmitted only for the purpose of generating an explanation.

## Authentication System

Users may choose to authenticate using Google OAuth to:

* Access higher daily token limits
* Enable persistent usage tracking across sessions

When users authenticate:

* Only email address and name are collected from Google
* Authentication tokens are stored locally in the browser
* Users can sign out at any time to remove stored authentication data

## Guest Usage

Users can use the extension without authentication:

* Limited daily token usage
* Usage tracking is session-based
* No personal information is required

## Data Storage

The extension stores the following locally in the user's browser using Chrome storage:

* Authentication tokens (when users sign in)
* User email and name (when users sign in)
* Usage statistics for rate limiting

This data is stored **locally on the user's device** and is **not transmitted to any server other than the AI service endpoint**.

## Data Sharing

This extension does **not sell, transfer, or share user data** with third parties.

The only external communication occurs when:

* Sending the user-selected code snippet to the AI service to generate an explanation
* Transmitting authentication tokens to the AI service for rate limiting and user identification

## Security

* Authentication tokens and preferences are stored using Chrome's secure extension storage system
* Users are responsible for keeping their authentication secure
* Users can sign out at any time to remove stored authentication data

## Changes to This Policy

This privacy policy may be updated periodically. Updates will be reflected on this page.

## Contact

For questions or concerns, please contact:
ai.code.explainer@gmail.com

Extension developer via GitHub repository.
