# ESP8266 PM2230 GitHub Dashboard

This is a simple GitHub Pages dashboard to view ESP8266 + PM2230 data uploaded via GitHub API.

## How to use

1. Update your ESP8266 firmware to upload data to:
   ```
   https://api.github.com/repos/your-username/esp8266-dashboard/contents/data/data.json
   ```

2. Replace the `your-username` in `dashboard.html` with your GitHub username.

3. Deploy this on GitHub Pages:
   - Go to your GitHub repo > Settings > Pages
   - Choose the branch and root (or `/docs` folder)
   - Access: `https://your-username.github.io/esp8266-dashboard/dashboard.html`

4. View your live data 🎉
