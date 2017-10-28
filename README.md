# PVV theme for SimpleSamlPhp

This has been forked from [fyrkat/ssp-theme](https://github.com/fyrkat/ssp-theme)

Clone this repo to your modules directory

	git clone https://github.com/Programvareverkstedet/ssp-theme themepvv

Make the following changes in your SSP setup:

## config/config.php

	'module.enable' => [
		'themepvv' => TRUE,
	],

	'theme.use' => 'themepvv:pvv',
