# RandomPassword
$Alphabet = "AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz!@#$%^&*()_";

$Password = str_split($Alphabet);

$MinimumPassword = "";

$MaximumPassword = 10;

shuffle($Password);

for ($index=0; $index < $MaximumPassword ; $index++) { 

    $MinimumPassword .= $Password[$index];
}

echo $MinimumPassword ;
