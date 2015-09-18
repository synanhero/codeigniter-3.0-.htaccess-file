# codeigniter-.htaccess-file

this is a useful htaccess file for codeigniter 3.0

.htaccess file coded based on https://gtmetrix.com/ results . 

1- it removes index.php from url. You must also change this line 
`$config['index_page'] = '';` on config file

2- Adds expires dates for cached files

3- Enables Gzip for html|txt|css|js|php|pl files

4- Also Output filters for .php and .js files 

5- removing index.php works fine also in shared hostings like godady etc

Thanks 
