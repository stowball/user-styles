Site: youtube.com

```
// ==UserScript==
// @name         Skip ads button for Youtube
// @namespace    http://tampermonkey.net/
// @version      2024-07-19
// @description  try to take over the world!
// @author       You
// @match        https://www.youtube.com/watch*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=youtube.com
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    setTimeout(() => {
        const container = document.querySelector('#below');
        const ff16 = document.createElement('button');
        ff16.textContent = '16x';
        ff16.style = 'margin-right: 10px; margin-top: 10px;';
        ff16.onclick = () => { document.querySelector('video').playbackRate = 16 };
        container.prepend(ff16);

        const ff10 = document.createElement('button');
        ff10.textContent = '10x';
        ff10.style = 'margin-right: 10px; margin-top: 10px;';
        ff10.onclick = () => { document.querySelector('video').playbackRate = 10 };
        container.prepend(ff10);

        const ff5 = document.createElement('button');
        ff5.textContent = '5x';
        ff5.style = 'margin-right: 10px; margin-top: 10px;';
        ff5.onclick = () => { document.querySelector('video').playbackRate = 5 };
        container.prepend(ff5);

        const ffButton1_75 = document.createElement('button');
        ffButton1_75.textContent = '1.75x';
        ffButton1_75.style = 'margin-right: 10px; margin-top: 10px;';
        ffButton1_75.onclick = () => { document.querySelector('video').playbackRate = 1.75 };
        container.prepend(ffButton1_75);

        const ffButton1_5 = document.createElement('button');
        ffButton1_5.textContent = '1.5x';
        ffButton1_5.style = 'margin-right: 10px; margin-top: 10px;';
        ffButton1_5.onclick = () => { document.querySelector('video').playbackRate = 1.5 };
        container.prepend(ffButton1_5);

        // document.querySelector('.html5-video-player video').addEventListener('play', () => { document.querySelector('video').playbackRate = 1.5 });

        // const config = { attributes: true, childList: true, subtree: true };
        // const callback = (mutationList, observer) => { console.log(mutationList); };
        // const observer = new MutationObserver(callback);
        // // Start observing the target node for configured mutations
        // observer.observe(container, config);
    }, 1000);
})();
```
