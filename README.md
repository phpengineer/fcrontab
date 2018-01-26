# fcrontab

# 安装步骤 
- tar xzvf fcron-3.2.1.src.tar.gz
- cd fcron-3.2.1
- ./configure --prefix=/usr --sysconfdir=/etc --without-sendmail
- make
- make install

# 编辑任务 
- fcrontab -e

# 任务格式写法 
- documention http://fcron.free.fr/doc/en/fcrontab.5.html
- example: @ 1s cd /data/www  && /usr/local/php/bin/php test.php > /tmp/test.log 2>&1

