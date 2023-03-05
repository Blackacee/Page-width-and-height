# Page-width-and-height
 
function pageWidth() {
 return window.innerWidth != null? window.innerWidth : document.documentElement &&
document.documentElement.clientWidth ? document.documentElement.clientWidth : document.body != null
? document.body.clientWidth : null;
}
function pageHeight() {
 return window.innerHeight != null? window.innerHeight : document.documentElement &&
document.documentElement.clientHeight ? document.documentElement.clientHeight : document.body !=
null? document.body.clientHeight : null;
}
