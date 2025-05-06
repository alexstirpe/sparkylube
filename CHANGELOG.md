Changelog, Authors: Mohammed M. & Alexandria S. (Molex)

All notable changes to this project will be documented in this file.
This project adheres to a structured changelog format for clarity and version control.
[v1.0.0] — Initial Launch (April 2025)
Added

    Basic website structure using HTML and CSS.

    Homepage layout with:

        Logo header section

        Call-to-action with phone number and address

        Promotional image cards for services

        Embedded Google Map with directional buttons (Google, Apple, Waze)

        Business description and footer

    Countdown timer with JavaScript showing expiry for promotions.

    All asset placeholders added to /assets.

[v1.0.1] — Responsive Improvements & Accessibility Pass (May 2025)
Changed

    Ensured layout responsiveness using Flexbox refinements.

    Font sizes and spacing optimized for small screen devices.

    Added alt tags to all images for screen reader compatibility.

    Adjusted contrast for text against backgrounds for improved readability.

    Reorganized promo section to prevent overflow and maintain clarity on mobile views.

Removed

    Redundant text styles and unscalable element sizes.

[v1.0.2] — Print Optimization Patch
Added

    Full print styling for promotions via @media print CSS query.

    Dedicated print-btn functionality to allow users to print optimized coupon pages.

    Included only essential sections for printing:

        Header with logo

        Call-to-action section

        All three promotions in single-page layout

        Clean footer with no unnecessary line breaks

Changed

    Disabled screen-only elements during print (map, navigation buttons, countdown).

    Compressed all promotional images for faster load times and better print quality.

    Flattened promo layout in print to appear side-by-side instead of stacked.

[v1.0.3] — Structural & UX Enhancements
Added

    Explicit section comments for easier HTML navigation.

    Flex adjustments to .promo-items for natural horizontal stacking.

    page-break-before and page-break-after properties fine-tuned to eliminate blank pages during printing.

Ensured

    Print layout now fits on a single page with properly aligned elements.

    Accessibility for senior users by using legible fonts, clear contrast, and logical flow of information.

Ongoing testing and feedback will continue to shape refinements in future minor versions. Accessibility, performance, and load time remain key priorities.