# ChromeExtension_CrashCourse

[Chrome Extension Docs](https://developer.chrome.com/docs/extensions/mv2/getstarted)

## manifest.json
- create a manifest.json file in your root repo

```js
{
    "name":"Market Stats",
    "version":"0.0.1",
    "manifest_version":2,
    "browser_action":{
        "default_popup":"popup.html",
        "default_icon":"logo.png" // 128x128
    },
    "permissions":["activeTab"]
}


```


- create popup.html for view
- create a script file linked to popup.html

- after basic setup you can see how your extension looks
    - goto chrome - more tools - Extensions - unable developer mode
    - Load unpacked and add the files

- Once the extension is ready we can publish on google web store
    - upload chrome extension [Docs to publish](https://developer.chrome.com/docs/webstore/publish)
    - One time fees to open chrome web store developer account of $5

- Web store developer dashboard
- New Item - upload zip file

- You can also create a node server to hide the API key
- npx create-express-api .
- create upload on heroku or docker and kubernetes server
