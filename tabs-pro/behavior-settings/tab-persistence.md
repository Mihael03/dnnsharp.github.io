# Tab Persistence

![](/tabs-pro/assets/persist.jpg)

### Summary

* Without using the persistence options, the current tab is lost when the page is refreshed or the user navigates away from the page
* Persist on Postback ensures that the current tab sticks after a post. Almost always you'll want this option turned on
* Persist in URL to make sure that the browser address bar reflects the current tab. Sharing this URL will open the page with same tab open
* Persist in URL is also useful for navigation with browser Back and Forward buttons
* Persist in Cookies to remember the most recent open tab when the user comes back to the page at a later time
* Persistence does not work for the inner accordion generated by the "Display modules in accordion" setting
* Persistence does not work with nested Tabs Pro modules

Often, interacting with a Tabs Module means more than hiding a tab and showing another in terms of making a smooth user experience. You will want control over how the system remembers the last open tab so the Tabs Module doesn't become that annoying module you can't drop yet.

Starting with the Tabs Pro 1.8 we've added the option to auto scroll to active tab when opening a bookmarked link.

### So what's Tab Persistence all about ?

Tab Persistence refers to the ability to save the last opened tab between page visits. Note that this also happens on Post Backs \(when the web page reloads from server as a result of an action\).

Tabs Pro comes with 3 persistence options. Note that options below are not exclusive, they each solve a specific problem. Persistence can be configured from Manage Tabs screen.

### Persist on Postback

This option is enabled by default because users expect the same tab to remain opened after they triggered an event that causes the page to submit data to the server. When this option is enabled, and you're showing modules within a tab that postback, then on refresh, the previously activated tab will be displayed after the page reloads.![](/tabs-pro/assets/postback.jpg)

### Persist in URL Bookmark

This option saves the current tab in URL which will look like this: site.com/Page.aspx\#tab123. This is a very good option when sharing is needed so someone can copy the URL from the Address Bar and send it to someone else who will see the same thing - an url part in the extension of the link which reflects the tabs the user is on. When the user activates a tab and refreshes the page, after the page loads, the previously accessed tab will be displayed on the page and the URL extension will be the same.

### Persist in Browser Cookies

This will save the active tab in browser cookies. The cookies are set to expire after a year, so unless manually cleared by the user, Tabs Pro will automatically display the last active tab when the user returns to the page \(let's say that the user activated a third tab on his page - the current position is persisted in the cookies, and afterward the user navigates to other external web page, when he later comes back to the site, he should be able to see the last opened tab\).

**Note**: Persistence doesn't work for the inner accordion generated by the "Display modules in accordion" setting and neither for the nested Tabs Pro modules



