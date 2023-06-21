From the library.custom.js, you can call
```js
window.opener.SteamUIStore.Navigate("/browser",
    window.opener.MainWindowBrowserManager.LoadURL(
        window.opener.urlStore.m_steamUrls.CommunityHome.url
    )
);
```
from a button to navigate to the community page.