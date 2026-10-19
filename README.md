# JOY rewards prototype

Research-led responsive frontend for the JOY by PepsiCo EU redesign. All offers, terms, dates, members and outcomes are illustrative. No live account, purchase, promotion entry, email or reward redemption is implemented.

## Open locally

Open `dist/index.html` in a modern browser, or serve `dist/` with a static HTTP server. There is no installation or build step. All visual assets and fonts are bundled locally. Local storage persists example activity on the current browser.

## Explore

- Home: logged-in greeting, activity summary, suggestions, entered promotions and favourite brands.
- Footer: switch between guest and member examples.
- Promotions: search; brand, type, market and availability filters; saved promotions; sorting.
- Details: prize, eligibility, deadline, requirements, FAQs and example terms.
- Entry: use `JOY2026`; confirm the simulation statements. Select an error, win or no-prize scenario where available.
- Result: draw confirmation or instant outcome, saved in My JOY. Use **Test another outcome** to replay a flow without duplicating entries.
- My JOY: activity, illustrative rewards, favourite brands, preferences and personal information. Reset restores the initial sample data.
- About this prototype: source links, research rationale and limitations.

## Design foundations

`tokens.css` transcribes the supplied JOY, Doritos and Rockstar semantic themes. `styles.css` adapts supplied component patterns to responsive layouts. `app.js` holds structured promotion data, reusable view functions, routing and browser-local state.

The default theme is JOY. Pepsi and 7UP use JOY because no dedicated theme was supplied. The native Figma source files are unchanged. The console and JOY logo assets were downloaded from the supplied wireframes. Ticket graphics are labelled illustrative prize artwork. The latest visual reference is https://www.joy-pepsico.eu/en-gb/: Galano fonts, white logo, blue header/footer, yellow hero buttons and decorative shapes are applied. Font files and reference artwork are bundled for this design demonstration.

## Verification

Browser checks covered search, brand and availability filters, market empty states, disabled ended entries, onboarding acknowledgement, invalid-code feedback, recoverable submission errors, draw confirmation, instant winning results, stored activity, brand following and preference saving. Layouts were reviewed at 390px and desktop widths. JavaScript syntax and local asset presence were checked.

This is implementation verification, not user validation or a complete WCAG audit. Before launch, validate with target-market participants and assistive-technology users, then integrate approved rules, real authentication, verified eligibility, secure entry services and prize fulfilment.

Visual update (18 October 2026): full-width JOY campaign layout, live site lifestyle and product artwork, official brand logos and account buttons. New sessions start as a guest; use the footer to switch to the sample member. These public brand assets are included for this design demonstration.
