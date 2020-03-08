# Twitter Word Cloud

A tool to generate word cloud images from twitter user timeline.

# Requirements :

- <a href="https://github.com/twintproject/twint">TWINT - Twitter Intelligence Tool</a>
- <a href="https://github.com/sobhe/hazm">Hazm</a>
- <a href="https://github.com/amueller/word_cloud">Word Cloud generator</a>
- <a href="https://github.com/pandas-dev/pandas">Pandas</a>

# how to run :
- `apt-get install python3-pip python3-venv`
- `python3 -m venv venv`
- `source venv/bin/activate`
- `pip3 install --upgrade pip`
- `pip3 install -r requirements.txt` (Install dependencies)
- `python3 twc.py -u twitter_username` - Scrape all the Tweets from user's timeline and genarate word cloud images. You can find images in this path `output/twitter_username/`.
- `python3 twc.py -u twitter_username -c 100` - Scrape all the Tweets from user's timeline and genarate word cloud images with 100 words.
- `python3 twc.py -u twitter_username -f "XB Zar.ttf"` - Scrape all the Tweets from user's timeline and use "XB Zar.ttf" font on the image. Yon can find fonts in the `fonts` folder.

# Sample Output:

![Sample Result](irLinja.png?raw=true)
