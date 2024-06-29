# Wutches

Wutches are entities devoted to visiting web pages and checking specific values on them. Each Wutch represents a single tracker for a particular website, designed to extract a specific value from it.

## Wutch Configuration

To operate, a Wutch needs to know a couple of things:
- The full address (URL) of the page, including all the complex and often unreadable parameters added by developers.
- The unique identifier (CSS Selector) of the element on the page to be checked.

Both of these can be specified either manually or with the help of our [browser extension](https://wutch.net/docs/chrome-extension). You'll need these values only for the initial configuration. After that, Wutch will continue to visit the page and check for changes automatically.

## Limitations

Wutch can access almost any site that your browser can. However, there are certain limitations:

- Wutch cannot log into websites on your behalf.
  <p className="description">However, this feature is currently under consideration and may be available in the future. You can <a href="https://shipright.community/wutch/5f1b2cbc4669139528dc53e5">track its progress</a> on our <a href="https://shipright.community/wutch">Suggestions Board</a>.</p>
- Wutch is a robot, so it won't pass "Not a Robot" tests.
  <p className="description">Challenges like ReCaptcha are, for now, beyond our capabilities.</p>
- Some websites implement bot detection mechanisms to prevent automated content extraction.
  <p className="description">This may include detecting User-Agent and browser features to prevent unauthorized use. This is a highly dynamic field, with new methods and mechanics emerging regularly. We strive to stay ahead in this game.</p>
- Some websites have a highly dynamic internal structure that changes when new content is added to the site.
  <p className="description">This can prevent Wutch from "recognizing" the element it needs to extract content from.</p>