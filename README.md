<?php

print " Quantos cigarros você fuma por dia?";
$pordia = (int) fgets (STDIN);

print " Há quantos anos você fuma?";
$years = (int) fgets (STDIN);

$min = $pordia*365*$years;
$min_perdidos = $min*10;
$hrs = $min_perdidos/60;
$diasper = round ($hrs/24);

print " Você perderá $diasper dias da sua vida!";



