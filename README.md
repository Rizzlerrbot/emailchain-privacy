# emailchain-privacy
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Privacy Policy — AI Email Chain</title>
<style>
body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; max-width: 800px; margin: 0 auto; padding: 40px 24px; color: #111; line-height: 1.7; }
h1 { font-size: 28px; margin-bottom: 8px; }
h2 { font-size: 18px; margin-top: 36px; margin-bottom: 8px; border-bottom: 1px solid #eee; padding-bottom: 6px; }
p, li { font-size: 15px; color: #333; }
ul { padding-left: 20px; }
.meta { color: #888; font-size: 14px; margin-bottom: 32px; }
a { color: #e8590c; }
.highlight { background: #fff8f5; border-left: 3px solid #e8590c; padding: 12px 16px; margin: 16px 0; border-radius: 0 4px 4px 0; }
</style>
</head>
<body>
<h1>Privacy Policy</h1>
<p class="meta">
  Extension: AI Email Chain<br>
  Developer: ChromeToolsHQ<br>
  Website: emailchain.com<br>
  Last updated: April 19, 2026
</p>

<h2>Overview</h2>
<p>AI Email Chain ("the Extension") is a Gmail productivity tool that helps users draft AI-powered email replies, log contacts to a built-in CRM, and create follow-up tasks — all from within Gmail. This Privacy Policy explains what data the Extension accesses, how it is used, and your rights regarding that data.</p>

<h2>Data the Extension Accesses</h2>
<p>AI Email Chain accesses the following data <strong>only when you actively click an action button</strong> within Gmail:</p>
<ul>
  <li>The subject line of the currently open email</li>
  <li>The sender's name and email address</li>
  <li>The body text of the currently open email</li>
  <li>The URL of the currently open Gmail thread</li>
</ul>
<div class="highlight">
  <strong>Important:</strong> This data is accessed only on explicit user action — never passively, automatically, or in the background.
</div>

<h2>How Your Data Is Used</h2>

<p><strong>AI Reply Drafting (OpenAI API):</strong><br>
When you click "Draft Reply" or "Do Everything," the current email's subject, sender, and body are sent directly from your browser to OpenAI's API (api.openai.com) using your own personal OpenAI API key. This communication goes directly between your browser and OpenAI — it does not pass through our servers at any point. Please review <a href="https://openai.com/privacy" target="_blank">OpenAI's Privacy Policy</a> for how they handle data sent to their API.</p>

<p><strong>CRM Logging:</strong><br>
When you click "Log to CRM" or "Do Everything," the sender's name, email address, and email subject line are saved to your browser's local storage on your device only. This data never leaves your device and is never transmitted to our servers or any third party.</p>

<p><strong>Task Creation:</strong><br>
When you click "Add Task" or "Do Everything," a follow-up task is created and saved to your browser's local storage on your device only. This data never leaves your device.</p>

<h2>Your OpenAI API Key</h2>
<p>Your OpenAI API key is stored in Chrome's secure local storage API on your device only. It is never transmitted to our servers. The key is used solely to make API calls directly from your browser to OpenAI on your behalf.</p>

<h2>Personal Communications</h2>
<p>The Extension reads the content of Gmail emails you are actively viewing when you click an action button. This email content is used only to generate AI replies via OpenAI's API. Email content is never stored on our servers, never shared with third parties other than OpenAI (per your explicit action), and never used for advertising or analytics purposes.</p>

<h2>Data Stored Locally on Your Device</h2>
<p>The following data is stored exclusively in your browser's local storage:</p>
<ul>
  <li>CRM contact entries (name, email, subject, notes)</li>
  <li>Follow-up tasks with linked Gmail thread URLs</li>
  <li>Your OpenAI API key</li>
  <li>Extension settings and preferences (tone, signature)</li>
</ul>
<p>None of this data is transmitted to our servers or any third party.</p>

<h2>Data We Do NOT Collect</h2>
<ul>
  <li>We do not store your emails on our servers</li>
  <li>We do not collect health information</li>
  <li>We do not collect financial information</li>
  <li>We do not use analytics or tracking of any kind</li>
  <li>We do not sell data to advertisers or data brokers</li>
  <li>We do not share data with any third party except OpenAI (per your explicit action)</li>
  <li>We do not read emails passively or in the background</li>
</ul>

<h2>Permissions Used</h2>
<p><strong>storage:</strong> Used to save your CRM entries, tasks, settings, and API key locally on your device only. No data is transmitted externally.</p>
<p><strong>Host permission (mail.google.com):</strong> Required to inject action buttons into Gmail and read the currently open email when you click an action button. The extension only activates on user action — it does not passively read your inbox.</p>

<h2>Third-Party Services</h2>
<p>AI Email Chain uses one third-party service:</p>
<ul>
  <li><strong>OpenAI API</strong> — Email content is sent to OpenAI only when you explicitly click a draft or "Do Everything" action. This is done using your own API key. See <a href="https://openai.com/privacy" target="_blank">OpenAI's Privacy Policy</a>.</li>
</ul>
<p>No other third-party services, analytics platforms, or advertising networks are used.</p>

<h2>Data Retention and Deletion</h2>
<p>All data is stored locally in your browser. You can delete all Extension data at any time by:</p>
<ul>
  <li>Uninstalling the Extension from Chrome</li>
  <li>Using the "Clear Data" option in Extension Settings</li>
  <li>Clearing your browser's local storage for the Extension</li>
</ul>

<h2>Children's Privacy</h2>
<p>This Extension is not directed at children under the age of 13. We do not knowingly collect data from children.</p>

<h2>Changes to This Policy</h2>
<p>We may update this Privacy Policy from time to time. Updates will be reflected by a revised date at the top of this page. Continued use of the Extension constitutes acceptance of the updated policy.</p>

<h2>Contact</h2>
<p>If you have questions about this Privacy Policy please contact:</p>
<p>
  <strong>Developer:</strong> ChromeToolsHQ<br>
  <strong>Email:</strong> <a href="mailto:Mathew@NBInnovations.com">Mathew@NBInnovations.com</a><br>
  <strong>Website:</strong> <a href="https://emailchain.com">emailchain.com</a>
</p>
</body>
</html>
