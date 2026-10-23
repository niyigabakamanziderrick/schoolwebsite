# Muhanga TVET School Website

A simple, paper-like, one-page website for parents: trades, who is accepted, fees, boarding requirements, notebooks and contact. Copy buttons let parents copy bank account numbers, the boarding list and the phone number.

Built with plain HTML and CSS, plus one small script for the notebook finder. No framework, nothing to install. If the script is off, a plain list of notebooks is shown instead.

## Files

| File | What it does |
|---|---|
| `index.html` | The page and all its content. |
| `style.css` | The look: colours, fonts and spacing. |
| `README.md` | This guide. |

Keep `index.html` and `style.css` in the same folder.

## Page order

1. School name, boarding school, location, year, admissions, contact number (with Copy button)
2. Trades (small cards, L3, L4, L5 as plain text)
3. Check if your student is accepted
4. Documents to bring
5. School fees (one card per term)
6. Banks (Copy button on each account number)
7. Boarding requirements (Copy list button)
8. Notebooks (choose a trade, tap a level, see the number of notebooks)
9. Contact us (with Copy button)

## Design

- Trades list the levels as plain text.
- Only white `#FFFFFF` and black `#000000`. No lines.
- Cards are white and are lifted off the page by a soft shadow. The selected level button is black with white text.
- Headings use Poppins, body text uses Inter (Arial is used offline).
- Copy buttons look like the level buttons. They appear only when JavaScript is on, and show "Copied" for 2 seconds.
- Space between sections grows with the screen (64px phone, 88px tablet, 104px desktop). Change it with `--section-space` at the top of `style.css`.
- Trades: 2 columns on phones, 3 on tablets and desktop. Bank names sit above their numbers on small phones.
- Cards: 1 column on phones, 2 on tablets, 3 on desktop. The notebook finder puts the choices beside the result from 760px.

## How to run it

Double-click `index.html`. It opens in your browser.

## How to change the content

Edit the text in `index.html`, save and refresh. Notebook numbers are in the `books` list in the script at the bottom of `index.html` (and in the plain backup list). Colours and fonts are at the top of `style.css`.

## How to put it online

Upload both files to a static host such as GitHub Pages, Netlify or Cloudflare Pages, with `index.html` in the main folder.
