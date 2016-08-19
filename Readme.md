#### Humdrum Grill

A weekend project by Will Johnson and Jenna Rajani.

## Live on Surge at: http://williamjohnsonjr-humdrumgrill.surge.sh

Will Johnson: https://github.com/WilliamJohnsonJr

Jenna Rajani: https://github.com/jjrajani

##Tools used:
HTML, Sass/SCSS, JavaScript, jQuery, AJAX, ES6.

# **Need to Style `read more>` into the end of latest news `<p>`**

##### javaScript Tools
* Used `$.ajax()` to pull images from flickr
* Used `.addClass` and `.removeClass` to add 'accordion' affect to the menu nav.

##### CSS Tools
* Used to cut off text and add "..." to end of latest news paragraph.
  ``` CSS
  display: -webkit-box;
  
  -webkit-line-clamp: 9;
  
  -webkit-box-orient: vertical;
  
  text-overflow: -o-ellipsis-lastline;
  ```