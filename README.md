# Chat on Page – Google Tag Manager template

Adds the [Chat on Page](https://chatonpage.com) AI support chatbot to any website that uses Google Tag Manager, without editing the site's code. The chatbot answers visitors from your own website content, with sources, and hands over to your team for live chat.

## Use

1. In Google Tag Manager, open **Templates → Tag Templates → Search Gallery** and add **Chat on Page**. (Before it is listed: **New → ⋮ → Import** and choose `template.tpl` from this repository.)
2. Create a tag with the template and enter the **public key** of your chatbot. You find it in the Chat on Page dashboard under **Plugins → Google Tag Manager**, or as `data-key` in the embed code.
3. Choose the position, language, whether the chat opens automatically and whether a greeting is shown.
4. Trigger the tag on **All Pages** (or the pages where the chat should appear) and publish the container.

Add your website's domain to the allowed domains of the chatbot in the dashboard if it differs from the site the chatbot reads.

## What the template does

It loads `https://chatonpage.com/widget.js` once per page, with the key and the options in the query string. Its permissions: injecting that script, and logging to the console in preview and debug mode only.

## License

Apache 2.0, see [LICENSE](LICENSE).
