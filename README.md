# Intrepid Browser Bot Distribution

This repository contains the distribution of the **Intrepid Browser Bot**, a desktop automation tool for processing orders and syncing data to Google Sheets.

## Features

- **Order Adjustment Sync** — Automatically reads order data, processes invoice adjustments, and writes results back to Google Sheets.
- **SKU Detail Extraction** — Extracts product SKU, quantity, and selling price from each order and writes them to a dedicated sheet tab.
- Simple, user-friendly interface with dark/light theme support.
- AI-assisted data extraction via Google Gemini and Groq.
- Multi-venture and multi-account support.

## Installation & Usage

1. Go to the [Releases](https://github.com/hatuanduchcm/intrepid-browser-bot-dist/releases) page and download the latest `IntrepidBrowserBot.zip`.
2. Extract the zip to any folder, then run `IntrepidBrowserBot.exe`.
3. Click the **Settings** (⚙) button and fill in:
   - **Connection**: Google Sheet URL or ID, and your Service Account key.
   - **Order Adjustment / SKU Detail**: Sheet tab names and column names matching your spreadsheet.
   - **Accounts**: Intrepid login credentials per venture.
   - **AI**: Gemini and/or Groq API key for SKU extraction.
4. Click **Save**, then press **▶ Run** to start the bot.

The bot will process rows automatically and update the status columns in your Google Sheet when done.

## Updates

When a new version is available, the bot will notify you on startup. Click **Update now** to download and apply the update automatically.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact [hatuanduc@gmail.com](mailto:hatuanduc@gmail.com).
