# Website translator widget (a free Google Translate widget alternative)

A café page with a language menu in the corner. Pick a language and the page text is translated in place by an AI model; layout, links and images stay put. Translations are cached in the visitor's browser.

**Live demo:** https://fengyiqicoder.github.io/website-translator-widget/

The snippet is at the bottom of `index.html`. The full guide, with options: [onetagai.com/guides/translate-page](https://onetagai.com/guides/translate-page).

## One script tag instead

If your site has the old Google Translate widget code, there is a hosted version that mounts in the same `google_translate_element` div:

```html
<div id="google_translate_element"></div>
<script src="https://onetagai.com/translate.js" data-languages="es,fr,zh-CN" defer></script>
```

It needs no key to start: desktop Chrome translates on the visitor's device, other browsers open the page in Google Translate, and with a OneTag AI key every browser translates in place. Old code next to new code: [onetagai.com/google-translate-widget-alternative](https://onetagai.com/google-translate-widget-alternative).

Google's own Website Translator is only offered to academic, government, nonprofit and non-commercial sites ([Google Translate Help](https://support.google.com/translate/answer/2534559)). This snippet works on any site with a free OneTag AI key (1,000,000 tokens to start, no card): [onetagai.com](https://onetagai.com).

The key in this repo is a public demo key with a small shared quota. Use your own on your site.
