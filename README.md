cd YouTube-Viewer
python3 -m pip install --upgrade pip wheel
pip3 install "setuptools<59"
pip3 install -r requirements.txt

ps aux | awk '/chrome/ { print $2 } ' | xargs kill -9
python3 V.py
https://www.sslproxies.org/


referers = [
'https://amatechx3.blogspot.com/'
,'https://duckduckgo.com/'
,'https://www.google.com/'
,'https://www.bing.com/'
,'https://t.co/'
,'https://search.yahoo.com/'
,'https://www.google.com'
,'https://www.youtube.com'
,'https://www.facebook.com'
,'https://www.baidu.com'
,'https://www.yahoo.com'
,'https://www.amazon.com'
,'https://www.wikipedia.org'
,'https://www.qq.com'
,'https://www.twitter.com'
,'https://www.google.co.in'
,'https://www.live.com'
,'https://www.taobao.com'
,'https://www.google.co.jp'
,'https://www.sina.com.cn'
,'https://www.bing.com'
,'https://www.instagram.com'
,'https://www.linkedin.com'
,'https://www.weibo.com'
,'https://www.yahoo.co.jp'
,'https://www.msn.com'
,'https://www.google.de'
,'https://www.vk.com'
,'https://www.hao123.com'
,'https://www.yandex.ru'
,'https://www.google.co.uk'
,'https://www.reddit.com'
,'https://www.ebay.com'
,'https://www.google.fr'
,'https://www.google.ru'
,'https://www.t.co'
,'https://www.pinterest.com'
,'https://www.tmall.com'
,'https://www.google.com.br'
,'https://www.amazon.co.jp'
,'https://www.netflix.com'
,'https://www.mail.ru'
,'https://www.360.cn'
,'https://www.sohu.com'
,'https://www.gmw.cn'
,'https://www.google.it'
,'https://www.google.es'
,'https://www.microsoft.com'
,'https://www.paypal.com'
,'https://www.chinadaily.com.cn'
,'https://www.tumblr.com'
,'https://www.wordpress.com'
,'https://www.blogspot.com'
,'https://www.imgur.com'
,'https://www.naver.com'
,'https://www.github.com'
,'https://www.stackoverflow.com'
,'https://www.apple.com'
,'https://www.aliexpress.com'
,'https://www.google.com.mx'
,'https://www.imdb.com'
,'https://www.google.co.kr'
,'https://www.whatsapp.com'
,'https://www.163.com'
,'https://www.fc2.com'
,'https://www.google.com.hk'
,'https://www.jd.com'
,'https://www.google.ca'
,'https://www.youth.cn'
,'https://www.ok.ru'
,'https://www.amazon.in'
,'https://www.xhamster.com'
,'https://www.blogger.com']
