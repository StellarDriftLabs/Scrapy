#Install scrapy
pip3 install scrapy

#Download the custom spider
wget -O ReconSpider.zip https://academy.hackthebox.com/storage/modules/144/ReconSpider.v1.2.zip

#Unzip it
unzip ReconSpider.zip

#Run Scrapy
python3 ReconSpider.py <http://inlanefreight.com>
