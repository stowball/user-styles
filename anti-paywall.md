Site: nytimes.com

```
/* nytimes.com */
.nytapp-vi-article #app > div > [class*="css-"] {
    position: static;
}

.nytapp-vi-article #app > div > [class*="css-"] > div[aria-hidden="true"] + [class*="css-"],
.nytapp-vi-article #app #gateway-content {
    display: none;
}

[data-premium="false"] .overlay {
    display: none !important;
}
```
