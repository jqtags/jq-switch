Sample Code: 
```html
	<jq-switch id="switch1" value=true on=Yes off=No label="Auto Search" ></jq-switch>
```
Using jQuery you can get/set value

```javascript
$("#switch1").val(true);

var x = $("#switch1").val();

$("#switch1").on("change",function(e){
    console.log("callback : switch has toggled")
})


```

# Install


```console
composer require jqtags/jq-switch

bower install jqtags-jq-switch

```