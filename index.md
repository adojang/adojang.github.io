<!DOCTYPE html> 
<html>
<head><meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Gate Control</title>
<style>html { font-family: Helvetica; display: inline-block; margin: 0px auto; text-align: center;}
body{margin-top: 50px;} h1 {color: #444444;margin: 50px auto 30px;} h3 {color: #444444;margin-bottom: 50px;}
.button {display: block;width: 80px;background-color: #3498db;border: none;color: white;padding: 13px 30px;text-decoration: none;font-size: 25px;margin: 0px auto 35px;cursor: pointer;border-radius: 4px;}
.buttonsmall {display: block;width: 80px;background-color: #3498db;border: none;color: white;padding: 13px 30px;text-decoration: none;font-size: 18px;margin: 0px auto 35px;cursor: pointer;border-radius: 4px;}
.button-on {background-color: #d74242;}
.button-on:active {background-color: #d74242;}
.button-off {background-color: #852b2b;}
.button-off:active {background-color: #2c3e50;}
.button-save {background-color: #429bd7;}
p {font-size: 14px;color: #888;margin-bottom: 10px;}
</style>
</head>
<body>
<h1>Tarentaal Gate Control</h1>
<p>Button Released</p><a class="button button-on" href="/toggle">Toggle Gate</a>
<a class="buttonsmall button-save" href="/exitconfig">Save Settings and Quit</a>
<form action="/sendrssi" method="POST"><input type = "number" name = "custom_in" placeholder = "Custom RSSI coming in"><br><input type = "number" name = "custom_out" style = "border-color:green;"placeholder = "Custom RSSI going out"><br><br><input type = "submit" value = "Enter"></form><h6>Created by A. van Wijk, 2021</h6>
</body>
</html>
