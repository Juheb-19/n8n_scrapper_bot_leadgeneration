n8n Scraper & Cold Outreach Bot (Public Edition)
This repository contains a lightweight version of an automated lead scraping and outreach system built using n8n. It helps solo entrepreneurs, freelancers, and indie hackers collect business leads and begin outreach in minutes.

🚀 Features
✅ Scrape startup data from IndieHackers (public HTML pages)
✅ Scrape agency listings from Clutch.co
✅ Connect to Google Sheets to store scraped leads
✅ Includes a basic Cold Email Bot that reads new leads and sends outreach emails
❗ Advanced bots (LinkedIn, Fiverr, Upwork integrations, auto-tagging, PhantomBuster, full LLM support) have been removed in this public version.

📁 Included Workflows (JSON)
Workflow Name	Description
indiehackers_scraper.json	Scrapes IndieHackers startup directory
clutch_scraper.json	Scrapes Clutch.co agency listing pages
cold_outreach_emailer.json	Reads Google Sheet → Sends email → Updates status
🛠 Requirements
A running n8n instance (local or cloud)
A Google Sheet with this header:
Name,Role,Email,Website/Profile,Source,Status,Notes
Google Sheets API credentials
🔧 Setup
Clone or download this repo
Import the .json files into your n8n instance
Create a Google Sheet named n8n_lead_scraper_outreach_db
Connect your Google account in n8n credentials
Update node settings with your custom URL or queries
📬 For Personalization
Want full access to advanced versions (LinkedIn, Fiverr, Upwork scraping, LLaMA scoring, Supabase sync, etc)?

👉 For personalization contact the author

📄 License
MIT License

🤝 Contributing
Pull requests are welcome for new source scrapers or sheet integrations.

🧑‍💻 Author
Juheb Mahmud
Automation Engineer | Indie Maker | AI+NoCode Solutions
