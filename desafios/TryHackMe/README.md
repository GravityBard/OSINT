🌸 OhSINT – TryHackMe OSINT Challenge

This challenge is OhSint from TryHackMe. Analyze a single image to extract key data and answer seven questions to unlock the digital badge.

🧩 Challenge Overview

Based on the provided image and HTML, answer:

Avatar: What is this user’s avatar of?

City: Which city is this person in?

SSID: What is the SSID of the WAP they connected to?

Email: What is their personal email address?

Source: On which site did you find their email?

Holiday: Where has the user gone on holiday?

Password: What is the hidden password?


🧠 Step-by-Step Solution

Metadata Extraction

exiftool challenge.jpg

• Found username OWoodflint and GPS: 54°17'41.27" N, 2°15'1.33" W

Username Investigation• Google OWoodflint → Twitter, GitHub, WordPress

Twitter Analysis• Avatar is a cat• BSSID B4:5D:50:AA:86:41 → Wigle.net → London, UnileverWiFi 

GitHub Repository• Found OWoodflint@gmail.com in README.md• Source: GitHub 

WordPress Blog• Holiday destination: New York

Hidden Password• Inspect HTML or select-all reveals pennYDr0pper.! 
