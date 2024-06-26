# KISS Translator

A simple, open source [bilingual translation extension & Greasemonkey script](https://github.com/fishjar/kiss-translator).

[kiss-translator.webm](https://github.com/fishjar/kiss-translator/assets/1157624/f7ba8a5c-e4a8-4d5a-823a-5c5c67a0a47f)

## Features

- [x] Keep it simple, smart
- [x] Open source
- [x] Adapt to common browsers
  - [x] Chrome/Edge/Firefox/Kiwi/Orion
  - [ ] Safari
- [x] Supports multiple translation services
  - [x] Google/Microsoft/DeepL/NiuTrans/OpenAI/Gemini/CloudflareAI/Baidu/Tencent
  - [x] Custom translation interface
- [x] Covers common translation scenarios
  - [x] Web bilingual translation
  - [x] Input box translation
  - [x] Seletction translation
    - [x] Favorite Words
  - [x] Mouseover translation
  - [x] YouTube subtitle translation
- [x] Cross-client data synchronization
  - [x] KISS-Worker（cloudflare/docker）
  - [x] WebDAV
- [x] Custom translation rules
  - [x] Rule subscription/rule sharing
  - [x] Customized terminology
- [x] Custom translation style
- [x] Custom shortcut keys
  - `Alt+Q` Toggle Translation
  - `Alt+C` Toggle Styles
  - `Alt+K` Open Setting Popup
  - `Alt+S` Open Translate Popup / Translate Selected Text
  - `Alt+O` Open Options Page
  - `Alt+I` Input Box Translation

## Install

> Note: For the following reasons, it is recommended to use browser extensions first
>
> - Browser extensions have more complete functions (local language recognition, context menu, etc.)
> - Grease Monkey script will encounter more usage problems (cross domain issues, script conflicts, etc.)

- [x] Browser extension
  - [x] Chrome [Installation address](https://chrome.google.com/webstore/detail/kiss-translator/bdiifdefkgmcblbcghdlonllpjhhjgof?hl=zh-CN)
    - [x] Kiwi (Android)
    - [x] Orion (iOS)
  - [x] Edge [Installation address](https://microsoftedge.microsoft.com/addons/detail/%E7%AE%80%E7%BA%A6%E7%BF%BB%E8%AF%91/jemckldkclkinpjighnoilpbldbdmmlh?hl=zh-CN)
  - [x] Firefox [Installation address](https://addons.mozilla.org/zh-CN/firefox/addon/kiss-translator/)
  - [ ] Safari
- [x] GreaseMonkey Script
  - [x] Chrome/Edge/Firefox ([Tampermonkey](https://www.tampermonkey.net/)/[Violentmonkey](https://violentmonkey.github.io/)) [Installation link](https://fishjar.github.io/kiss-translator/kiss-translator.user.js)
    - [Greasy Fork](https://greasyfork.org/zh-CN/scripts/472840-kiss-translator)
  - [x] iOS Safari ([Userscripts Safari](https://github.com/quoid/userscripts)) [Installation link](https://fishjar.github.io/kiss-translator/kiss-translator-ios-safari.user.js)

## Associated Projects

- Data synchronization service: [https://github.com/fishjar/kiss-worker](https://github.com/fishjar/kiss-worker)
  - Data synchronization service available for this project.
  - Can also be used to share personal private rule lists.
  - Deploy by yourself, manage by yourself, data is private.
- Community subscription rules: [https://github.com/fishjar/kiss-rules](https://github.com/fishjar/kiss-rules)
  - Provides the latest and most complete list of subscription rules maintained by the community.
  - Help with rules-related issues.
- Translation interface agent: [https://github.com/fishjar/kiss-proxy](https://github.com/fishjar/kiss-proxy)
  - If you encounter network problems when accessing a certain translation interface, this proxy service may help you.
  - Deploy and manage by yourself.
- Minimalistic Dictionary Plugin: [https://github.com/fishjar/kiss-dictionary](https://github.com/fishjar/kiss-dictionary)
  - A word-marking translation plug-in used with this project.
  - Supports query of English words, sentences and Chinese characters.
  - Supports history records and word collections.

## Development Guidelines

```sh
git clone https://github.com/fishjar/kiss-translator.git
cd kiss-translator
pnpm install
pnpm build
```

## Discussion

- Join [Telegram Group](https://t.me/+RRCu_4oNwrM2NmFl)

## Appreciate

![appreciate](https://github.com/fishjar/kiss-translator/assets/1157624/ebaecabe-2934-4172-8085-af236f5ee399)
