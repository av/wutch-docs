# Wutches

Wutches are fiends devoted to visiting web pages and checking certain values on them. Each Wutch represents a single check for certain website, running to extract a specific value from it. 

## Configuring a Wutch
To operate, Wutch needs to know a couple of things:
- the full address (URL) of the page, including all the nitty-gritty unreadable tails put there by developers
- the special handle (CSS Selector) of the element on the page to check

Both of these could be specified either manually, or with the help of Wutch browser extension for Chrome. You'll need these values only for the initial setup, all the forthcoming checks will just use what was set during the configuration.