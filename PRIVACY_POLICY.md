# Privacy Policy

**Effective date:** October 24, 2026

This Privacy Policy explains what **NamelessNanashi** ("we," "us," "our") does with the information you share when buying from us, including through our online store at [pay.namelessnanashi.dev](https://pay.namelessnanashi.dev), getting support, or contacting us. Physical orders are US-only; coding, consulting, and other remotely delivered services are available internationally, where legally permitted. All customers must be at least 18 and meet the age requirement in our [Terms of Service](TERMS_OF_SERVICE.md).

**We never sell user data for any reason. We do not conduct advertising or marketing, send marketing emails, or share user data for advertising or marketing purposes.**

## 1. Information We Collect

Depending on your order and how you contact us, we may receive:

- **Contact information:** your name, email address, shipping and billing addresses, phone number, and Discord username or user ID.
- **Order and transaction information:** quotes, items purchased, invoices, payment status, transaction references, and refund or dispute records.
- **Communications and project materials:** Discord messages, emails, support requests, files, code, specifications, photographs, videos (including proof of approved hardware destruction for an exchange), and other information you send us.
- **Online store checkout information:** when you buy through our online store, Stripe collects your name, email address, shipping address, billing address, and optional company name. After your payment succeeds, our server retrieves these details from Stripe along with Stripe Radar fraud-check results (such as risk level, risk score, and whether the card security code (CVC) and postal code checks passed). If you use a promotion code with a per-person limit, our site asks for your email address before Stripe's payment form and passes it to Stripe. The store checkout does not ask for your phone number. Your full card number, expiration date, and security code are entered only into Stripe's payment form; they are never sent to or stored by us. Stripe keeps your payment-card information under its own policy, and Stripe's records available to us may show limited card details, such as card brand and last four digits.
- **Fulfillment information:** fulfillment status and history, and shipment tracking information we add to your order.
- **Website technical information:** when you visit our online store, your IP address and request information (such as the page requested, browser type, and time of the request) are processed by Cloudflare and our server, as described in Sections 2 and 5.

Please send only information needed for your order or request. Do not send passwords, private keys, full payment-card details, or unrelated sensitive information through Discord or email.

## 2. Where Information Is Stored

Customer information and business records are stored through **Stripe, Discord, email, and our own order server**:

- **Stripe** processes payments and holds payment and transaction records. Payment details you submit to Stripe are handled by Stripe; we receive the transaction and customer information available to us for managing your order. Card details entered in the online store's payment form are sent only to Stripe, not to our server.
- **Discord** holds messages and files exchanged with us through Discord. When an online store order is paid, our private store-management bot also sends us a private Discord direct message containing your name, email address, phone number (if one was provided), shipping address, items, totals, and a fraud-check summary, so Discord stores those order details as part of our messages.
- **Email** holds correspondence, attachments, and order or support records sent or received by email.
- **Our order server** is a server we operate ourselves in the United States. It stores records of paid online store orders: the customer details listed in Section 1 (contact and address details are encrypted at rest in its database), items, amounts, payment status, fraud-check results, fulfillment status and history, and shipment tracking information. It does not store payment-card details, such as card numbers, expiration dates, security codes, card brands, or the last four digits of cards. If a checkout is started but not paid, the server keeps a reservation record of the items and related timestamps; that record contains no contact or address information, except the per-person promotion code email described next. When a per-person promotion code is used, the server stores the email you entered on our site, encrypted, including for checkouts that are started but never paid. For each use of that code, it also stores keyed one-way hashes of your normalized email address and shipping address to enforce the code's limits. These hashes are not sent to anyone.

We also use this service provider for the online store:

- **Cloudflare** provides DNS and network services for our website. All website traffic passes through Cloudflare, which processes visitors' IP addresses and request information to deliver the site and protect it from abuse, including through its bot-detection checks. We also use Cloudflare Web Analytics to understand website traffic. We do not use Cloudflare for advertising.

These providers operate their own systems and may collect technical information, such as device, connection, or usage information, when you use their services. Their own processing is subject to their policies. See the [Stripe Privacy Policy](https://stripe.com/privacy), [Discord Privacy Policy](https://discord.com/privacy), [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/), and [Pirate Ship Privacy Policy](https://www.pirateship.com/privacy). Email providers also apply their own policies to the messages they handle.

Using these services does not authorize us to sell your data or use it for marketing.

## 3. How We Use Information

We use personal information to:

- Prepare quotes, process payments, fulfill orders, and handle cancellations, returns, and refunds.
- Perform agreed custom work, repairs, and other services.
- Answer questions and provide technical or order support.
- Review photos or videos to assess faults and verify an approved exchange, including any agreed destruction of the faulty hardware.
- Send order confirmations, shipping updates, safety notices, and other messages related to your purchase or request.
- Maintain business records, address fraud or security issues, comply with legal obligations, and resolve disputes.
- Operate and protect our online store, including reserving items during checkout, limiting excessive or abusive requests, and reviewing fraud-check results before shipping.
- Enforce promotion code limits, including per-person limits, and review orders that exceed them.

We do not use personal information to send marketing emails, target advertisements, or build marketing profiles.

## 4. When We Share Information

We never sell user data for money or anything else of value. We do not share it for marketing or targeted advertising, including advertising based on your activity across different websites or apps.

Sometimes we need to share information to complete your order or meet our responsibilities. This may include:

- **Stripe, Discord, and email providers** to process transactions, communicate with you, and maintain the records described above.
- **Cloudflare** to deliver and protect our website, as described in Section 2.
- **Shipping carriers, Pirate Ship, and contractors** to deliver your order or perform agreed work. For shipped orders, we enter your shipping name and address into Pirate Ship to buy postage labels, and Pirate Ship provides them to the carrier (such as USPS).
- **Professional advisors** who need it for accounting, legal advice, or related business obligations.
- **Authorities or parties to a legal matter** when required by law, to respond to lawful requests, or as reasonably necessary to address fraud, safety, security, or legal claims.

We limit disclosures to information needed for the relevant purpose. Providers may also have independent legal obligations and privacy practices.

That promise also applies if the business is sold: user data will not be an asset we sell.

## 5. Cookies, Browser Storage, and Provider Settings

We do not use advertising or marketing cookies or tracking technologies. Stripe and Discord may use cookies or similar technologies as part of their own services. Their policies and account settings explain their practices and available choices.

### Online Store

Our online store uses only the following cookie and browser storage items. They are strictly functional: they are needed for checkout to work, and none is used for advertising, analytics profiling, or tracking you across other websites.

- **`nnos_shopper` cookie:** a random identifier that lets our checkout recognize a cart your browser has already reserved, so unfinished checkouts don't pile up and hold stock. If you start a new checkout while an earlier one is still open, you'll be asked to resume or release it first. It does not limit how many orders you can place or how much you can buy: once a reserved cart is paid, released, or expires, you can start another checkout right away. It is sent only to our checkout service, cannot be read by page scripts, is sent only over secure connections and only from our own site, and lasts 30 days. Our server stores only a keyed hash of it, not the identifier itself.
- **`nnos_open_checkout` (browser local storage):** your currently reserved cart (items, a random checkout ID, and an expiry time), so you can resume or release it. It is removed when the order is paid, the cart is released, or the reservation expires (about 35 minutes).
- **Order-status token (browser session storage):** a token used to show your order's status after payment. Your browser clears session storage when you close the tab or window.
- **Stripe cookies:** Stripe sets its own cookies inside its payment form, under its own policy.

Our website also permits Cloudflare's bot-detection checks (which may run scripts or show a challenge in your browser) and Cloudflare Web Analytics scripts. These are used to protect the site and understand website traffic, not for advertising. See the [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/) for Cloudflare's practices.

Our server uses your IP address to limit excessive or abusive requests. It stores only a keyed, irreversible hash of your IP address, not the address itself, and deletes those records once the rate-limit period ends.

Browser settings may let you block or remove cookies and browser storage, but doing so can affect checkout, payment, or communication features. Our no-advertising commitment describes our activities; it is not a claim that independent platforms never conduct their own advertising.

## 6. How Long We Keep Information

**We retain customer communications and voluntarily provided materials indefinitely through Stripe, Discord, email, and other channels where you submit information.** This includes emails, Discord messages, support conversations, code, files, schematics, specifications, photographs, videos, attachments, project materials, and similar materials you supply for an order, project, warranty claim, or support request.

We also retain ordinary business records—including orders, transactions, payment and refund records, accounting and tax records, warranty records, fraud and security records, and dispute records—for as long as reasonably necessary for business, legal, accounting, tax, fraud prevention, security, warranty administration, recordkeeping, or dispute-resolution purposes. Online store order records on our order server, and the order notifications in our Discord messages, are business records kept under this paragraph. The hashed email and shipping-address records for per-person promotion codes are kept with the order records for as long as the code and its records are kept, for fraud prevention and limit enforcement.

The law and our providers' storage and deletion controls still apply. Providers such as Stripe, Discord, and email providers may delete information according to their own systems and policies. We cannot guarantee that every record will be retained forever, and some information may remain in backups, logs, archives, or third-party provider systems even after we delete copies under our control.

You can contact us to ask for deletion of information you previously provided. We'll delete information we are reasonably able to delete from systems under our control when retention is not still reasonably necessary.

Deletion may be limited when information must or reasonably should be retained for reasons such as legal obligations, tax or accounting records, transaction records, active or possible disputes, fraud prevention, security, warranty administration, legal claims, or other legitimate recordkeeping needs. Full deletion may not always be technically possible because information may remain in backups, logs, archives, third-party provider systems (including those of Stripe, Discord, email providers, Cloudflare, Pirate Ship, shipping providers, and other service providers), or records independently controlled by those providers.

## 7. Security

We use reasonable safeguards for the accounts and information under our control and rely on our providers for the security of their systems. For our online store, these safeguards include sending card details only to Stripe, encrypting customer contact and address details at rest in our order server's database, storing only keyed hashes of IP addresses and checkout cookie identifiers, and restricting store management to a private bot used only by us. Order notifications in Discord are ordinary Discord messages and are protected by Discord's security, not by additional encryption of our own. No method of transmission or storage is completely secure.

## 8. Your Choices and Privacy Requests

Deletion requests are handled as described in Section 6.

Email [Nanashi@NamelessNanashi.dev](mailto:Nanashi@NamelessNanashi.dev) or contact `NamelessNanashi` on Discord (account ID: `221701506561212416`) to request access to, correction of, or deletion of your personal information or previously provided materials—including communications, messages, files, attachments, code, project materials, photos, and videos.

We may request information reasonably needed to verify your identity or an agent's authority. Do not send identity documents unless we request them through an appropriate process. We will respond within any deadline required by applicable law and explain if we cannot fulfill all or part of a request.

You do not need to opt out of data sales or advertising: we do not sell your information or share it for those purposes in the first place.

For information a provider controls independently, you may also need to use that provider's privacy-request process. Contact us if you need help identifying which records we control.

## 9. Adults Only - 18 and Over

Our products and services are intended for adults. **We do not sell products or provide services to anyone under 18.** Customers must also meet any higher age-of-majority requirement described in our Terms of Service.

If you're under 18, please do not place an order, hire us, or send us personal information. If you believe someone under 18 has provided personal information, please contact us. We'll review the situation, stop any ineligible order or service engagement, and handle the information as required by law, including deletion where required. Any cancellation or refund will follow applicable law and our [Refund and Return Policy](REFUND_AND_RETURN_POLICY.md).

## 10. Provider Processing Locations and Third-Party Services

We are based in the United States and accept international customers for remotely delivered services. Our order server is located in the United States. Your information may be handled in the United States or other countries where our providers operate. Their policies explain their processing locations and international transfers. The US-only restriction on physical orders does not mean that all information is stored only in the US.

Links to third-party services do not make their privacy practices part of ours. Review their policies before providing information directly to them.

## 11. Changes to This Policy

We may update this Privacy Policy and will identify the effective date of each version. **Information connected to an order is governed by the version in effect when you placed that order, unless you choose to use the latest version instead.** To choose the latest version, tell us in writing by email or Discord and identify the order. The version in effect at that time then applies to that order's information as a whole, replacing the earlier version. We will provide any notice or obtain any consent required by law before making a material change to how we use previously collected information. An update does not authorize the sale of user data collected under our no-sale commitment.

## 12. Contact Us

Have a privacy question or want help with your information? Please use email or Discord:

Email: [Nanashi@NamelessNanashi.dev](mailto:Nanashi@NamelessNanashi.dev)\
Discord: `NamelessNanashi` (account ID: `221701506561212416`)

We do not accept routine customer communication by postal mail. This does not restrict legally required notices or communication methods.

**If your communication access has been restricted due to harassment, abuse, threats, discrimination, or illegal content**, you may submit warranty claims, privacy requests, and other legally required notices by postal mail to the address below.

Legal correspondence address:

**NamelessNanashi**\
PO Box 163\
Elm Grove WI 53122-0163
