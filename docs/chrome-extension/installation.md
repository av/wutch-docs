# Installing Wutch Extension for Chrome

Wutch requires one pretty technical pointer to operate - a precise handle of an element for the target page. Because not everybody have hands-on experience with Web Development, we're shipping an extension for Chrome Browser to simplify this procedure.

All in all, extension's purpose is very simple: capture the page you want to track and the element you'll point on it. 

However, you'll still need to put it right inside of your browser. So, to provide better transparency, we're distributing this extension as an Open Source Software. In addition to transparency, it makes it possible for anybody to inspect and verify this extension's source code. So, overall it's easy to ensure that it does only what it's supposed to do and no shady business going on.

## Installation

As for the moment, Wutch Browser extension is not yet available in Chrome Web Store. So the only way to install it is via manual installation.

## Manual Installation

Open Extension's Releases Page

![Screenshot of GitHub releases page](/images/docs/extension-releases.png)

Locate the latest release, at the "Assets" section, there will be a `.zip` archive with packaged extension. Download it.

After downloading, unpack it to a folder on your local machine and proceed to **chrome://extensions** in your Browser's address bar. This will open a special page in Chrome, to manage and control installed extensions.

In order to manually install the extension, you'll need to have the "Developer Mode" toggle being enabled.

![Screenshot of chrome://extensions page](/images/docs/chrome-extensions.png)

After enabling the toggle, you'll see three new controls below it. Click "Load unpacked" and locate the folder you've extracted the archive into. Choose the folder to install the extension.

If everything is set up correctly, you should see a new item in your extensions list.

![Screenshot of installed Wutch extension](/images/docs/installed-extension.png)

You can also disable and/or remove Wutch extension from the same page once you no longer need it.
