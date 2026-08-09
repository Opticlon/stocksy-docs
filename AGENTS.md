# Documentation project instructions

## About this project

- This is the documentation site for **Stocksy: Back in Stock**, a Shopify app by Opticlon
- Built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Style reference: [Iconic Frequently Bought docs](https://frequently-bought-docs.geticonicapps.com/get-started/introduction)

## Terminology

- Use **Stocksy** or **Stocksy: Back in Stock** for the app name
- Use **App Embed** for the theme extension that must be enabled
- Use **subscriber** for a customer waiting for a stock/price/coming-soon alert
- Use **notification** for emails sent when a product is back in stock or a price drops
- Use **widget** for the storefront signup form
- Widget types: **Back in stock**, **Price drop alert**, **Coming soon waitlist**
- **Coming soon waitlist** is paid plans only — never document it as available on the free plan
- Coming soon requires product selection; show widget when inventory is 0; hide widget on storefront when in stock — do not describe this as "automatic"
- Notifications currently support **Email** only; email templates cover all 3 widgets with content + style (colors, font, radius, padding)
- Plans: Free $0 (100), Starter $9.99 (1,000), Growth $19.99 (3,000), Pro $49.99 (10,000); wallet $1/100 emails after quota (not on Free)
- Custom branded email domain is a Pro feature marked Coming soon in the app; Advanced custom support is future-only
- Use **Notification Wallet** for prepaid email credits after the monthly quota
- Support email: `support@opticlon.com`

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Match the Iconic docs tone: clear product overview, then section-by-section UI explanations
- Do not add screenshots or images in docs pages unless the user explicitly asks

## Content boundaries

- Document merchant-facing app features only
- Do not document internal admin tooling or unpublished APIs
- Prefer documenting what merchants see in the Shopify admin app UI
