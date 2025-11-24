[PopSearch] – Privacy Policy (English)
Last updated: 2025-11-24

[PopSearch] ("the extension") respects your privacy and handles data as follows.

1. Data Collected

The extension does not automatically collect or transmit personal data to our own servers.

When you select text on a web page and invoke the extension, the selected text is inserted into your configured search URL at the {q} placeholder. The browser then opens that URL in a new tab so you can see the search results. The selected text is not stored by us or reused for any other purpose.

Your settings – including custom search engines, their URL templates with {q}, enabled/disabled flags, the active mode, and UI preferences such as popup delay and maximum number of buttons – are stored in the browser’s sync storage (chrome.storage.sync) and may sync across your devices if browser sync is enabled.

If you use the optional “Report unsupported URL” feature on the options page, the URL you manually enter is sent to our Google Form. This information is used only to debug and improve the URL parsing logic and is not linked to any other personal data.

To display site icons in the options page and mini popup UI, the extension may request favicon images from the configured sites themselves or from common favicon services (for example, Google or DuckDuckGo). These requests include only the site’s domain or URL needed to fetch the icon and are not linked to your selected text, browsing history, or identity by the extension.

2. Single Purpose of Use

Any data handled by the extension is used only for one purpose: opening the selected text on your configured search destination.  
Data is not used for advertising, profiling, analytics, or tracking.

3. Data Sharing & Sale

We do not sell or share data with third parties for advertising or marketing purposes.  
No analytics or advertising SDKs are embedded in the extension.

Google Forms and favicon services used as described above receive only the minimal information necessary to provide those specific features (URL you submit for debugging, or the site domain/URL for favicon retrieval). We do not combine this information with other data.

4. Permissions and Why We Use Them

The extension requests only the permissions needed to provide its core functionality:

- **contextMenus**:  
  Used to add a “search selected text” item to the right-click context menu when you select text.  
  Clicking this menu item is what triggers the extension to open your configured search URL in a new tab.

- **storage**:  
  Used to save your custom search engines, URL templates, enabled/disabled flags, mode, and UI preferences (such as popup delay and maximum number of buttons) in chrome.storage.sync so your settings persist and can optionally sync across devices.

- **Site access via content scripts (host permissions implied by content_scripts)**:  
  A minimal content script runs on pages where you select text in order to:
  - read only the text you have actively selected and its position on the screen, and  
  - display a small overlay (mini popup) with buttons to open your configured search engines.

  The content script does not inspect or modify the rest of the page content and does not send page contents, browsing history, or personal data to us or to any third party.

All permissions are used solely to implement this single “search selected text” feature and its mini popup UI.

5. Data Retention

Settings stored in chrome.storage.sync remain until you edit them, remove them on the options page, or uninstall the extension.  
We do not create separate user accounts or maintain external databases for this extension.

Data you submit via the optional “Report unsupported URL” form may be retained in our Google Form responses for debugging and quality-improvement purposes. You can request deletion of specific entries by contacting us (see Contact section).

6. User Controls

You can edit or remove search engines, change modes, and update popup settings at any time on the options page.  
Removing a search engine or resetting the extension’s options will delete the corresponding settings from the browser’s storage.  
Uninstalling the extension removes all of its stored settings from your browser.

You can also choose not to use the optional “Report unsupported URL” feature or disable browser sync if you do not want settings to sync across devices.

7. Contact

For questions, requests regarding this policy, or deletion of specific form submissions, please contact:  
[akvyit.dev@email.address]

8. Changes to This Policy

We may update this privacy policy from time to time.  
Material changes will be announced in the project repository or on the extension’s listing page, and the “Last updated” date will be revised accordingly.
