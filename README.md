# Chosen Readonly
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=VKY8YAWAS5XRQ&lc=CA&item_name=Weston%20Ganger&item_number=chosen_readonly&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHostedGuest" target="_blank" title="Donate"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt="Donate"/></a>

Chosen Readonly is a JQuery plugin that enables the support of the readonly attribute for chosen selects.

# Install

##### Bower
```
bower install chosen-readonly
```

##### NPM
```
npm install chosen-readonly
```

# Usage
```javascript
/* Makes elements readonly if they already have the readonly attribute */
$('select').chosen().chosenReadonly();

/* Sets all elements as readonly */
$('select').chosen().chosenReadonly(true);

/* Remove readonly from all elements */
$('select').chosen().chosenReadonly(false);

/* Anytime you want to trigger the readonly check just run */
$('select').trigger('chosen:updated');
```


# Credits
Created by Weston Ganger - @westonganger

Plugin based off off [this jsFiddle](http://jsfiddle.net/eirc/v2es7L8o/) by @eirc
