# NextCard

**The Digital Business Card**

NextCard is a simple digital business card by **NEXTWAVE LABS**. A
physical NFC-enabled card or QR code can open a personal web profile
where contact information and useful actions are available instantly.

The initial NextCard profile is for **Sohail Aziz --- Founder & CEO,
NEXTWAVE LABS**.

## Live Profile

**Sohail Aziz**\
Founder & CEO\
**NEXTWAVE LABS**

`https://nextcard.next-wav.com/sohailaziz`

## Current Features

-   NFC card opens the digital NextCard profile
-   QR code provides an alternative way to open the profile
-   Click-to-call
-   WhatsApp
-   Email
-   Website
-   LinkedIn
-   Save Contact as a vCard (`.vcf`)
-   Share NextCard
-   Responsive mobile-first web interface
-   No dedicated app required for the basic NFC-to-web experience


## Repository Structure

``` text
nextcard/
├── LICENSE.md
├── README.md
└── sohailaziz/
    ├── index.html
    ├── styles.css
    └── nextwave-labs-logo.png
```

The `sohailaziz` directory contains the web profile intended to be
served at:

`nextcard.next-wav.com/sohailaziz`

## How It Works

The physical NextCard contains an NFC tag programmed with the profile
URL:

`https://nextcard.next-wav.com/sohailaziz`

When a compatible phone is brought near the card, the phone detects the
URL and allows the user to open the NextCard profile in the browser.

The QR code printed on the physical card points to the same URL and acts
as a simple fallback when NFC is unavailable or inconvenient.

## Deployment

NextCard can be hosted as a static website.

For the current GitHub Pages deployment structure, keep the files inside
the `sohailaziz` directory together so relative assets such as the
NEXTWAVE LABS logo and stylesheet resolve correctly.

The intended public route is:

`https://nextcard.next-wav.com/sohailaziz`

## Brand

**NEXTWAVE LABS**

*Purity . Clarity . Brilliance*

Website: `https://next-wav.com`

## License

This project is **source-available**, not open source.

It is licensed under the:

**NEXTWAVE LABS Non-Commercial License (NWL-NC) v1.0**

You may view, study, download, modify, and use the source code subject
to the terms of the license.

**Commercial use is prohibited without prior written permission from
NEXTWAVE LABS (SMC-Private) Limited.**

The NEXTWAVE LABS and NEXTCARD names, logos, trademarks, visual
identities, and other brand assets are not granted for use under the
software license.

See [`LICENSE.md`](LICENSE.md) for the complete license terms.

------------------------------------------------------------------------

Copyright © 2026 **NEXTWAVE LABS (SMC-Private) Limited.**\
All rights reserved.
