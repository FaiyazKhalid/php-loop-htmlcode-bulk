# php-loop-htmlcode-bulk


for ($x = 1; $x <= 1500; $x++) {


 

//$html = <<<HTML

set droptop=37<br>

for /f %%i in ( ' find /c /v "" ^<$x.html ' ) do set /a dropend=%%i-20<br>

for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""<br>

^<$x.html ' ) do if %%i leq %dropend% >>new\'$x.html echo\%%j<br>

for %%i in (droptop dropend) do (set %%i=)

HTML;

// echo $html.'<br>';

}



