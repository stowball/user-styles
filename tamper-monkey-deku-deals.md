Site: dekudeals.com

```
// ==UserScript==
// @name         Deku Deals Show Original Price
// @namespace    http://mattstow.com/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        https://www.dekudeals.com/items/*
// @icon         https://www.google.com/s2/favicons?domain=dekudeals.com
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    const { data } = JSON.parse(document.getElementById('price_history_data').innerHTML);
    const prices = data.map(price => price[2]);
    const maxPrice = Math.max(...prices).toFixed(2);
    const currPrice = prices[prices.length - 1].toFixed(2);

    if (maxPrice != currPrice) {
        document.querySelector('.item-price-table .btn').innerHTML = `<span class="mr-2 text-dark">$${maxPrice}</span> ${document.querySelector('.item-price-table .btn').innerHTML}`;
    }
})();
```
