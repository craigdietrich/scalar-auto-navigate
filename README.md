# Scalar, Omeka, and Omeka-S Auto-navigate
If you're using this file in conjuction with CommonPlace, follow the instructions below. When encountering a project URL, CommonPlace will look for the plugin in each platform's respective folder.

## Scalar  
Place **index.html** into a new folder at:  
  
**(scalar root)/system/application/plugins/auto-navigate/**  

Point to this URL in your browser:  
  
**http://<span></span>path/to/scalar/system/application/plugins/auto-navigate/index.html?book=(book URL Segment)**  

Example:  
http://scalar.usc.edu/works/system/application/plugins/auto-navigate/index.html?book=guide2
  
## Omeka
Place **index.html** into a new folder at:  
  
**(omeka root)/plugins/AutoNavigate/**  
  
Point to this URL in your browser:  
  
**http://<span></span>path/to/omeka/plugins/AutoNavigate/index.html**  

Example:  
http://craigdietrich.com/omeka/plugins/AutoNavigate/index.html

## Omeka-S
Place **index.html** into a new folder at:  
  
**(omeka-s root)/modules/AutoNavigate/**  
  
Point to this URL in your browser:  
  
**http://<span></span>path/to/omeka/modules/AutoNavigate/index.html** (all sites)  
or  
**http://<span></span>path/to/omeka/modules/AutoNavigate/index.html?site=(site URL Segment)** (a single site)  
 
Example:  
http://specialcollections.oxycreates.org/equitydiversity/modules/AutoNavigate/index.html?site=/equitydiversity/s/oxy-united-for-black-liberation
