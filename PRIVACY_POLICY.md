# Privacy Policy for Liuer SEO Analyzer

Last updated: June 22, 2026

Liuer SEO Analyzer ("the Extension") is a Chrome extension that helps users analyze search results, AI answer blocks, content briefs, and on-page SEO data.

This Privacy Policy explains what information the Extension processes, when information is sent to the Liuer API, and how users can control their data.

## Information The Extension Processes

When you use the Extension, it may process information from the current browser tab, including:

- Current page URL and page title.
- Search result titles, descriptions, URLs, related keywords, ads count, AI answer text, and AI source cards from supported search result pages.
- On-page SEO information, including page title, meta description, canonical URL, robots meta tag, headings, body text, schema data, links, outbound links, image URLs, keyword density, and basic page structure.
- Link and image HTTP status information, such as whether links or images return successful or error responses.

The Extension processes this information to provide SEO research, SERP analysis, content brief generation, and on-page SEO checking features.

## API Key Storage

If you enter a Liuer API key, the Extension stores the key locally in Chrome storage on your browser.

The API key is used only to authenticate requests to the Liuer API. The Extension does not intentionally log your API key to the browser console.

You can remove the saved API key at any time from the Extension settings.

## When Data Is Sent To The Liuer API

The Extension can run local scan and SEO check features without an API key.

The Extension does not send SERP data or page content to the Liuer API unless you explicitly start an API-powered action, such as:

- Generating a content brief.
- Analyzing a page against selected SERP research.
- Requesting an article based on a generated Content Plan.

When you start one of these actions, the Extension may send the relevant research data to the Liuer API, including:

- Keyword and search engine information.
- SERP research data, such as organic results, related keywords, AI answer text, and AI source cards.
- Page SEO data, such as title, meta description, headings, body text, links, images, and page sections.
- Content Plan data, such as the recommended title, content strategy, outline, semantic keywords, required topics, exclusions, and questions to answer.
- Content Plan recommendations, including entities, content gaps, and SEO/AEO recommendations.

This data is used to generate SEO/AEO recommendations, search intent analysis, content plans, page comparison results, and user-requested articles.

When you request an article, the request is processed by the Liuer API and the generated result may be delivered to the website connected to your Liuer account.

## How Information Is Used

Information processed by the Extension is used to:

- Display SERP and SEO analysis inside the Extension.
- Generate content briefs and search intent recommendations.
- Queue article generation requests based on a Content Plan selected by the user.
- Compare a page with SERP research.
- Identify SEO issues, missing content, weak content, unnecessary content, broken links, broken images, and optimization opportunities.

We do not sell user data.

## Data Sharing

Data is sent to the Liuer API only when you intentionally use API-powered analysis features. The Liuer API may use AI model providers and infrastructure service providers acting on Liuer's behalf to process the request and generate the requested analysis or article.

These service providers may process only the data necessary to provide the requested feature. Data is not shared for personalized advertising, creditworthiness, or unrelated purposes.

We do not sell, rent, or trade user data to third parties.

## Browsing Data

The Extension reads the URL, title, and relevant content of the active page only when needed for a user-facing SERP scan, SEO check, or page comparison. It does not collect or maintain a complete history of websites you visit, and it does not monitor mouse movement, scrolling, keystrokes, or browsing behavior for advertising or analytics.

## Local Browser Data

The Extension may store the following data locally in Chrome storage:

- API key.
- API verification status.
- Extension language settings.
- Analysis language settings.
- Current asynchronous job state, such as a content brief or page analysis that is still being processed.

Local storage is used to keep the Extension working across browser sessions and Side Panel reopen events.

Content plans and analysis results requested through the Liuer API may remain available through the API-backed history features associated with your Liuer account. For questions about server-side retention or deletion requests, contact us using the email address below.

## Permissions

The Extension requests the following Chrome permissions:

- `activeTab`: to read the current tab when you use the Extension.
- `scripting`: to inject the local extractor script into the active tab for SERP and SEO analysis.
- `storage`: to save settings, API key, and active job state locally.
- `sidePanel`: to display the Extension interface in Chrome Side Panel.
- `http://*/*` and `https://*/*`: to check HTTP status for internal links, outbound links, and image URLs during user-initiated SEO checks.

The Extension uses these permissions only to provide its SEO analysis features.

## User Control

You can:

- Use local SEO checks without entering an API key.
- Choose when to send data to the Liuer API by clicking API-powered analysis actions.
- Remove the saved API key from Extension settings.
- Uninstall the Extension at any time from Chrome.

## Data Security

We use reasonable technical measures to protect data transmitted to the Liuer API. However, no method of transmission or storage is completely secure.

You should not enter API keys or sensitive data into pages or workflows unless you trust the service and your browser environment.

## Children's Privacy

The Extension is intended for SEO, marketing, and website analysis use. It is not directed to children.

## Changes To This Policy

We may update this Privacy Policy from time to time. If we make changes, we will update the "Last updated" date at the top of this document.

## Contact

For privacy questions or support, contact:

```text
liuertech@gmail.com
```
