# Simplified Chinese Extension for Flarum

This's ont part of [Flarum i18n](https://github.com/justjavac/flarum-i18n-zh)

[中文说明](README-zh_CN.md)

### Include

- [Flarum](https://github.com/flarum/core) 0.1.0-beta (Core)
- [Likes](https://github.com/flarum/likes) 0.1.0-beta
- [Lock](https://github.com/flarum/lock) 0.1.0-beta
- [Mentions](https://github.com/flarum/mentions) 0.1.0-beta
- [Pusher](https://github.com/flarum/pusher) 0.1.0-beta
- [Sticky](https://github.com/flarum/sticky) 0.1.0-beta
- [Subscriptions](https://github.com/flarum/subscriptions) 0.1.0-beta
- [Tags](https://github.com/flarum/tags) 0.1.0-beta

## Documentation

### How to download?

Click [on this link](https://github.com/Flarum-Chinese/Flarum-zh-CN/archive/master.zip) or on the **Download ZIP** button located in the right sidebar. 

### How to install?

1. Extract the archive you just downloaded.

2. Using [FTP](http://en.wikipedia.org/wiki/File_Transfer_Protocol), browse into your Flarum root (which contains the *config.php* file). You will see an **extensions/** directory. 

3. Inside this directory, create a **zh-CN/** directory. 

4. Upload the content of the previous extracted archive inside the **zh-CN/** directory.

The extension is now uploaded to your server and your next step is to enable it. Log-in to your forum and click on your username located at the top right of the screen. You will see a pop-up. Click on the **Administration** link. Once in the administration page, click on **Extensions**. You will see a list of all your extensions. Note that the Simplified Chinese extension is the grey tinted one, with a white icon of the Earth and a blue background. Hover the extension and notice the dotted vertical menu. Click on that vertical menu and click on **Enable**.

Your extension is now enabled. Congratulations! You, and your users, can now select the language via a dropdown menu located in the header, at the right of the search box.

Your extension files are now installed, but you have to force the cache of your forum to refresh. To do that, using [FTP](http://en.wikipedia.org/wiki/File_Transfer_Protocol), locate the **assets/** directory. Inside the directory, delete the **forum-zh-CN-\*.js** and **admin-zh-CN-\*.js** files. You can now enjoy the latest improvements and fixes of the updated extension!

### License

Released under the MIT License. Please see the [LICENSE](LICENSE) file.
