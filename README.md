# period-tracker
<!DOCTYPE html>
<html>
<head>
    <!--http://wwww.periodt.com -->
    <title>Periodt</title>
    <link href="shoppingcart.css" rel="stylesheet" type="text/css" />
    <script src="shoppingcart.js" type="text/javascript"></script>
    <script>
        var scart = new shoppingcart();
        scart.Paypal.business = "periodt@paypal.com";
        scart.inventory.Add("ORGANICCOTTONPADS", "Organic Cotton Pad (Sumi-e)", "15.99"," Organic Cotton Pads (Sumi-e)" http://wwww.periodt.com/yonishop/organic-cotton-pads.jpg)
    </script>
</head>
<body>

<div id="ORGANICCOTTONPADS"></div>
<div id="REUSABLEORGANICCOTTONPADS"></div>
<div id="ORGANICCOTTONTAMPONS"></div>
<div id="MENSTRUALCUP"></div>
<input type="button" onclick="scart.Show" value="Show cart" />
