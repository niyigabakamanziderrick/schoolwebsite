HEAD

# schoolwebsite

A school website in Rwanda that helps parents view information to arrive at school well prepared

# Muhanga TVET School Website

A simple, paper-like, one-page website for parents: trades, who is accepted, fees, boarding requirements, notebooks and contact.

Built with plain HTML and CSS, plus one small script for the notebook finder. No framework, nothing to install. If the script is off, a plain list of notebooks is shown instead.

## Files

| File | What it does |

`index.html` The page and all its content. |
`style.css` The look: colours, fonts and spacing. |
`README.md` This guide. |

Keep `index.html` and `style.css` in the same folder.

## Page order

1. School name, boarding school, location, year, admissions
2. Trades (L3, L4, L5 as plain text on each card)
3. Check if your student is accepted
4. Documents to bring
5. School fees (one card per term)
6. Banks
7. Boarding requirements
8. Notebooks (choose a trade, tap a level, see the number of notebooks)
9. Contact us

## Design

Trades list the levels as plain text.
Only white `#FFFFFF` and black `#000000`. No lines.
Cards are white and are lifted off the page by a soft shadow. The selected level button is black with white text.
Headings use Poppins, body text uses Inter (Arial is used offline).
Cards: 1 column on phones, 2 on tablets, 3 on desktop. The notebook finder puts the choices beside the result from 760px.

## How to run it

Double-click `index.html`. It opens in your browser.

## How to change the content

Edit the text in `index.html`, save and refresh. Notebook numbers are in the `books` list in the script at the bottom of `index.html` (and in the plain backup list). Colours and fonts are at the top of `style.css`.
