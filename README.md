# Sky.app

A lightweight wrapper around Bluesky ([staging.bsky.app](https://staging.bsky.app/)) on MacOS.

It has some neat features like keyboard shortcuts, Dark Mode Sync️, and notification badges.

## Installation

* DIY way: Clone the repo and build in XCode
* Easy way: Download the DMG from the [Releases](https://github.com/jcsalterego/Sky/releases) page.

## Keyboard Shortcuts

### Posting

* `⌘-N` New Post

### Navigation

* `⌘-⇧-R` Refresh
* `⌘-⇧-]` Next Tab (or `^-Tab`)
* `⌘-⇧-[` Previous Tab (or `^-⇧-Tab`)
* `⌘-1` Home
* `⌘-2` Search (also `⌘-k`)
* `⌘-3` Notifications
* `⌘-4` Profile

### Other

* `⌘-T` Open in Browser
* `⌘-⇧-C` Copy Current URL

## Screenshot

![](docs/screenshot.png)

## Credits

App icon based on the [work](https://unsplash.com/photos/KVVpx8M10OY) of Carmine Savarese.

## Changelog

### 0.0.9

* Fix Tab navigation in Dark Mode
* `Advanced > Developer Console`

### 0.0.8

* Using `⌘-1` for Home while you're already on the page will click the
  "Load More Posts" button. Same for Notifications.
* Navigate inner tabs (Following, What's New):
  * Previous Tab: `⌘-⇧-[` or `^-⇧-Tab`
  * Next Tab: `⌘-⇧-]` or `^-Tab`
* Bonus key binding: `⌘-k` goes to Search
* `Advanced > Search Posts By Newest First` will reorder searched posts in reverse chronological order.

### 0.0.7

* FIX: Restore Dark Mode sync scrollbars. Whoops.

### 0.0.6

* Notification badges! It might be a little wonky. One can always issue a Refresh (⌘-⇧-R).
* FIX: Dark Mode sync got outta whack. It is in whack now.
* FIX: Search page is scrollable now.

### 0.0.5

* ⌘-⇧-C to copy the current URL (#1)

### 0.0.4

* Open in Browser

### 0.0.3

* Full Light/Dark Mode sync (scrollbars included)

### 0.0.2

* Title bar follows dark mode
* FIX: Remove outer scrollbars

### 0.0.1

* Initial release

## LICENSE

[2-Clause BSD](LICENSE)
