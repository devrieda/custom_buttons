## Custom Buttons

While browser default buttons are perfectly fine in many instances, there are 
times you want to give your buttons a little more class. Styling buttons to 
behave predictably in all browsers is rather tricky. 

This project contains XHTML/CSS to change the visual style of both the 
`<button>` and `<a>` tag using a *button* class. It aims to use semantically 
correct markup and maintain the various button states (in supported browsers).


## Examples

There are two different button examples -- a round button, and a more 
rectangular button. 

Tested in IE6, IE7, IE8, Safari, Firefox, and Chrome. 

Round Button: 

```
<button type="submit" class="button round_button"><span>Submit</span></button>
<a href="#" class="button round_button"><span>Submit</span></a>
```

Rectangular Button:   
  
```
<button type="submit" class="button rect_button"><span>Submit</span></button> 
<a href="#" class="button rect_button"><span>Submit</span></a>
```  

Add the *primary* class to make a button bolded: 

```
<button type="submit" class="button round_button primary"><span>Submit</span></button>
```

Add the *disabled* class to make a button faded:

```
<button type="submit" class="button round_button disabled"><span>Submit</span></button>
```

## Attribution

A lot of what I've done is based on previous work demoed in these articles, and 
their comments: 

* [How to Make Sexy Buttons with CSS](http://www.oscaralexander.com/tutorials/how-to-make-sexy-buttons-with-css.html)
* [Recreating the Button](http://stopdesign.com/archive/2009/02/04/recreating-the-button.html)
* [Rediscovering the Button Element](http://particletree.com/features/rediscovering-the-button-element/)
* [Syting the Button Element with Sliding Doors](http://www.filamentgroup.com/lab/styling_the_button_element_with_sliding_doors/)


## LICENSE

(The MIT License)

Copyright © 2012 [Derek DeVries](https://github.com/devrieda/)

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without
limitation the rights to use, copy, modify, merge, publish, distribute,
sublicense, and/or sell copies of the Software, and to permit persons
to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
