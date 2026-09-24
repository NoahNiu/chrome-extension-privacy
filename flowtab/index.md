# FlowTab Privacy Policy

**Effective date:** September 24, 2026 (FlowTab 1.0)

FlowTab is a Chrome extension that replaces the new tab page with a full-screen wallpaper, a greeting, a clock, a search box and a short row of website shortcuts. It works entirely on your device.

## Data stored locally

FlowTab saves only the preferences you set yourself: the wallpaper you chose, a picture you uploaded or imported, the name shown in the greeting, the greeting language, the clock size, display options and your website shortcuts. They are stored in Chrome's local storage on your device (`chrome.storage.local`), with a small display cache in the extension page's local storage so the page paints quickly.

FlowTab uses this information only to show your new tab page. It is never sent to the developer or to any other party.

You can remove an uploaded picture at any time in the settings panel. Removing the extension from Chrome deletes all of FlowTab's stored data.

## Records from earlier versions

FlowTab 0.x could store notes, todos, ideas, saved links and similar content. FlowTab 1.0 no longer displays these, but it does not delete them either: they stay in your browser's local storage, and FlowTab offers to export them to a file on your own computer. The export happens locally; nothing is uploaded.

## Network requests

FlowTab has no backend server, no account and no remote code. Its scripts, fonts and built-in wallpapers are bundled with the extension, and it works offline.

- **Search:** text you type in the search box is handed to Chrome's own default search engine through the `chrome.search` API. FlowTab does not read, store or send your queries anywhere. The search engine you chose in Chrome handles them under its own privacy policy.
- **Pictures from websites:** only when you paste the address of a picture and choose to use it, FlowTab downloads that single image and saves it locally. For sites other than Unsplash's image service (`images.unsplash.com`), Chrome first asks for your permission to access that site. No other data is sent with the request.
- **Shortcuts and links:** when you open a shortcut or a link, Chrome navigates to that website, which handles your visit under its own privacy policy.

## Permissions

- `storage`: saves your preferences and pictures locally.
- `search`: runs searches with the default search engine you chose in Chrome.
- Optional access to websites: requested only at the moment you import a picture from a particular site.

## Data sharing and sale

FlowTab does not collect, sell, rent, share or transfer personal data. It does not use advertising, analytics, tracking pixels or affiliate tracking.

## Changes

If this policy changes materially, the updated policy will be published at this same address with a new effective date.

## Contact

For questions or support, open an issue at
https://github.com/NoahNiu/chrome-extension-privacy/issues

---

## 中文摘要

FlowTab 只在你的电脑上保存你自己设置的内容（壁纸、上传或导入的图片、问候中的名字和语言、时钟大小、显示选项、快捷入口），不会发送给开发者或任何第三方，也不做统计、广告或追踪。

搜索框的内容交给你在 Chrome 中设置的默认搜索引擎处理，FlowTab 不读取也不保存。只有在你主动粘贴网上图片地址时，FlowTab 才会下载那一张图片并保存在本地；访问 Unsplash 图片服务以外的网站前，Chrome 会先征求你的同意。

旧版（0.x）的便签、待办等记录不会被删除，可以在新版中导出到你自己的电脑。卸载扩展会删除 FlowTab 保存的全部数据。
