# Crypto-Price-Alert-Agent-
<img width="959" height="603" alt="Screen Shot 2025-08-29 at 5 38 00 PM" src="https://github.com/user-attachments/assets/d6bc1534-910d-464a-bf3b-08b3493279ba" />



## Overview
This project is a **single-page web app** that acts as a **Crypto Price Alert Agent**.  
It fetches live cryptocurrency prices (BTC and ETH) from the **CoinGecko API** and continuously monitors price changes.  
If the price moves **more than 2%** (up or down) since the last check, it highlights the price in **green (increase)** or **red (decrease)**.

## Features
- **Live Data**: Uses the CoinGecko API for real-time crypto prices.  
- **Automation**: Checks prices automatically every 30 seconds.  
- **Visual Alerts**: Displays alerts with color-coded highlights (green for up, red for down).  
- **Lightweight**: Entire project runs from a single `index.html` file on GitHub Pages.  
- **No Setup Needed**: Works directly in the browser — no backend or local installation required.

## How It Works
1. The app loads in your browser.  
2. Every 30 seconds, it fetches the latest BTC and ETH prices from the CoinGecko API.  
3. It compares the new price to the previous price.  
4. If the price has moved more than 2%, the text color changes:  
   - **Green** = price increased  
   - **Red** = price decreased  
5. The prices update automatically without refreshing the page.

## Live Demo
**BRING ME TO LIFE HERE**
https://pritiks23.github.io/Crypto-Price-Alert-Agent-/

## Files
- **index.html** → Contains all the HTML, CSS, and JavaScript in a single file.

## Tech Stack
- **HTML** for structure  
- **CSS** for styling  
- **JavaScript (Fetch API)** for data retrieval and logic  
- **CoinGecko API** for real-time crypto price data

## Example Use Case
This project demonstrates **automation in market monitoring**.  
Traders and enthusiasts can use it as a starting point for creating real-time alerts or dashboards.

## License
This project is open-source under the MIT License.
