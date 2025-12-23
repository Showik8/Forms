📜 Mission: The Crypto Ledger Architect
Mission Name: ₿ Mission: Digital Asset Visualization
Theme: Fintech & Cryptocurrency Dashboard
Difficulty: Intermediate | Tech Stack: HTML5 (Tables, Semantics) & CSS3 (Flexbox, Dark Mode)
Welcome, Developer!

The Global Digital Exchange has requested a new interface to track the world's most valuable crypto assets. Your task is to build a high-performance, visually sharp Crypto Market Dashboard. Accuracy is key—in the world of finance, a misplaced decimal or a broken table row can cost billions!

Your Goal: Build a complete HTML document representing a real-time crypto market, using structured tables and professional styling to ensure data clarity.

Phase 1: The Digital Foundation (Structure)
Create the standard HTML skeleton: <!DOCTYPE html>, <html>, <head>, and <body>.

Inside the <head>, set the <title> to: Crypto Market Dashboard: Live Quotes.

Warning: Ensure you link your external stylesheet using <link rel="stylesheet" href="style.css"> before moving to the content.

Phase 2: Mapping the Market (Semantics)
Header: Create a <header> containing an <h1> with the text: "Global Market Overview".

Navigation: Add a <nav> with links pointing to internal IDs: #market, #stats, and #settings.

Main Content: Use the <main> tag to wrap your primary data table.

Aside: Create an <aside> representing a "Breaking News" ticker. Inside, add a <p> about a sudden Bitcoin price surge.

Footer: Add a <footer> with the exchange’s copyright information.

Phase 3: The Asset Ledger (Formatting & Tables)
Inside a <section> with id="market":

Magical Table: Create a <table> to display the assets:

Use <thead> for headers: Asset Name, Price, 24h Change, Market Cap.

Use <tbody> with at least 5 rows of data (BTC, ETH, etc.).

Data Formatting: Use the following tags within your table cells:

<strong> for the Price values.

<em> for the asset Ticker (e.g., BTC).

<mark> to highlight the Top Gainer of the day.

<span class="positive"> or <span class="negative"> for the percentage changes.

Iconography: Add a small <img> or a stylized <span> for each coin logo next to the name.

Phase 4: Exchange Statistics (Lists)
Inside a <section> with id="stats":

Unordered List: Create a <ul> listing 3 active trading pairs (e.g., BTC/USDT).

Ordered List: Create an <ol> listing the top 3 exchanges by volume.

Description List: Use a <dl> to define crypto terms (e.g., <dt>HODL</dt> -> <dd>Holding an asset for the long term</dd>).

Phase 5: Visual Evidence (Multimedia)
Inside a <section> with id="evidence":

Iframe: Embed a YouTube video or a TradingView widget showing a live price chart.

External Link: In the footer, add a link to "CoinMarketCap." It must open in a new tab (target="\_blank").

✨ The Finale: The Professional Gloss (CSS)
Once your HTML structure is solid, apply these CSS rules to your style.css to achieve the "Dark Mode" look:

Background: Set the body background to #0b0e11 (Binance Dark).

Typography: Use font-family: 'Inter', sans-serif; for a clean, modern look.

Table Styling: \* Set border-collapse: collapse; for the table.

Add a subtle border-bottom to each tr using #2b2f36.

Apply .positive { color: #0ecb81; } and .negative { color: #f6465d; }.

Interactivity: Add a hover state to rows: tr:hover { background-color: #1e2329; }.

✅ Checklist for Success:
[ ] Semantic tags (header, nav, main, aside, footer) are correctly placed.

[ ] The table is properly structured with thead, tbody, and data cells.

[ ] Both positive (green) and negative (red) price indicators are styled.

[ ] All three list types (ul, ol, dl) are implemented.

[ ] External links open in a new tab for a better user experience.

[ ] The CSS link is active, transforming the raw HTML into a pro dashboard.
