<div align="center">

# BayPOS

**Point-of-sale for a single-lane supermarket — built for the UAE, works fully offline.**

<img src="docs/baypos-demo.gif" alt="BayPOS — supermarket point-of-sale demo" width="840" />

Fast barcode checkout · UAE 5% VAT · bilingual English/Arabic invoices · customer credit (khata) · inventory & purchasing · reports.

### [⬇️ Download the latest version](https://github.com/AbdulRahim-Ul-Haq/BayPOS-releases/releases/latest)

Download **`BayPOS-win-Setup.exe`** from the latest release and run it. That's it.

</div>

---

This is the **download & updates** home for BayPOS. Every release below contains the
Windows installer plus the update packages the tills use to keep themselves current.

## Install on a new till

1. Open the **[latest release](https://github.com/AbdulRahim-Ul-Haq/BayPOS-releases/releases/latest)**.
2. Under **Assets**, download **`BayPOS-win-Setup.exe`**.
3. Double-click it. BayPOS installs and creates a desktop shortcut — no sign-in, no account, nothing to configure.

> **"Windows protected your PC"?** The installer isn't code-signed yet, so Windows
> SmartScreen may warn you the first time. Click **More info → Run anyway**. It only
> happens on the very first install.

**First launch:** sign in with the default admin PIN **`1234`**, then go to
**Staff** and change it right away (and add a PIN for each cashier).

## Automatic updates

Once installed, a till keeps itself up to date — no need to visit this page again.
On startup it quietly checks here, downloads any new version in the background, and
applies it the next time BayPOS starts. Nothing to click, no login required.

## What BayPOS does

- **Checkout** — barcode scanning, tap-to-sell item browser with product photos,
  weighed items (enter weight *or* amount), cash / card / on-account tender,
  change calculation, and a printed invoice after every sale.
- **UAE VAT** — 5% back-calculated from shelf prices, simplified tax invoices with
  your TRN, bilingual **English/Arabic**, and your business **WhatsApp QR code** on
  every receipt.
- **Customer credit (khata)** — credit limits, an append-only account ledger,
  cash/card settlements with printed payment receipts, and monthly statements.
- **Invoices** — reprint, change payment method or customer, itemised **refunds**
  (proper credit notes), and void — all audit-logged.
- **Inventory** — stock tracking, adjustments with reasons, low-stock alerts,
  product photos, and CSV catalogue import.
- **Purchasing** — suppliers, purchase invoices, a **supplier-payments** screen
  (oldest unpaid first) with cheque/transfer proof capture, and stock-in.
- **Shifts** — open with a float, close with counted cash, Z-report.
- **Reports** — 13 reports (sales, VAT, top products, cashiers, stock and more),
  sortable, with one-click **PDF and Excel export**.
- **Staff & security** — cashier / manager / admin roles with **configurable
  permissions**, PIN login, and a full audit log.
- **Settings** — store profile & logo, WhatsApp number, 5 colour themes
  (light & dark), receipt printer, and backups.
- **Backups** — automatic daily snapshots, plus one-click **backup & restore to USB**.

## What you need

| | |
|---|---|
| **Computer** | Windows 10 or 11, 64-bit |
| **Barcode scanner** | Any USB keyboard-wedge scanner — works out of the box |
| **Receipt printer** *(optional)* | 80mm ESC/POS printer, e.g. **BIXOLON SRP-E300**, with its Windows driver installed |
| **Internet** | Only for downloading updates — the till runs completely offline |

### Setting up the receipt printer

1. Install the printer's own Windows driver (from the manufacturer).
2. In BayPOS: **Settings → Receipt printer**, pick the printer, choose the paper
   width (80mm), then **Test print**. Enable the cash-drawer option if your drawer
   is wired to the printer.

Receipts print in English and Arabic and include your store details and WhatsApp QR.

## Your data & backups

All data lives **on the till** at `C:\ProgramData\BayPOS` — it never leaves the shop.
BayPOS makes a backup automatically every day. To keep an off-site copy, plug in a
USB drive and use **Settings → Backup to USB**; you can restore from there on the
same or a replacement machine.

## Support

Questions, a new feature request, or trouble installing? Contact the BayPOS maintainer:

- **Owner:** AbdulRahim-Ul-Haq

---

<div align="center">
<sub>Installers here are free to deploy to your own tills. The application source code is maintained privately.</sub>
</div>
