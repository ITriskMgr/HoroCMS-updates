# HoroCMS — User guide

*Beta 0.2.5*

HoroCMS is a private, encrypted register for a fine-watch collection. This guide follows the app's own Help screen (menu › Help), where an assistant can also find the right section for a question.

## Contents

- **Getting started**
  - [Creating your vault](#creating-your-vault)
  - [Unlocking, locking and the inactivity lock](#unlocking-locking-and-the-inactivity-lock)
  - [The overview](#the-overview)
  - [The online assistant (optional)](#the-online-assistant-optional)
  - [Language, formats and appearance](#language-formats-and-appearance)
  - [Support, suggestions and problem reports](#support-suggestions-and-problem-reports)
- **Your collection**
  - [Adding a watch](#adding-a-watch)
  - [Correct brand names and references](#correct-brand-names-and-references)
  - [Web pages and screen captures](#web-pages-and-screen-captures)
  - [Photos and documents](#photos-and-documents)
  - [Searching and sorting the collection](#searching-and-sorting-the-collection)
  - [Service history](#service-history)
  - [Sharing watches privately](#sharing-watches-privately)
  - [Selling a watch: the sale sheet](#selling-a-watch-the-sale-sheet)
  - [Recording a sale or a watch that left](#recording-a-sale-or-a-watch-that-left)
  - [Wear log: time on the wrist](#wear-log-time-on-the-wrist)
  - [Storage: where each watch is](#storage-where-each-watch-is)
  - [Straps and accessories](#straps-and-accessories)
  - [Travelling with watches](#travelling-with-watches)
  - [Your collection on your phone](#your-collection-on-your-phone)
  - [Specifications of a reference](#specifications-of-a-reference)
  - [Importing many watches from a spreadsheet](#importing-many-watches-from-a-spreadsheet)
  - [Checking a watch with WatchBase](#checking-a-watch-with-watchbase)
  - [What’s included: box, papers and extras](#whats-included-box-papers-and-extras)
  - [Researching a new watch with AI](#researching-a-new-watch-with-ai)
  - [Adding many watches from photos](#adding-many-watches-from-photos)
- **Values and currencies**
  - [Recording the purchase](#recording-the-purchase)
  - [Valuations](#valuations)
  - [The Valuation screen](#the-valuation-screen)
  - [Display currency and exchange rates](#display-currency-and-exchange-rates)
  - [Printing an inventory for insurance or a theft report](#printing-an-inventory-for-insurance-or-a-theft-report)
  - [Insurance policies and coverage](#insurance-policies-and-coverage)
  - [Wishlist](#wishlist)
  - [Market prices and price alerts](#market-prices-and-price-alerts)
- **Security and backups**
  - [Forgotten passphrase: using the recovery key](#forgotten-passphrase-using-the-recovery-key)
  - [Hiding values and serial numbers](#hiding-values-and-serial-numbers)
  - [Backups](#backups)
  - [Restoring a backup or moving to a new computer](#restoring-a-backup-or-moving-to-a-new-computer)
  - [Checking the vault](#checking-the-vault)
  - [When something goes wrong](#when-something-goes-wrong)
  - [Sync between your computers](#sync-between-your-computers)

## Getting started

### Creating your vault

HoroCMS keeps your collection in an encrypted vault on this computer. Nothing is sent anywhere.

1. Choose the language and the format for numbers and dates.
2. Choose a passphrase of at least 12 characters. Four or five unusual words are easy to remember and hard to guess.
3. Print or copy your recovery key, then retype its third group to confirm you have it.

Keep the recovery key away from the computer: with your watch papers, in a safe, or with your notary. It is the only way into the vault if you forget the passphrase.

### Unlocking, locking and the inactivity lock

Type your passphrase to unlock. The vault locks itself after a few minutes without activity (5 by default; change it in Settings › Security), and when you choose Lock the vault in the menu.

When the vault locks, the screen returns to the unlock page and decrypted photos are cleared from memory.

### The overview

The overview opens when you unlock HoroCMS. It shows the value of the collection in your display currency and its change over 12 months, the number of watches, what you paid, and when you last made a backup.

Needs attention lists what is worth doing, watch by watch: services due or reminded, service warranties ending, values missing or older than two years, and watches without a receipt, papers, photo or serial number. Click a watch to open the right tab.

A service is suggested every five years for mechanical watches; change this in Settings › Overview. Quartz watches and watches with a service already planned are left out.

Below, the collection is broken down by brand, movement and category, with the watches added most recently.

### The online assistant (optional)

The Help assistant answers from these guides, on your computer, without any connection. If you want fuller answers, including general questions about watches, you can let it ask Claude, Anthropic’s AI. This is off until you turn it on.

1. Create an API key at console.anthropic.com (API keys). Anthropic bills each question to that account, usually a fraction of a cent.
2. In Help, open Use an online AI assistant (or go to Settings › Help assistant) and click Turn on the online assistant.
3. Read what is sent, paste your key and click Turn on.

What is sent: your question, the conversation so far, and the guide pages that match it. What is never sent: anything about your watches, values, photos, documents or passphrases. The key is kept inside your encrypted vault, so the online assistant works only while HoroCMS is unlocked.

Answers from Claude are marked Claude (online), with links to the related guides. If it cannot answer, the guides answer instead. Turn it off, change the model or remove the key in Settings › Help assistant.

### Language, formats and appearance

Choose Français, English, Español or Deutsch at any time from the language list in the menu. Settings › Language and appearance sets the format of numbers and dates and the theme: Acier bleui (light), Ardoise (dark) or Sceau (white). Display size makes everything larger or smaller (80 to 150 %); Window size when HoroCMS opens chooses as you left it, compact, standard, large or the whole screen.

### Support, suggestions and problem reports

Choose Support in the menu to reach the online installation and user guides, the download page, and the author.

To send a suggestion, report a problem or ask a question, choose its type, write a subject and a message, then choose Open in my email program: the message opens ready to send, and you can read and change it first. If you use webmail, choose Copy the message and paste it into an email to the address shown.

Technical details (HoroCMS version, system, language and display size) are added only if you leave the box ticked, and you see exactly what they say. HoroCMS sends nothing by itself and never includes your collection. When reporting a problem, say what you did, what happened and what you expected, and leave out serial numbers.

## Your collection

### Adding a watch

Choose Add a watch on the Collection screen, then say which watch it is:

- From my references: a model you already described (its specifications are shared).
- New reference: describe the brand, collection, model and reference once.
- Not sure yet: just the brand; you can link the exact reference later.

Serial numbers can be recorded, unknown, partly legible or disputed, so you never have to invent one.

You can record the purchase at the same time (see Recording the purchase).

### Correct brand names and references

HoroCMS keeps identities consistent so that searches, totals and reports stay right:

- Brands are stored under their official name whatever you type: Oméga, OMEGA and omega all become Omega; Patek becomes Patek Philippe; JLC becomes Jaeger-LeCoultre.
- A collection or model name already used for the brand keeps that spelling.
- References are written one way (capitals, single spaces). If the reference is already in your catalogue, HoroCMS links the watch to it instead of creating a duplicate.
- If a name looks like a typo of a known brand, HoroCMS suggests it; nothing is changed without telling you.

### Web pages and screen captures

For a recent reference, add the manufacturer’s page in the Official page field (or later in the Specifications tab). If you bought online, add the order page in the purchase.

To keep a copy of the page as it was, take a screen capture and add it with Add a screen capture: press Shift-Command-4 (Mac) or Windows-Shift-S (Windows), then click the paste area and press Command-V or Ctrl-V. You can also choose an image file.

Each capture remembers the address of the page it shows. HoroCMS opens links in your browser only when you click them.

### Photos and documents

In a watch’s Photos and documents tab, add JPEG, PNG, WebP, HEIC, PDF or text files (up to 50 MB each). Files are encrypted in the vault; your originals are not changed.

Open a photo to see its details: the date and time it was taken, the camera, its size, and where it was taken if the phone recorded a position. Show on the map opens OpenStreetMap in your browser.

A photo that records its position is marked Contains location. The encrypted original keeps it; copies you share will not.

### Searching and sorting the collection

Search by brand, collection, model, reference or nickname; a case serial must be typed in full. Filter by brand or category, and include watches you no longer own if you wish.

Sort by name, brand, oldest or newest, value, purchase cost, recently acquired, longest held, recently added or recently serviced.

### Service history

In the Service tab, record each service with its provider, dates, cost, warranty and a reminder for the next one. List the parts replaced, refinished or returned to you: they matter for originality. Attach the invoice to the service.

### Sharing watches privately

Share… (on the Overview or Collection screen) prepares a description of the watches you choose, to print, save as PDF or save as a spreadsheet (CSV).

- Friend or collector: photos and descriptions only.
- Insurer or appraiser: adds the purchase, the current value and the list of documents on file.
- Custom: descriptions only, plus what you tick.

Serial numbers and storage locations are hidden in every case: they are what a thief needs most. You can add them for someone you trust; HoroCMS then warns you before printing or saving.

Notes are never included, and photos are copies without the location or camera details your phone recorded. The preview shows exactly what will be shared, and lists what is hidden.

### Selling a watch: the sale sheet

Sell (in the menu, on the Overview, in the Collection or on a watch’s record) creates a professional sale sheet in PDF: one or two pages per watch with the main photo, a price box, the highlights, a description, more photos and the full specifications.

1. Tick one or more watches. With several watches, the sheet opens with a cover that shows them all.
2. For each watch, enter an asking price, or leave it empty to show Price on request. Tick Negotiable if you are open to offers. Choose up to six photos; the first is the main photo.
3. Check the description: HoroCMS writes a first draft from the record, in the language of the sheet, and you can rewrite it.
4. Fill in your contact details: name, email, and if you wish a phone number, WhatsApp, a Messenger user name and your city. They are kept in your vault for next time.
5. Add a note if you like, for example a show or a group sale where you will be, then choose Create the PDF.

The sheet can be in French, English, Spanish or German, whatever the language of the app, on Letter or A4 paper.

To email it: on a Mac, Create the message in Mail opens a new message with the PDF attached. Otherwise your email program opens with the subject and message filled in, and the folder with the PDF opens beside it. Nothing is sent until you press Send.

Privacy: the serial number is left out unless you tick Show the serial number, notes and values are never printed, and photos are copies without location or camera details.

### Recording a sale or a watch that left

When a watch leaves the collection, open its record and choose Record that it left the collection: sold, traded, given away, lost, stolen or passed on.

For a sale or a trade, enter the price or value and the fees (commission, shipping, insurance), with their currency, and who bought it.

The watch keeps all its history (photos, documents, service, values) and stops counting in the value of the collection and on the wrist. If a sale falls through, it can be undone.

### Wear log: time on the wrist

Each watch’s record has a Wear tab. Choose Put it on when you put the watch on, and Take it off when you take it off: HoroCMS records the time on the wrist. Putting another watch on takes the first one off.

While a watch is on, the menu shows it with the time so far and a Take it off button.

Forgot? Log a day afterwards with or without a duration (8:30, 2h or 45 min), and an occasion. Any time can be corrected; a session left open is capped at 24 hours.

Wear (in the menu) shows the last 30, 90 or 365 days: a calendar, the most worn watches with their time and cost per wear (purchase price divided by every day worn), and the watches waiting for the wrist for 60 days or more.

### Storage: where each watch is

Storage (in the menu) lists your places, one inside another: the house, the safe in it, the tray in the safe. Each place shows the watches kept there, then the watches that are away and those with no place yet.

To record where a watch is, open its record › Storage and insurance › Move or lend…: stored in a place, being worn, at the watchmaker, lent, travelling or on consignment, with the date and, if it is with someone, who. Earlier places are kept as history.

A place’s private details (address, box number) stay behind the veil and are never shared or exported.

### Straps and accessories

Straps and accessories (in the menu) records straps, bracelets, buckles, spare links, winders, boxes, pouches and tools, with their price.

Put a strap on a watch with Put on: it comes off the previous watch by itself, and its history is kept. Enter a strap’s width at the lugs and HoroCMS lists the watches it fits.

On a watch’s record, the Storage and insurance tab shows the strap on it now.

### Travelling with watches

Travel (in the menu) plans a trip: name, destination and dates, the watches and accessories you take, and a checklist (travel case, insurance certificate, receipts for customs…) you can change.

Tick each item Packed when it goes in the case, choose We’re leaving, and tick it Back when you are home. Back home warns you about anything not ticked; the Overview also reminds you once the return date has passed.

A trip does not move watches in the collection by itself. To note that a watch is travelling, use its Storage and insurance tab.

### Your collection on your phone

The HoroCMS companion for iPhone and Android shows your collection with its photos, lets you put a watch on and take it off, and keeps your wishlist. What you change on the phone comes back to your computer.

On the computer, open Settings › Phone companion and choose Turn on the phone companion, then Pair a phone (your passphrase is asked). On the phone, choose a passphrase for the phone, then Scan the code, or type the address and the code shown on the computer. Both must be on the same Wi-Fi network.

The phone keeps its own encrypted copy of the collection and locks itself when you leave the app. It talks only to your computer, on your home network, and only while HoroCMS is unlocked there; nothing goes through the internet. If your computers sync through a cloud folder, the phone also receives what the other computers send.

The first time, macOS or Windows may ask whether HoroCMS may accept incoming connections: allow it on private networks only. Turn the companion off in the same place when you do not need it. If you forget the phone’s passphrase, erase the phone’s data from its unlock screen and pair it again.

### Specifications of a reference

The Specifications tab of a watch holds its reference’s full technical description in 21 groups: identification, production, movement and its details, certifications, complications (with the chronograph’s control and clutch), case dimensions and construction, crown and pushers, crystal, case back, dial, lume, hands, bracelet, water resistance, magnetism and shock, limited edition, manufacturer information and data quality.

Choose Edit beside a group to fill it in. Numbers can be typed as you like (40, 40.5 or 40,5 mm). Groups with nothing recorded are hidden; tick Show details not recorded to see every field. The gauge shows how many essential details are recorded.

Specifications belong to the reference: every watch of the same reference shares them. Data quality records where the information comes from, whether it was verified, how confident you are and when it was last checked.

### Importing many watches from a spreadsheet

In Collection, choose Import from a spreadsheet, then choose an Excel, Numbers or LibreOffice file (.xlsx, .xls, .ods) or a CSV file. The first row names the columns; each other row is one watch. Save a template to start from a file with every column HoroCMS reads.

HoroCMS recognises column names in English, French, Spanish and German, including any specification (diameter, bezel, case back…). Check the mapping and correct a column if needed, then choose Check the rows: nothing is saved yet. Rows with a problem are listed and left out; rows whose serial number is already in the collection are flagged as possible duplicates.

Choose Import to create the watches, with their purchase (date, price, currency, seller), category and specifications. Only the brand is required. Up to 5,000 rows at a time.

### Checking a watch with WatchBase

WatchBase is a database of watch references. With your own WatchBase data-feed key (request one at datafeed.watchbase.com), HoroCMS can check a reference and fill its specifications. It is off by default: turn it on in Settings › WatchBase and enter the key, which is kept in your encrypted vault on this computer.

When you add a watch, type the brand and the reference, then choose Check with WatchBase. The search is free. Pick the right watch and choose Fill from this watch: WatchBase charges for these details (US$0.30 per watch when this was written), so HoroCMS only asks for them when you confirm. The form and the Specifications tab are filled, and Data quality records WatchBase as the source.

For a watch already in the collection, use Check with WatchBase in its Specifications tab: only what is not recorded is filled; your own values are kept. Only the reference or the words you search for are sent, never serial numbers, prices or photos. WatchBase does not license its images, so none are shown.

### What’s included: box, papers and extras

The Overview of each watch has a What’s included section in three groups: packaging (the box), documentation (the papers) and accessories and extras. Choose Record what’s included, then mark each item Included, Not included or Not recorded.

- Packaging: inner presentation box, a box that is not original but suits the model, outer cardboard box.
- Documentation: warranty card or certificate, certificate of authenticity, chronometer certificate, instruction manuals, booklets, service records, receipts.
- Accessories and extras: hang tags, spare links, additional straps, specialized tools, bezel protectors.

Countable items take a quantity (2 spare links, 3 booklets) and every item takes a short note, such as the date on a warranty card or the condition of a box. The inner presentation box and the warranty card together make a full set; they also answer Box and Papers in the watch form, and the sale sheet lists everything that comes with the watch.

### Researching a new watch with AI

When you add a watch, Research with AI at the top of the form can identify it for you. Describe the watch in a few words (brand, model, reference, dial colour…), or type them in the form, then choose Research. Claude, Anthropic’s AI, searches the web, usually in 20 to 60 seconds, and shows the watch it found, how sure it is, the sources it read and other possible matches.

Choose Fill the form to use what was found: brand, collection, model, reference, movement, calibre, diameter, official page and dial, and every other specification it could confirm, which is saved in the Specifications tab with the watch. Check everything against the watch and its papers before saving: AI can be wrong, so these details are marked AI research, unverified, in Data quality. If the watch was not identified with confidence, choose one of the other matches to research it.

It uses the Help assistant with your own Anthropic key: turn it on in Settings › Help assistant. Only the words you typed about this watch are sent, never anything else from your collection. Each research uses up to five web searches, billed by Anthropic to your account (a few cents).

### Adding many watches from photos

In Collection, choose Add from photos, then Choose a folder of photos. Put one photo per watch in the folder, with the dial clearly visible. HoroCMS reads JPEG, PNG and WebP photos, and iPhone HEIC photos on a Mac; on Windows, export HEIC photos as JPEG first. Up to 200 photos at a time.

Choose Identify with AI: Claude looks at each photo, reads the dial and searches the web to confirm the reference. Each row then shows what it found and how sure it is. Correct the brand, model or reference where needed, untick the photos you do not want, and choose Add. If you change the identification, the details the AI found for that watch are not saved. Without the Help assistant, you can still type each watch yourself.

Every watch added this way gets its photo and is marked AI · to verify, in the collection, on the watch and in the overview’s Needs attention. Open it, check its details and specifications against the watch and its papers, then choose I checked: mark as verified. The filter Only AI-identified watches to verify lists the ones left. Watches filled in by Research with AI are marked the same way.

Each photo is sent to Anthropic as a reduced copy without its location or other metadata, with its file name, using your own key; nothing else from your collection. Each costs a few cents.

Deep dive: on a watch still to verify, choose Deep dive: look for more information. Claude checks the identification against more sources (up to 8 web searches, usually 10 to 30 cents) and looks for the details still missing. It lists the new details, ticked, and those that differ from what is recorded, not ticked; save only what you keep. If the sources point to a different watch, it says so and changes nothing.

## Values and currencies

### Recording the purchase

When adding a watch (or later in its Acquisition tab), record how it came to you: date, seller, the currency of the transaction, and the price, fees and taxes paid in that currency.

Type amounts the way you write them (14 650,00 or 14,650.00). They are stored exactly to the cent; a blank amount stays unknown, never zero.

If the currency differs from your display currency, HoroCMS shows the equivalent at the rate of the purchase date and can keep that rate with the purchase.

Attach the receipt or invoice to the purchase with Attach a document.

### Valuations

In a watch’s Values tab, add a valuation with its basis (market, replacement, quick sale, insured) and its source (your estimate, an appraisal, a verified sale, an asking price).

Valuations are never overwritten: each new one joins the history. You can accept or reject one; the latest valuation not rejected is used for each basis.

Attach the appraisal report to the valuation it supports.

### The Valuation screen

Valuation in the menu shows what the collection is worth today on the basis you choose, what it cost, the change since purchase, a chart of its evolution and a line per watch.

A watch without a valuation on that basis counts at its cost, and the screen says how many do. Past values use the rate of their date; costs use the rate of the purchase date.

Hover over or use the arrow keys on the chart to read each month; Show as a table gives the yearly figures.

### Display currency and exchange rates

In Settings › Currency, choose the currency in which every screen shows amounts. The ten main currencies are listed; add any other ISO code (for example NOK).

Before a currency is used, HoroCMS checks the rate it will use and shows its date and source. Amounts stay stored in the currency you entered.

Official daily rates come from the Bank of Canada if you turn on Fetch official daily rates. It is off by default; only currency codes and a date are sent. You can also enter a rate yourself; it takes precedence on its date.

### Printing an inventory for insurance or a theft report

On the Valuation screen, choose Print an inventory, then the kind of document:

- Insurance schedule: every watch you own, with photo, reference, serial numbers and value (insured value by default), totalled.
- Theft or loss report: tick the watches concerned; each is described in full (photos, serials, distinguishing features, purchase, value, documents on file), with the date, place and police report number you type.

Printing shows serial numbers, so HoroCMS asks first. The names and incident details you type are not stored. Use Save as PDF in the print dialog to keep a file.

### Insurance policies and coverage

Insurance (in the menu) keeps your policies: insurer, number, kind, dates, limit, deductible and premium. HoroCMS reminds you on the Overview 45 days before a renewal.

Add each watch to a policy with its insured value. Beside it, HoroCMS shows today’s market value: a watch insured for less than 85 % of it is marked Under-insured, so you can ask your insurer to update the schedule.

Watches covered by no policy in force are listed with their value. Claims (loss, theft, damage) are recorded on the policy with the amounts claimed and paid, and the police report number.

For your insurer’s file, Inventory for the insurer prints the inventory with photos and documents.

### Wishlist

The Wishlist keeps the watches you are looking for: priority from 1 (grail) to 5, the most you will pay, the lowest condition you accept, whether box and papers are required, and where you would buy.

When you buy one, choose I bought it and pick the watch in your collection: the wish is kept, linked to it.

Prices and alerts for wishlist watches are in Market prices (see Market prices and price alerts).

### Market prices and price alerts

Market prices (in the menu) follows the watches on your wishlist. For each one it shows your maximum price, the lowest asking price of the last 90 days, the median sale of the last 12 months and the latest estimate, all in your display currency.

To record a price, choose Record a price. You can paste the text of a listing or an auction result with its link: HoroCMS reads the price, currency, reference and whether box and papers are included, on your computer, without opening the page. Check, then save. To add many at once, import a CSV file (date, brand, reference, price, currency, and optionally kind, source, link, condition, box, papers).

Alerts: tick When a listing meeting my conditions is at or below… or For every new listing. They are checked on your computer each time a price is recorded and when you unlock; the Overview tells you about new matches. Listings that do not meet your conditions (box and papers, minimum condition) never trigger an alert.

Optional: automatic prices from WatchCharts, with your own paid WatchCharts API key. It is off by default; when on, only the brand and reference of the watches you choose are sent. Owned watches receive a market value, wishlist watches an estimate.

## Security and backups

### Forgotten passphrase: using the recovery key

On the unlock screen, choose Forgotten passphrase?, type the recovery key (29 characters; dashes and case do not matter), then choose a new passphrase.

If a character is wrong, HoroCMS says the key contains a typo: compare each group with your printed copy.

You can generate a new recovery key at any time in Settings; the old one stops working immediately.

### Hiding values and serial numbers

Amounts and serial numbers appear as dots until you press Show values; they hide again when the vault locks. The window is also excluded from screenshots and screen sharing (Settings › Security).

### Backups

HoroCMS makes an encrypted backup automatically after you unlock, at most once a day, in HoroCMS’s own data folder (or a folder you choose; Settings › Backups › Show in Finder or Explorer opens it). It keeps the 10 newest. Each automatic backup opens with the passphrase you unlocked with that day.

To make one yourself, go to Settings › Backups, choose a passphrase for it and Save a backup…, then pick a place such as a USB key. Keep at least one copy away from the computer.

### Restoring a backup or moving to a new computer

On a new computer, choose Restore from a backup… on the first screen; on this one, use the unlock screen or Settings.

1. Choose the backup file (.horobak).
2. Type its passphrase.
3. Choose the passphrase for the restored vault.

Everything is checked before the current vault is touched; the current vault is kept aside. You receive a new recovery key to print.

### Checking the vault

Settings › Vault health checks the database, decrypts and verifies every photo and document, and looks for inconsistencies (for example a sold watch still insured). Each finding is explained; damaged files can be recovered from a backup.

### When something goes wrong

HoroCMS checks everything it reads, so damage is detected rather than shown as wrong data. Two kinds of problem can happen after a disk failure or a crash.

The collection will not open, although the passphrase is right. HoroCMS then offers two ways back:

- Go back to an automatic copy: HoroCMS keeps one before each update. Changes made since are lost; photos and documents are not affected. The damaged file is kept aside.
- Restore a backup: choose your most recent one (see Restoring a backup or moving to a new computer).

Some photos or documents are missing or damaged. Settings › Vault health › Check the vault finds them. Choose a backup made when they were fine and type its passphrase: HoroCMS copies back only those files, after checking each one. Files not in any backup can then be removed from the record; the watch itself is not affected.

Keep backups on a USB key or another disk, not only on this computer: they are what makes every problem recoverable.

### Sync between your computers

Sync keeps the same collection on your computers (for example a Mac and a Windows PC) through a cloud folder you already use: iCloud Drive, OneDrive, Dropbox or Google Drive. It is off until you turn it on in Settings › Sync between your computers.

On the first computer, name it, choose Choose the folder and start, and pick your cloud folder. HoroCMS creates a HoroCMS Sync folder in it and shows a code of nine groups of four characters. On the other computer, once your cloud app has downloaded that folder, open Settings › Sync between your computers, type the code, choose Choose the folder and join, and pick the same cloud folder.

Everything is encrypted on your computer with a key that comes from the code before it reaches the folder, photos and documents included; your cloud service sees only sealed files. HoroCMS itself sends nothing over the internet. Keep the code like a password. The keys for the online assistant and WatchCharts stay on each computer.

HoroCMS syncs when you unlock, every three minutes while the vault is open, when you lock and when you choose Sync now. If the same record was changed on both computers before they synced, the most recent change wins. To add a computer later, choose Show the code (your passphrase is asked). Stopping sync on one computer keeps its collection and does not affect the others. Sync does not replace backups: keep your encrypted backups.

---

© 2026 Marc-André Léger. All rights reserved. Built with Claude (Anthropic).
