# WebhookMon

See, verify and replay Stripe, Polar, GitHub, Shopify and Slack webhooks on localhost, with a plain-English reason when a signature fails.

[Website](https://getwebhookmon.com) · [Help](https://getwebhookmon.com/help) · [Guides](https://getwebhookmon.com/guides/) · [Privacy](https://getwebhookmon.com/privacy) · [Changelog](https://getwebhookmon.com/changelog)

This public repository hosts issue reports, signed releases, and the Sparkle appcast. The application source is maintained in a private repository.

Requires macOS 14 or later. Install from the DMG on the [latest release](https://github.com/suresk/webhookmon/releases/latest) or with Homebrew:

```sh
brew tap suresk/tap
brew install --cask suresk/tap/webhookmon
```

Webhook payloads contain customer data and secrets. Please do not paste raw payloads, signing secrets or endpoint URLs into an issue: an endpoint URL lets anyone post to your endpoint. **Copy Summary** masks secret-looking values; check what it copied before you paste it. Security reports: support@getwebhookmon.com.
