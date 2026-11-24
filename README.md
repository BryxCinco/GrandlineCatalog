# Grandline Catalog

A redesigned, single-page website concept for **Grandline Maritime Training & Development Center Inc.** (Ermita, Manila), with the full course catalogue.

## Features

- **Course catalogue:** 139 STCW and in-house courses in 12 labelled categories, each with a description, duration, schedule and price.
- **Course finder:** live search (name, code or description), category filters, an STCW / In-house switch and sorting by name, price or duration.
- **Enquiry shortlist:** add courses, see an estimated total and send a pre-filled enquiry email.
- **Visit us:** embedded Google map (map / satellite), directions via Google Maps or Waze, and step-by-step guidance to the office.
- **Design:** colors and type based on the Grandline logo, with animated ships sailing in the background.
- **Responsive and accessible:** works on phones, tablets and desktops. Keyboard navigation, screen-reader labels and reduced-motion support are built in.

## Run locally

It's a static site with no build step. Open `index.html` in a browser, or serve the folder:

```bash
npx http-server . -p 5173
```

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles, scripts and course data |
| `logo.png` | Original Grandline logo |
| `logo-mark.png` | Logo emblem only (ship and wave), transparent background |

## Notes

- Course names, durations and prices come from the current grandline-maritime.com courses and prices pages. Prices may change, so confirm them with the office.
- The course descriptions are drafts and need to be reviewed by the training office before publishing.
