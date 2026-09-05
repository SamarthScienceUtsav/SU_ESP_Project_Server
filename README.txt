API KEY SERVER

1. Open env.js.
2. Replace PASTE_YOUR_GEMINI_API_KEY_HERE with the required API key.
3. Upload index.html and env.js to the same web directory.
4. When the key changes, edit and upload only env.js. Clear the CDN/server cache if needed.

The page no longer contains an API-key input. It reads and displays the value from env.js on every device.

SECURITY WARNING
env.js is a public browser file. Anyone who can access the website can read the API key, even if the page uses a PIN. Use a provider-restricted key only. A secure production solution requires a server-side proxy that never sends the secret key to visitors.
