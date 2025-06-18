# Jackett-Indexer-Autoselect

load jackett settings

select "Add Indexer"

enter this text in console:

```
var chs = document.querySelectorAll('.checkboxColumn input[type="checkbox"]');
for (let i = 0; i < chs.length; i++) {chs[i].checked=true;}
```

thanks to @gokhanmeteerturk for profound insight
