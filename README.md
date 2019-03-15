<?php

print " Quantos cigarros você fuma por dia?";
$day = (int) fgets (STDIN);

print " Há quantos anos você fuma?";
$years = (int) fgets (STDIN);

$min = $day*365*$years;
$perdidos = $min*10;
$hrs = $perdidos/60;
$diasper = round ($hrs/24);

print " Você perderá $diasper dias da sua vida!";



