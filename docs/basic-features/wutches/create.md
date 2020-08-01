# Creating a Wutch

We recommend you setting up our [Browser Extension](https://wutch.net/docs/chrome-extension) to streamline the process.

- The hardest part, find something useful for you to track
  <p className="description">You can visit our <a href="https://wutch.net/use-cases">Use Cases</a> page for some inspiration</p>
- When on the page you want to track, click the extension icon <img src="https://wutch.net/logo.png" width="16" className="inline" /> in the browser
  <p className="description">If you have some custom filtering or sorting applied on the page, for example "Newest" or "Most popular", page may or may not expose it in the address. An easy way to check that it's done is by copying complete page address and pasting it in the new Incognito Tab. If the content stays in place as on the original page, Wutch will be able to capture those filters 👌</p>
- Hover your mouse on the element containing precisely the value you want to track
  <img src="/images/docs/extension-hover.png" />
  <p className="description text-center">Here's what you'd select if you were subscribing to latest feature suggestion for Wutch</p>
- Click 🖱!
  <img src="/images/docs/new-wutch.png" />
  <p className="description text-center">It will open a new tab with a new Wutch screen, pre-configured with the page and selector you've just chosen</p>
- Adjust the Wutch name to your liking
  <p className="description">You will later see this name in change notifications to help you distinguish between the updates.</p>
- Check that URL of the page and Selector were captured correctly.
  <img src="/images/docs/wutch-config.png" />
  <p className="description text-center">In general, you won't need to make any tweaks to these values. However, if you've got hands-on Web Development experience, you may absolutely tweak these to your liking.</p>
- On the next screen, choose a Notification Channel to receive updates.
  <img src="/images/docs/wutch-channel.png" />
  <p className="description text-center">Check out our <a href="https://wutch.net/docs/basic-features/channels">Channel docs</a> for more information on creating new notification channels</p>
- Upon proceeding, Wutch will run multiple checks, trying to access the configured value. It may take a while.
  <img src="/images/docs/wutch-checks.png" />
  <p className="description">Wutch is running these tests to verify it's able to access the required value and measure the approximate time it takes to load and process the page. The smaller and leaner the page - the less time will be needed. The less time will be needed - the more Wutches could be run within your current plan limits.</p>
  <div className="pane-info">
    Checks might fail due to various reasons, starting with general network connectivity issues and ending with a full-fledged bot protection on a target website. You may learn more about that at the <b>Limitations</b> section of <a href="http://localhost:3000/docs/basic-features/wutches">Wutch docs</a>.
  </div>
- If at least some checks succeeded, you'll be able to observe extracted value(s) on the next screen
  <img src="/images/docs/wutch-scheduling.png" />
  <p className="description">If Wutch found different values when running these separate checks, for example because the values change very frequently, it'll display all the extracted values. You can also see how much on average it took Wutch to load and process the page. In general it should be on par or faster than doing it from your computer, because Wutch runs in the ☁️ clouds ☁️, right where most websites live.</p>
- Select desired check frequency and proceed with saving the Wutch
  <p className="description">Check frequency can always be tweaked later, on a Wutch Details page.</p>
  <div className="pane-info">It's by far the most important factor influencing your monthly service usage, so choose carefully.</div>
- Observe a new Wutch added to your dashboard
  <img src="/images/docs/wutch-added.png" />
  <p className="description">It will schedule the very first check as soon as possible, typically within a couple of minutes. You'll be able to observe it right in the Wutches List.</p>
