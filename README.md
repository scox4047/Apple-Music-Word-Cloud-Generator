# Apple_Music_Word_Cloud_Generator
Python scripts to create word cloud from Apple Music Replay, Playlists, Albums, etc

Currently, full scripts (from webscraping to word cloud generation) only exist for Replay and Playlist URLs. 

### Dependencies
I first used BeautifulSoup for webscraping, but the dynamic Apple Music web pages caused it to fail. I am in the process of updating the scripts with Selenium. 
Current webscraping uses Selenium, a package for scraping dynamic web pages. A dependency of Selenium is ChromeDriver, an open source tool for automated testing of webapps across many browsers. ChromeDriver can be downloaded from [here](https://sites.google.com/chromium.org/driver/home?authuser=0).
The path to your ChromeDriver executable must be inserted into the scripts along with the Apple Music URLs. 
