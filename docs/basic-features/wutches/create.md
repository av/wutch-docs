# Creating a Wutch

We recommend you setting up our [Browser Extension](https://wutch.net/docs/chrome-extension) to streamline the process.

<div className="pane-info text-center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/RX702Qfhm4s" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  <p className="description">Same procedure as described below, but as a no-comment video.</p>
</div>

- The hardest part: finding something useful for you to track.
  <p className="description">Visit our <a href="https://wutch.net/use-cases">Use Cases</a> page for some inspiration.</p>
- When on the page you want to track, click the extension icon <img src="https://wutch.net/logo.png" width="16" className="inline" /> in the browser.
  <p className="description">If you have applied custom filtering or sorting on the page, such as "Newest" or "Most popular", the page may or may not reflect it in the address. An easy way to verify this is by copying the complete page address and pasting it into a new Incognito Tab. If the content remains the same as on the original page, Wutch will be able to capture those filters 👌.</p>
- Hover your mouse over the element containing precisely the value you want to track.
  <img src="/images/docs/extension-hover.png" />
  <p className="description text-center">This is what you would select if you were subscribing to the latest feature suggestion for Wutch.</p>
- Click 🖱!
  <img src="/images/docs/new-wutch.png" />
  <p className="description text-center">This action will open a new tab with a new Wutch screen, pre-configured with the page and selector you've just chosen.</p>
- Adjust the Wutch name to your liking.
  <p className="description">You will later see this name in change notifications to help you distinguish between the updates.</p>
- Verify that the URL of the page and the Selector were captured correctly.
  <img src="/images/docs/wutch-config.png" />
  <p className="description text-center">Generally, you won't need to make any adjustments to these values. However, if you have hands-on web development experience, you may certainly tweak these to your preference.</p>
- On the next screen, choose a Notification Channel to receive updates.
  <img src="/images/docs/wutch-channel.png" />
  <p className="description text-center">Check out our <a href="https://wutch.net/docs/basic-features/channels">Channel docs</a> for more information on creating new notification channels.</p>
- Upon proceeding, Wutch will run multiple checks, attempting to access the configured value. This process may take some time.
  <img src="/images/docs/wutch-checks.png" />
  <p className="description">Wutch runs these tests to verify it can access the required value and to measure the approximate time it takes to load and process the page. The smaller and leaner the page, the less time will be needed. The less time required, the more Wutches could be run within your current plan limits.</p>
  <div className="pane-info">
    Checks might fail due to various reasons, ranging from general network connectivity issues to full-fledged bot protection on the target website. You can learn more about these limitations in the <b>Limitations</b> section of the <a href="http://localhost:3000/docs/basic-features/wutches">Wutch docs</a>.
  </div>
- If at least some checks succeed, you'll be able to observe the extracted value(s) on the next screen.
  <img src="/images/docs/wutch-scheduling.png" />
  <p className="description">If Wutch finds different values during these separate checks, for example, because the values change very frequently, it will display all the extracted values. You can also see how much time on average it took Wutch to load and process the page. In general, it should be on par or faster than doing it from your computer, because Wutch runs in the ☁️ clouds ☁️, right where most websites live.</p>
- Select desired check frequency and proceed with saving the Wutch
  <p className="description">Check frequency can always be tweaked later, on a Wutch Details page.</p>
  <div className="pane-info">It's by far the most important factor influencing your monthly service usage, so choose carefully.</div>
- Observe a new Wutch added to your dashboard
  <img src="/images/docs/wutch-added.png" />
  <p className="description">It will schedule the very first check as soon as possible, typically within a couple of minutes. You'll be able to observe it right in the Wutches List.</p>
