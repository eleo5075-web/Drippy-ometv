# Drippy-ometv
Gets the other user's public IP and looks up their approximate location using the IPGeolocation API. Shows the country, city, ISP, timezone, and a snapshot in a floating panel.

This script adds a panel to OmeTV that waits until you connect with someone. When it detects the other person's public IP through the WebRTC connection, it uses your IPGeolocation API key to look up approximate information like their country, city, region, ISP, language, coordinates, and time zone, then displays it in the panel. It also captures a snapshot of the other person's video once it's available.

To use it, create a free account at IPGeolocation and copy your API key. Open the script, find `let apiKey = "";`, and replace the empty quotes with your key. Then open OmeTV in your browser, press **F12**, go to the **Console** tab, paste the entire script, and press **Enter**. Once you connect to someone, the panel will automatically show any information it can retrieve. The location is only an estimate based on the detected public IP, so it may not always be accurate, and if OmeTV changes how it handles connections, some features may stop working.
