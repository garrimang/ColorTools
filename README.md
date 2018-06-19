# ColorTools

This is Simple PHP Static Helper Class for RGB To HSL/HSL to RGB color manipulation and Color List Generator.
Color lists may used for some task: generate unique colors with same lightness, generate paletes for ChartDirector and others

Class include few static function for color manipulations

## Usage

	<?php
		$count  = 8;
		$color  = '3d628e';
		$colors = ColorTools::ColorArrayGenerator($count,$color,true);
		print_r($colors);
	?>

	Array
	(
		[0] => #3d628e
		[1] => #553d8e
		[2] => #8e3d8b
		[3] => #8e3d4e
		[4] => #8e693d
		[5] => #768e3d
		[6] => #3d8e40
		[7] => #3d8e7d
	)
	
Use this colors for generate some color blocks
<img src="https://raw.githubusercontent.com/NickyX3/ColorTools/master/result_preview.png">

## CREDITS

Nic Latyshev <nickyx3@gmail.com>

This work is dual-licensed under the GPL v3 and the MIT license.
