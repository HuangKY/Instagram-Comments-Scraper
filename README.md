# Instagram Comments Scraper
forked from [AgiMaulana](https://github.com/AgiMaulana/Instagram-Comments-Scraper)

## Install dependencies
`pip install -r requirements.txt`   # or conda install

## Install Chrome Web Driver
Download latest Chrome web driver from https://sites.google.com/a/chromium.org/chromedriver/downloads <br /> <br />
Or if you on Linux/Ubuntu <br />
`wget https://chromedriver.storage.googleapis.com/2.43/chromedriver_linux64.zip` <br /> <br />
Extract the binary then move to `/usr/local/bin/` <br />
`sudo mv chromedriver /usr/local/bin/chromedriver` <br />
`sudo chown root:root /usr/local/bin/chromedriver` <br />
`sudo chmod +x /usr/local/bin/chromedriver` <br /> <br />
[Ref:/usr/bin vs. /usr/local/bin](https://stackoverflow.com/questions/32659348/operation-not-permitted-when-on-root-el-capitan-rootless-disabled)

## Run
`python scraper.py post-url total-load-more-click` <br />
Change the URL with your post target <br />
Example : <br />
`python scraper.py https://www.instagram.com/p/BqUfulwH6O4/ 5`

# License
This project is under the [MIT License](https://github.com/AgiMaulana/instagram-comments-scraper/blob/master/LICENSE.md)

# Other reference
* [Load more comments](https://www.youtube.com/watch?v=yebUIymZJm0)
