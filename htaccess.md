## Redirect only domain
```
<IfModule mod_rewrite.c>
RewriteEngine On
RewriteCond %{QUERY_STRING} =""
RewriteRule ^$ https://solution.printcart.com/ [L,R=301]
</IfModule>

# BEGIN WordPress
```

---