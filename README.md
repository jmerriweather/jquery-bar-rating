jQuery Bar Rating Plugin
========================

Minimal, light-weight jQuery ratings.

How to use
----------

Examples of use are here:

[http://netboy.pl/demo/jquery-bar-rating/examples/](http://netboy.pl/demo/jquery-bar-rating/examples/)

How to run tests
----------------

```
git clone https://github.com/netboy/jquery-bar-rating
cd jquery-bar-rating
npm install
./node_modules/mocha/bin/mocha -R spec

  bar rating plugin on init with custom options
    ✓ should update defaults 

  bar rating plugin on show
    ✓ should have data 
    ✓ should transform the select field into a rating widget 
    ✓ should store rating values in data attributes 
    ✓ should read the selected rating from the select field 
    ✓ should set correct class 
    ✓ should append a rating div 
    ✓ should display a correct rating 
    ✓ should hide the select field 

  bar rating plugin on show and rating selected
    ✓ should update data 
    ✓ should set correct class 
    ✓ should display a correct rating 
    ✓ should pass correct values to a callback 

  bar rating plugin on deselect
    ✓ should update data 
    ✓ should successfully deselect rating 

  bar rating plugin on clear
    ✓ should restore original rating 
    ✓ should set correct class 

  bar rating plugin on destroy
    ✓ should remove data 
    ✓ should show the select field back again 


  ✔ 19 tests complete (515 ms)


```

License
-------

Dual licensed under the MIT and GPL licenses:<br />
[http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)<br />
[http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)