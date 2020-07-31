# Wutches

Wutches are fiends devoted to visiting web pages and checking certain values on them. Each Wutch represents a single tracker for certain website, running to extract a specific value from it.

## Wutch Configuration

To operate, Wutch needs to know a couple of things:
- the full address (URL) of the page, including all the nitty-gritty unreadable tails put there by developers
- the special handle (CSS Selector) of the element on the page to check

Both of these could be specified either manually, or with the help of our [browser extension](https://wutch.net/docs/chrome-extension). You'll need these values only for the initial configuration, and then Wutch will just proceed endlessly visiting the page, checking for changes.

## Limitations 

Wutch can go almost anywhere your browser can. There're, however, certain limitations:

- Wutch can not log in to websites on your behalf
  <p className="description">However, this feature is under consideration right now and may be available in future. You could <a href="https://shipright.community/wutch/5f1b2cbc4669139528dc53e5">track it</a> on our <a href="https://shipright.community/wutch">Suggestions Board.</a></p>
- Wutch is a robot, so it won't pass "Not a Robot" tests
  <p className="description">Things like ReCaptcha and alike are out of our reach, for now.</p>
- Some websites implement bot detection mechanisms to prevent automated content extraction
  <p className="description">This may include User-Agent and Browser features detection to prevent unauthorized use. This is a highly dynamic field with new methods and mechanics emerging on a regular basis. We do our best to keep up with the game.</p>
- Some websites have highly dynamic internal structure, which changes when new content added to the site
  <p className="description">This may prevent Wutch from "recognizing" the element it should use to extract content from.</p>

