# SteamSight by Cesferort

⚠️ **Note:** SteamSight is currently in development. Features may be incomplete or change frequently.

**SteamSight** is a free Google Chrome extension that enhances and customizes your Steam wishlist by adding powerful filters and handy options.

## Features
- **Filter games** by average playtime (from How Long To Beat), prices from various stores (via CheapShark), and more
- **Sort your wishlist** according to your favourite criteria
- **Visual customization** of your wishlist, making it easier to browse and organize


## Installation

### A - Manual Installation (for developers / testers)
1. Download or clone this repository:  
	```bash
	git clone https://github.com/Cesferort/SteamSight.git
	``` 
  
2. Create a proxy server to handle requests. For example, you can use Render, live-server or any proxy tool you prefer

3. Update the references in the extension code to point to your proxy URL
	```javascript
	// content.js
	const SERVER_URL = "YOUR_PROXY_URL";
	```

4. Open Chrome and go to the [Chrome extensions page](chrome://extensions/)

5. Enable **Developer Mode** (toggle in the top right)

6. Click **Load unpacked** and select the folder containing SteamSight

7. Open your Steam wishlist to start using the filters and customization options

### B - Automatic Installation (for general users)
1. Visit the Chrome Web Store page for SteamSight

2. Click **Add to Chrome**

3. Confirm any prompts and the extension will install automatically

4. Open your Steam wishlist to start using the filters and customization options