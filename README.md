<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-type" content="text/html;
charset=utf-8">
<meta name="viewport" id="viewport" content="width=device-width, height=device-height, initial-scale=1.0, maximum-scale=1.0, user-scalable=no;" />
<script type="text/javascript" charset="utf-8" src="phonegap.js"></script>

<script type="text/javascript" charset="utf-8">
function onBodyLoad() {
document.addEventListener("deviceready",onDeviceReady,
false);
}
function onDeviceReady() {
navigator.notification.alert("PhoneGap is ready!");
}
</script>

</head>
<body onload="onBodyLoad()">
<h1>HelloWorld2</h1>
<p>This is a sample PhoneGap application.</p>
</body>
</html>
