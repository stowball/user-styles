Site: bricklink.com

```
const want = $$('.wl-col-quantity > .wl-hover-editable:first-of-type').reduce( (acc, curr) => acc + Number(curr.innerText.replace(/Want: -?/, '')), 0);
const have = $$('.wl-col-quantity > .wl-hover-editable:last-of-type').reduce( (acc, curr) => acc + Number(curr.innerText.replace(/Have: -?/, '')), 0);
console.log('Want:', want);
console.log('Have:', have);
console.log('Need:', want - have);
```
