# Payment workflow

## Required sequence

1. The prospect starts a WhatsApp conversation from the website.
2. Confirm client identity, need, deliverables, exclusions, timing, price, currency, revision policy, and acceptance criteria.
3. Record the agreement in the appropriate proposal/contract form for the owner's jurisdiction.
4. Create the client/project in Bonsai.
5. Create an invoice with precise line items and due date.
6. Send the Bonsai invoice/payment URL through the agreed channel. Share links only with the intended recipient.
7. For a Bonsai-integrated card payment, confirm the invoice status in Bonsai before starting the paid phase.
8. For Wise, Payoneer, IBAN, or bank transfer, independently confirm cleared funds, then use Bonsai’s receive-payment action to record amount, date, and method. Do not mark paid from a screenshot alone.
9. Deliver against the written scope, record completion, and retain the agreement, invoice, payment record, and handoff evidence according to applicable law.

## Controls

- Never collect card details on the website, in chat, or in project documents.
- Never commit payment instructions, bank details, API keys, or personal client data to Git.
- Do not imply that every external method is supported in every region.
- Refunds follow the signed agreement and the relevant payment rail; external-method refunds are handled externally and recorded.
- Confirm current fees and currency/region availability before quoting a final payable amount.

References: [marking external payments paid](https://help.hellobonsai.com/en/articles/2899880-how-to-manually-mark-invoices-as-paid), [offline instructions](https://help.hellobonsai.com/en/articles/1195676-adding-custom-offline-payment-instructions-to-invoices), and [refund handling](https://help.hellobonsai.com/en/articles/919333-refunding-invoice-payments-to-clients).

