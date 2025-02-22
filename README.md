# YouTube Shorts Auto-Browser Script

This is a cool little script that uses Selenium to log into YouTube and take you straight to the YouTube Shorts page. It also scrolls through the feed, so you can just kick back and watch some Shorts without lifting a finger!

## What It Does

- **Logs You In**: Automatically enters your Google account details to get you logged into YouTube.
- **Takes You to Shorts**: After logging in, it zips you over to the YouTube Shorts page.
- **Scrolls for You**: Scrolls through the Shorts feed, so you don’t have to keep swiping.

## How to Get Started

Set Up ChromeDriver:
Download ChromeDriver from the official site. Place it somewhere easy to find and update the path in the script where it says path/to/chromedriver.

Add Your Details:
Open up the script and swap out youremail@gmail.com and yourpassword with your own Google account info.

Install What You Need:
Make sure you’ve got Python and Selenium installed. Install Selenium with:

bash
Copy code
pip install selenium
Run the Script:
bash
Copy code
python script.py
Extra Tips
Keep Your Info Safe: For better security, use environment variables or a config file for your credentials instead of putting them right in the script.
Tweak It: Feel free to adjust the wait times and scroll amount to fit your own browsing habits.

### Clone the Repo:
```bash
git clone https://github.com/yourusername/repository.git
