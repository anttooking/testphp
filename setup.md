
# Setting up a website

```
sudo nautlius
```
Open flie system


# Link

https://prognotes.net/2016/08/configuring-local-lamp-stack-web-development/

# Configure /etc/apache2/site-available

ServerName testsite
```
ServerAdmin webmaster@localhost
DocumentRoot /home/anthony/Code/phpdev/test
<Directory /home/user/websites/test/>
    Options Indexes FollowSymLinks MultiViews
    AllowOverride All
    Require all granted
</Directory>
```

# Configure Hosts