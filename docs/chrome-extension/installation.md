# Installing Wutch Extension for Chrome

There are two ways to install Wutch Extension for Chrome: 
- [**Recommended**](#default-installation) - Install from [**Chrome Web Store**](https://chrome.google.com/webstore/detail/wutch/daepijeddhccepaahegmohekmifhnnfe)
  <p className="description">Extension will be installed in the same way as other Browser Extensions and will be automatically updated to latest stable version.</p>
- [**Manual**](#manual-installation) - Install directly from extension repository
  <p className="description">Manual installation could be used to get access to new extension features faster. It'll also require periodical <i>manual updates</i>.</p>

## Default Installation

Open the extension page in Chrome Web Store and click `Add to Chrome` in the top right corner of the page.

![Screenshot of Wutch Chrome Extension page in Chrome Web Store](/images/docs/extension-page.png)

## Manual Installation

To install extension, you'll need to download its sources from GitHub.

### Downloading Extension

Open Extension's [Releases Page](https://github.com/av/wutch-chrome-extension/releases)

![Screenshot of GitHub releases page](/images/docs/extension-releases.png)

Locate the latest release, at the "Assets" section, there will be a `.zip` archive with packaged extension. Download it.

### Unpacking Extension

After downloading, unpack it to a folder on your local machine and proceed to **chrome://extensions** in your Browser's address bar. This will open a special page in Chrome, to manage and control installed extensions.

### Enabling "Developer Mode" for Chrome Extensions

In order to manually install the extension, you'll need to have the "Developer Mode" toggle being enabled.

![Screenshot of chrome://extensions page](/images/docs/chrome-extensions.png)

### Loading Unpacked Extension

After enabling the toggle, you'll see three new controls below it. Click "Load unpacked" and locate the folder you've extracted the archive into. Choose the folder to install the extension.

### Verifying Installation

If everything is set up correctly, you should see a new item in your extensions list.

![Screenshot of installed Wutch extension](/images/docs/installed-extension.png)

You can also disable and/or remove Wutch extension from the same page once you no longer need it.
