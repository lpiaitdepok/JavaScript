fullcalendar has already been rendered

```
$(function() {
// fullcalendar has already been rendered 

  if($('#calendar').length !== 0) alert("calendar exists!!");
  
  // or
  if ( $('#calendar').children().length > 0 ) {
    alert("calendar exists!!");
}

// or
if ( document.getElementById('calendar').hasChildNodes() == true ) {
    alert("calendar exists!!");
}
  
});
