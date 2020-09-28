
# Setting up a website

```
sudo nautlius
```
Open file system with admin rights on Ubuntu

Chown could be used for permissions


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

```
etc\hosts
```

Add a line such as 

```
127.0.0.1 mySiteName 
```



# Useful Links

https://prognotes.net/2016/08/configuring-local-lamp-stack-web-development/
