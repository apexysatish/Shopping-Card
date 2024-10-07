# Shopping-Card Plug-in

![Screenshot](https://raw.githubusercontent.com/sattuvirus/Shopping-Card/master/screenshot.gif)

This is shopping card type plugin.In this plugin there 16 types of buttons color which you have change according to your application.

In this Shopping-Card , Below 16 color classes added for button you can change button colors that you can use in your sql query.
```
blue-btn ,
red-btn ,
ruby-btn, 
dark_orchid-btn ,
purple-btn,
speech_blue-btn,
dodger_blue-btn,
deep_sky_blue-btn,
iris_blue-btn,
dark_cyan-btn,
yellow-btn,
orange-btn,
steel_teal-btn,
pink-btn
```

When you use these Dashboard plugin in Apex, below sql query will help to create sample Dashboard.
```
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'blue-btn' as BUTTON_CLASS,
    'red-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
union all
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'ruby-btn' as BUTTON_CLASS,
    'dark_orchid-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
union all
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'purple-btn' as BUTTON_CLASS,
    'speech_blue-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
    union all
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'dodger_blue-btn' as BUTTON_CLASS,
    'deep_sky_blue-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
    union all
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'iris_blue-btn' as BUTTON_CLASS,
    'dark_cyan-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
    union all
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'yellow-btn' as BUTTON_CLASS,
    'orange-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
    union all
select
    'fa-heart-o' AS ICON2,
    '#' AS LINK,
    'Asus X552CL-SX019D Laptop' AS PRODUCT_NAME,
    'https://www.91-img.com/pictures/laptops/asus/asus-x552cl-sx019d-core-i3-3rd-gen-4-gb-500-gb-dos-1-gb-61721-large-1.jpg' AS PRODUCT_IMAGE,
    'fa-inr' as ICON,
    '32000' AS PRODUCT_PRICE_MAIN,
    '50000' AS PRODUCT_PRICE_PRE,
    'steel_teal-btn' as BUTTON_CLASS,
    'pink-btn' as BUTTON_CLASS2,
    '#' AS ADD_TO_CART_LINK,
    '#' AS BUY_LINK
from
    DUAL
```
<b>Note:-In the Latest Verison Please use below CSS code in your page.</b>
```
.apex-row {
     display: block;
     flex-wrap: wrap; 
}
```	
For working Demo just click on:
<a href ="https://apex.oracle.com/pls/apex/f?p=140847:6"> <h4>Demo</h4></a>

If you like my stuff, Please Like share and comment.

