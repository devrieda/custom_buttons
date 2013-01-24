## Custom Buttons

While browser default buttons are perfectly fine in many instances, there are 
times you want to give your buttons a little more class. Styling buttons to 
behave predictably in all browsers is rather tricky. 

This project contains HTML/CSS to change the visual style of both the 
`<button>` and `<a>` tag using a *button* class. It aims to use semantically 
correct markup and maintain the various button states (in supported browsers).


## Examples

There are two different button examples -- a large and small button.

Tested in IE6, IE7, IE8, Safari, Firefox, and Chrome. 

Large Button: 

```
<button type="submit" class="button large_button"><span>Submit</span></button>
<a href="#" class="button large_button"><span>Submit</span></a>
```

Small Button:   
  
```
<button type="submit" class="button small_button"><span>Submit</span></button> 
<a href="#" class="button small_button"><span>Submit</span></a>
```  

Add the *primary* class to make a button bolded: 

```
<button type="submit" class="button large_button primary"><span>Submit</span></button>
```

Add the *disabled* class to make a button faded:

```
<button type="submit" class="button large_button disabled"><span>Submit</span></button>
```

## Attribution

A lot of what I've done is based on previous work demoed in these articles, and 
their comments: 

* [How to Make Sexy Buttons with CSS](http://www.oscaralexander.com/tutorials/how-to-make-sexy-buttons-with-css.html)
* [Recreating the Button](http://stopdesign.com/archive/2009/02/04/recreating-the-button.html)
* [Rediscovering the Button Element](http://particletree.com/features/rediscovering-the-button-element/)
* [Syting the Button Element with Sliding Doors](http://www.filamentgroup.com/lab/styling_the_button_element_with_sliding_doors/)


## LICENSE

Copyright (c) 2012 Derek DeVries

Released under the [MIT License](http://www.opensource.org/licenses/MIT)
