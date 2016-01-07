# fail2ban-nginx-botnet

Recently in my nginx log files I've seen an old botnet reappearing and it's been annoying me.

If you see the following in your log files:

POST http://123.249.24.233/POST_ip_port.php HTTP/1.1" 404 570 "http://123.249.24.233/POST_ip_port.phpAccept: */*" "Mozilla/4.0 (compatible; MSIE 9.0; Windows NT 6.1; 125LA; .NET CLR 2.0.50727; .NET CLR 3.0.04506.648; .NET CLR 3.5.21022)

Then this is for you!

So using fail2ban we can now block them.

Copy the file in filter.d/ to your fail2ban filter.d directory and add what is in jail.local to your jail.local file

Simple
