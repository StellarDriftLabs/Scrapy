# Install scrapy <br />
pip3 install scrapy

# The next two commands is not required instead download the spider directly from this repo
# Download the custom spider <br />
wget -O ReconSpider.zip https://academy.hackthebox.com/storage/modules/144/ReconSpider.v1.2.zip

# Unzip it <br />
unzip ReconSpider.zip

# Run Scrapy <br />
python3 ReconSpider.py <http://inlanefreight.com>
