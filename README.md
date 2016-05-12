<VirtualHost *:80>
    ServerAdmin caopeng8787@163.com
    DocumentRoot "D:/xampp/htdocs/frontend/web"
    ServerName dev.lancome.com
    <Directory "D:/xampp/htdocs/frontend/web">
        Options Indexes FollowSymLinks
        AllowOverride All
        Order Deny,Allow
        Allow from all
    </Directory>
    ErrorLog "logs/dummy-host2.example.com-error.log"
    CustomLog "logs/dummy-host2.example.com-access.log" common
</VirtualHost>
