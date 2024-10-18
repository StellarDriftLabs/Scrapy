#Install scrapy__
pip3 install scrapy

#Download the custom spider__
wget -O ReconSpider.zip https://academy.hackthebox.com/storage/modules/144/ReconSpider.v1.2.zip

#Unzip it__
unzip ReconSpider.zip

#Run Scrapy__
python3 ReconSpider.py <http://inlanefreight.com>
