# Invoices

One PDF per invoice, named by its invoice number exactly as written on the invoice:

`INV-7E846BE1.pdf`, `INV-B8438A47.pdf`, ...

The `invoice` field of each entry in data.json points here, e.g. `"invoice": "invoices/INV-7E846BE1.pdf"`.

Receipts without an invoice number (e.g. hospitality): use `YYYY-MM-DD-name.pdf`, for example `2026-11-27-emily-lunch.pdf`, and put that same name in the entry's `invoice` field.
