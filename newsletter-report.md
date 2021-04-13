


```
document.querySelectorAll('table#contentTable, htmlTrackingDisplayContainer, #oDoc, #dataContainerNoScroll').forEach((x) => x.style.height = '2600px'); 
 
const dateSent = document.querySelector("td.pageTitleCenter > table > tbody > tr > td > table > tbody > tr > td > table > tbody > tr:nth-child(4) > td:nth-child(1) > b").innerText
 
copy("RougeMTL" + dateSent);
 
document.querySelector("#dataContainerNoScroll")
```