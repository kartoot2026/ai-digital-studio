# Zoho Invoice setup

> The filename is retained for compatibility with the original project specification. Bonsai was not used because account access was blocked; Zoho Invoice is the approved operational system.

## Current configuration

- Organization: AK DIGITAL MARKETING LLC (ARBISOFT)
- Brand: ARBISOFT
- Default currency: USD
- Invoice theme: light layout with ARBISOFT green accent
- Logo: A — ARBISOFT
- Terms, customer note, and payment thank-you message configured
- Automated reminders enabled for 1, 7, and 14 days overdue
- Stripe connected with cards and Apple Pay selected
- Live card processing remains unavailable until Stripe completes its review

## Remaining owner-controlled steps

1. Add and verify `support@arbisoft.biz` as an approved sender.
2. Configure the Customer Portal welcome message and invite clients individually.
3. Create one real client only after scope and consent are established.
4. Enable Stripe on an invoice only after Stripe approves the account.
5. Record Wise, Payoneer, IBAN, or bank transfers as external payments after funds clear.
6. Never collect card or bank credentials through WhatsApp, email, or this repository.

Official references:

- [Zoho Invoice customer portal](https://www.zoho.com/in/invoice/help/customer-portal/)
- [Zoho Invoice reminders](https://www.zoho.com/in/invoice/help/settings/reminders.html)
- [Zoho Invoice and Stripe](https://www.zoho.com/us/invoice/help/online-payments/stripe.html)
- [Zoho Invoice payment links](https://www.zoho.com/in/invoice/help/payment-links/receiving-payments.html)
