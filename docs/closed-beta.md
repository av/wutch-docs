# Closed Beta Guides

Thanks for joining a closed beta of Wutch! My biggest hope is that Wutch can be useful for you at least to some extent. If that's not the case, please feel free to shout at me via any of our [available support channels](https://wutch.net/docs/support).

To actually start using Wutch during this beta stage, there're a couple more steps need to be completed.

---

As Wutch is a product which is being in the development right now, there are a lot of areas which might not work properly or not work at all. There are also multiple implicit limitations which might render the service unavailable or inaccessible for use. Please, don't hesitate to be loud about these. Loud-speaking could be done in any of the support channels suitable for you.

---

## Complete the invitation

If you haven't yet finished setting up your Wutch account, it could be done so with:

- Open your invitation email, it should contain an invitation link
- Proceed with a link, it'll confirm your invitation request in our platform
- After request confirmed, you'll be redirected to a password configuration page
- Choose a secure password and ensure you've got it stored somewhere, as Wutch doesn't yet have a password reset flow available
- After password successfully set, you'll be redirected to a main Wutch dashboard (which will be empty, for now).

## Installing Beta Chrome Extension

Wutch extension haven't yet been approved by a Google Web Store team, so the only way to obtain it right now is manual installation. Luckily, Chrome team got us covered and it's not that hard to do:

- Download Beta Extension from its GitHub Releases
- Unpack the downloaded archive somewhere on your computer
- Go to a **chrome://extensions** address in your Chrome
- Enable the "Developer Mode" in the top right corner of the page
- Click "Load unpacked" in the Toolbar
- Select the folder with the contents of an archive you've previously unpacked
- Done!

## Creating your first Wutch

Having a Wutch account activated and Chrome extension installed, it should now be pretty easy to create your first Wutch to track something useful!

- The hardest part, find something useful for you to track
  - You can visit our [Use Cases](https://wutch.net/use-cases) page for some inspiration
- When on the page you want to track, click the extension icon in the browser
- Hover your mouse on the element containing precisely the value you want to track
- Click!
  - It should open a new tab with a new Wutch screen, pre-configured with the page and selector you've just chosen
- Adjust the Wutch name to your liking
- Apply any tweaks needed to the page URL and the chosen selector
  - If you got any hands-on Web Development experience, in most scenarios you'd be able to tweak selector in a way that would be more robust and reliable than our default algorithm. That's not required though.
- On the next screen, choose a Notification Channel to receive updates.
- Upon proceeding, Wutch will run multiple checks, trying to access the configured value
  - Checks might fail due to various reasons, starting with general network connectivity issues and ending with a full-fledged bot protection on a target website
- If at least some checks succeeded, you'll be able to observe extracted value(s) on the next screen
- Select desired check frequency and proceed with saving the Wutch
  - Check frequency can always be tweaked later, on a Wutch Details page
- Observe a new Wutch added to your dashboard
  - It should indicate scheduling of the very first check as soon as possible
  - After first check has run, you should receive a notification via chosen channel
