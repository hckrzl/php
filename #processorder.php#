<html>
<head>

<title>
Bob's Auto Parts - Order Results
</title>
</head>

<body>
<h1>Bob's Auto Parts</h1>
<h2>Order Results</h2>
<?php
echo "order processed!";
echo "<p>".date('H:i, jS F Y')."</p>";

$tireqty=$_REQUEST['tires'];
$oilqty=$_REQUEST['oil'];
$sparkqty=$_REQUEST['sparks'];

echo "<p>the quantity of tires is $tireqty"."</p>";
echo "<p>the quantiry of oil is $oilqty"."</p>";
echo "<p>the quantity of sparks is $sparkqty"."</p>";

#var_dump($_REQUEST);

define('TIREPRICE',100.0);
define('OILPRICE',10.0);
define('SPARKPRICE',4.0);


echo "The total price for tires is: ".$tireqty*TIREPRICE."<br />";
echo "The total price for oil is: ".$oilqty*OILPRICE."<br />";
echo "The total price for sparks is: ".$sparkqty*SPARKPRICE."<br />";


$out=`ls -la`;
echo "<pre>".$out."</pre>";

#var_dump($_REQUEST);
#define the global variables

define('TIREPRICE',100.0);
define('OILPRICE',10.0);
define('SPARKPRICE',4.0);


echo "The total price for tires is: ".$tireqty*TIREPRICE."<br />";
echo "The total price for oil is: ".$oilqty*OILPRICE."<br />";
echo "The total price for sparks is: ".$sparkqty*SPARKPRICE."<br />";

?>




</body>
</html>
