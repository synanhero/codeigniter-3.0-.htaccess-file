# codeigniter 3.0 .htaccess file

**1.htaccess**
this is a useful .htaccess file for codeigniter 3.0

.htaccess file coded based on https://gtmetrix.com/ results . 

* you can use codeigniter with or without index.php in url. You must also change this line 
`$config['index_page'] = 'index.php';` to this=> `$config['index_page'] = '';`  on config file

* Adds expires dates for cached files

* Enables Gzip for html|txt|css|js|php files

* Also Output filters for .php and .js files 

* removing index.php works fine also in shared hostings like godady etc

**2.htaccess**

 * Working on Plesk Panel


Thanks 
