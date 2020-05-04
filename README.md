# updateCrypto

updateCrypto.py - a utility for updating an .xlsx file which contains
a portfolio of crypto currencies.

By Colin Trierweiler.  Released under the GNU GPL

This is a proof-of-concept, version 0.1, so to speak, but it works!

It works by scraping all the h4 HTML tags off of Coinbase's price page
and using certain indices to match certain currencies.  These indicies
start at 3 for BTC, and then go up by 7 from there.  For the time being
it will only work with the included CryptoPortfolio.xlsx spreadsheet.

Future improvements will include:
 * Turning the scrape part into a function
 * Allowing for more customization of the contents of the portfolio
 * Turning it into a command line argument with an optional filename
