# JARS Product Tool

A Windows desktop app that automates bulk product creation in the Dutchie backoffice, from a CSV, a form, a saved template or a vendor invoice PDF.

**[⬇ Download the latest installer](../../releases/latest)**

This repo holds only the installers and the auto-update files. The source code is kept in a separate private repo.

---

## Install

1. Download the `.exe` installer from the [latest release](../../releases/latest).
2. Run it. You can choose where to install it. It adds a desktop shortcut and a Start Menu entry.
3. You don't need Node.js or anything else. Automation runs in **Microsoft Edge**, which comes with Windows 11.

### First-time setup

A fresh install has no Claude API key and no Snowflake connection. Until both are added in **Settings**, the Invoice Parser won't run, and the dropdown lists come from the lists shipped with the app. Get the keys, the module list and the house brands from the data team, and follow **First-time setup** in the staff SOP.

## Updates

The app checks for updates when it starts and downloads them in the background. When an update is ready, open **Settings → About** and click **Restart & Install**. To check by hand, click **Check for Updates** in the same place.

---

## What it does

| Page | What it's for |
|---|---|
| **Dashboard** | Launch the Dutchie session, manage the product queue and run it |
| **Add Product** | Add a product by hand |
| **Templates** | Save an in-house product format once, then make one product per strain |
| **Invoice** | Drop in a vendor invoice PDF and get products named to the naming guide, ready for the queue |
| **Create Strain** | Create Dutchie strains in bulk |
| **Add Vendor/Brand** | Create vendors and brands in Dutchie |
| **History** | Every run, with a log for each item and a CSV export |
| **Settings** | Companies and modules, lookups, API keys, Snowflake, updates |

---

## How to use it

Step-by-step instructions are in the **staff SOP** on SharePoint, which is kept up to date with each release. Ask the data team for the link. This page covers only installing and updating.

---

## Reporting a problem

Open an [issue](../../issues). Include the app version (shown under **Settings → About**) and what you were doing. For an invoice problem, attach the invoice PDF if you're allowed to share it.
