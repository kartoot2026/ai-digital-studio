# Payment workflow

## Required sequence

1. The prospect starts a WhatsApp or email conversation from the website.
2. Confirm client identity, need, deliverables, exclusions, timing, price, currency, revisions, and acceptance criteria.
3. Record the agreement in the appropriate proposal or contract for the applicable jurisdiction.
4. Create the customer and quote in Zoho Invoice.
5. After approval, create an invoice with precise line items, milestones, currency, and due date.
6. Send the Zoho Invoice link only to the intended client.
7. For a Stripe payment, confirm the paid status in both Zoho Invoice and Stripe before starting the paid phase.
8. For Wise, Payoneer, IBAN, or bank transfer, independently confirm cleared funds and then record the payment in Zoho Invoice.
9. Deliver against the written scope and retain the agreement, invoice, payment record, approvals, handoff, and completion evidence privately.

## Controls

- Do not collect card details on the website, WhatsApp, email, or project documents.
- Do not commit payment instructions, bank details, keys, or client data to Git.
- Stripe is not operational until its account review is approved.
- Do not mark an invoice paid from a screenshot supplied by a customer.
- External methods are offered only when the owner can legally and operationally receive them.
- Refunds follow the written agreement, applicable law, and the original payment rail where possible.

References: [Zoho Invoice online payments](https://www.zoho.com/en-sg/invoice/help/online-payments/), [Stripe integration](https://www.zoho.com/us/invoice/help/online-payments/stripe.html), and [customer portal](https://www.zoho.com/in/invoice/help/customer-portal/).
