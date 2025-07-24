# UiPath Automation Projects
A collection of RPA projects using UiPath Studio.

## Projects Included
### 1️⃣ RPA Challenge
Automates the RPAChallenge.com form filling exercise.

### 2️⃣ IMDb Movie Scraper
Extracts IMDb movie details like name, release date, and rating.

### 3️⃣ ACME System – Calculate Client Security Hash  
**Objective:** Automate WI5 items in ACME System 1 by extracting client data, generating a SHA1 hash, and updating each work item.  
**Key Steps:**  
- Log in using Orchestrator-stored credentials  
- Extract and filter “WI5” work items  
- For each item:  
  - Extract ClientID, ClientName, ClientCountry  
  - Generate hash via SHA1-online.com  
  - Update work item: set status to “Completed” and post hash as a comment  
**Framework & Best Practices:**  
- Built on UiPath REFramework (Init, Get, Process, End states)  
- Configurable via `Config.xlsx` and Orchestrator Assets  
- Includes exception handling, retries, and logging  


## Technologies Used
- UiPath Studio
- Excel, PDFs, Websites (Web scraping)
- Regex, DataTables
- Orchestrator

## Why I Built This
- Practice UiPath core skills: selectors, data scraping, orchestrator.
- Strengthen problem-solving in automation scenarios.

## How to Run
1. Open each project in UiPath Studio.
2. Review dependencies.
3. Run the `Main.xaml`.

## ⚠ Important Note:
For the projects to run correctly, please ensure that the file paths used are updated to reflect your local machine's directories as well as the orchestrator assets.
