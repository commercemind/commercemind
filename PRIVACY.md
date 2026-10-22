# CommerceMind Privacy Policy

**Effective:** 22 October 2026 · **Last updated:** 22 October 2026

This policy explains what personal data CommerceMind handles and why, for our Adobe Commerce and Magento Open
Source extensions - including **AI Content Generator** - our Adobe Commerce Marketplace listings, and our support.

### In short

- Our extensions run on your own store. They send nothing to CommerceMind - no tracking, analytics or license checks.
- AI Content Generator sends catalog and page content to the AI provider *you* choose, directly from your server,
  with your own API key. It never sends customer or order data.
- We only receive personal data that you send us, for example in a support email, or that Adobe shares with us when
  you buy an extension.
- We don't sell personal data and don't use it for advertising.

## 1. What the extension processes

Our extensions are installed on, and run entirely within, your own Adobe Commerce or Magento Open Source
installation. They have no connection to CommerceMind: they do not send us usage statistics, store details, license
checks or any other data, and they set no cookies on your storefront.

When you run a store, you are responsible for the personal data in it. Our extensions process that data only as
described below and only when an admin uses them.

## 2. Data sent to AI providers

AI Content Generator writes content and creates images by calling the AI provider that the store admin selects in
the configuration - OpenAI, Anthropic or Groq. Requests go **directly from your server to that provider**,
authenticated with **your own API key**. CommerceMind never receives them.

| Request | Data sent |
|---|---|
| Product text | Name, SKU, product type, category names, storefront-visible attribute values and the current description and meta fields. |
| Category text | Name, parent category names, product count, example product names and the current description and meta fields. |
| CMS page or block | Title, URL key or identifier and the current content. |
| Product images | Product name, the admin's prompt, the short description or description, and - when "Product photo" is chosen - the product's main image file. |
| All requests | Any extra instructions typed by the admin and the brand voice text from the configuration. |

No customer, order or payment data is sent. Avoid typing personal data into the extra instructions or prompts.

The provider handles this data under its own terms and privacy policy, which you accept when you create your API
key: [OpenAI](https://openai.com/policies/privacy-policy/), [Anthropic](https://www.anthropic.com/legal/privacy),
[Groq](https://groq.com/privacy-policy/). Please review them before enabling a provider.

## 3. Data kept in your store

The extension stores the following in your own database and media folder. It stays under your control and is never
sent to us.

- **Generation jobs:** the record each job is for, the generated content, the options used, token counts, status,
  dates and the ID of the admin user who started the job.
- **API keys:** stored encrypted in the store configuration and sent only to the provider they belong to.
- **Generated images:** kept in `pub/media/commercemind_ai/generated/` until they are reviewed. Files of discarded,
  failed and deleted jobs are removed automatically, and those of applied jobs after 14 days.
- **Error log:** provider error messages in `var/log/commercemind_ai_content_generator.log`.

You can delete jobs at any time in the Generation Queue. Uninstalling the extension and removing its database table
deletes the rest; the user guide describes how.

## 4. Purchases through Adobe

Our extensions are sold through the Adobe Commerce Marketplace. Adobe processes your account, order and payment under
the [Adobe Privacy Policy](https://www.adobe.com/privacy/policy.html); we never receive your payment details. Adobe
may share order information with us, such as your name, company and email address. We use it only to provide the
extension and support, and to meet legal and accounting obligations.

## 5. Support requests

When you email us, we receive your name, email address and whatever you include in your message and attachments, such
as version numbers and log extracts. We use this only to answer you and to fix problems in our extensions.

Please don't send API keys, passwords, or customer data from your store. If a log extract contains personal data,
remove it before sending.

## 6. How we use and share data

We use personal data only for the purposes above: to provide our extensions, answer support requests and meet legal
obligations. We rely on the performance of our agreement with you and on our legitimate interest in supporting our
products.

We don't sell personal data, don't use it for advertising, and don't share it with third parties, except with the
email service we use to receive and answer messages, or when the law requires us to.

## 7. Security and retention

We keep the personal data we hold to a minimum and protect access to it. We keep support correspondence for as long as
needed to resolve your request and for up to two years afterwards for future support, unless you ask us to delete it
sooner or the law requires us to keep it longer.

## 8. Your rights

Depending on where you live, you can ask us to access, correct, delete or export the personal data we hold about you,
or object to or restrict how we use it. Email us and we will reply within 30 days. You can also complain to your local
data protection authority.

For personal data in your own store, including anything sent to an AI provider, contact the store owner or the
provider concerned, since they control that data.

## 9. Children

Our extensions and services are intended for businesses and are not directed at children under 16. We don't knowingly
collect their personal data.

## 10. Changes to this policy

We may update this policy when our extensions or legal requirements change. We will change the date at the top of this
page, and describe significant changes in the release notes of the affected extension.

## 11. Contact us

Questions or requests about this policy or your personal data: **anju0987singh@gmail.com**

---

CommerceMind · Extensions for Adobe Commerce and Magento Open Source
