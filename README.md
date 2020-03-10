# What is HSTS?

## HSTS: HTTP Strict Transport Security Protocol

HSTS enabled browser won't allow HTTPS enabled website to be accessed over HTTP or broken HTTPS connection. 

Websites with HSTS configured returns Strict-Transport-Security header as response header. Then the browser caches the header, 
default for 30 days, but this can be configured. Also inclusion and exclusion of subdomain can be configured as well.
