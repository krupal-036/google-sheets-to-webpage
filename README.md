# Google Sheets to webpage data fetcher

This project fetches data from a Google Sheets spreadsheet and displays it in a webpage using HTML, JavaScript, and CSS.

## Steps Before Using This Code

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/krupal-036/google-sheets-to-webpage.git
   ```
2. Navigate to the project folder:
   ```sh
   cd google-sheets-to-webpage.git
   ```

### 1. Get Your Google Sheets ID
- Open your Google Sheet and copy the **Spreadsheet ID** from the URL:
  ```
  https://docs.google.com/spreadsheets/d/SPREADSHEET_ID/edit
  ```
- Example: If the URL is:
  ```
  https://docs.google.com/spreadsheets/d/1AbCDEFGHIJKLMNOPQRST/edit
  ```
  Then, your **Spreadsheet ID** is:
  ```
  1AbCDEFGHIJKLMNOPQRST
  ```

### 2. Enable Google Sheets API and Get API Key
- Go to [Google Cloud Console](https://console.cloud.google.com/)
- Create a new project
- Go to **APIs & Services → Enable APIs**
- Search for **Google Sheets API** and enable it
- Go to **Credentials → Create API Key**
- Copy your **API Key**


## 🔹 How This Works

- Fetches **live data** from Google Sheets API using `fetch()`
- Parses the **JSON response** from Google Sheets
- Dynamically updates the **table** with data
- Handles **errors** (Invalid API Key, incorrect Spreadsheet ID, etc.)

## 🔹 Next Steps

1. Replace **`YOUR_SPREADSHEET_ID`** with your **Google Sheet ID**
2. Replace **`YOUR_GOOGLE_API_KEY`** with your **API Key**
3. Save the file as **`index.html`** and open it in a browser

## 🚀 Deployment
You can host this webpage on GitHub Pages, Netlify, or Vercel for live updates.

---

This project can fetch and display **real-time data** from your Google Sheet! 🎉

For any issues, feel free to ask [Krupal](mailto:krupalfataniya007@gmail.com). 😊