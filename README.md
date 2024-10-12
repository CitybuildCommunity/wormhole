# c.ity.gg (wormhole)

> [!WARNING]
> work in progress

`c.ity.gg` (wormhole) is [Vercel Edge Function](https://vercel.com/docs/functions/edge-functions/quickstart) that acts as a shortcut to the [Citybuild Community wiki](https://wiki.city.build/).

## Usage

Just pass your query as the path, and you will be redirected to the most relevant page of the Citybuild Community wiki.

*examples coming soon*

## Tip

### Chrome

- Navigate to [`chrome://settings/searchEngines`](chrome://settings/searchEngines)
- Under **Site Search** select **Add**.
- Fill in the **Search Engine** as `CBWiki`. The **Shortcut** can be `cbwiki` or any alias you prefer!
- Set the **URL** to `https://c.ity.gg/%s`.
- Press **Save**.

Now, you can type `cbwiki` in Chrome's address bar, followed by whatever topic you'd like to jump to in the Citybuild Community wiki.

### Firefox

Firefox out of the box does not support adding a new search engine. However, there is an option to enable it. Here is how:

- Open a new tab and navigate to [`about:config`](about:config)
- In the search box, type `browser.urlbar.update2.engineAliasRefresh`.
- At this point, the result list should be empty.
  - If it is empty, click the **+** button at the top right.
  - If the option already exists, set it to `true` by clicking the swap button on the right.
- Now navigate to `about:preferences#search`.
- Click on the **Add** button under the “Search Shortcuts” list.
- In the popup, set the **engine URL** to `https://c.ity.gg/%s`.
- Set the alias to `cbwiki`, or anything you prefer!
- Press **Add Engine**.

Now you can type `cbwiki` followed by your search term. It will redirect you into the Citybuild Community wiki! 

🫡 May your blocks be plentiful and your creepers scarce, master architect!

## Thanks

- [`@lazd`](https://blog.lazd.net/) for [`mdn.io`](https://github.com/lazd/mdn.io), which was the inspiration for this project.
- [DuckDuckGo](https://duckduckgo.com/) for powering the search!
