---
icon: sfe-logo
---

!!! warning "Need Help?"
	If you need technical assistance or more information on a product that is not working as you expected, we recommend heading on over to the [SparkFun Technical Assistance](https://www.sparkfun.com/technical_assistanc) page for some initial troubleshooting.

	<center>
	[SparkFun Technical Assistance Page](https://www.sparkfun.com/technical_assistance){ .md-button .md-button--primary }
	</center>
	
	If you can't find what you need there, the [SparkFun Forums](https://forum.sparkfun.com/index.php) is a great place to search product forums and ask questions.
	
	!!! info "Account Registration Required"
		If this is your first visit to our forum, you'll need to create a [Forum Account](https://forum.sparkfun.com/ucp.php?mode=register) to post questions.

### `PWR` LED dims when the board is disabled

The `PWR` LED on the Qwiic hall-effect sensor may only dim when it is disabled through the ++"Disable"++ button or `DISABLE` PTH pin. This will occur when the Qwiic hall-effect sensor is used in conjunction with development boards that have pull-up resistors on their `SDA` and `SCL` pins.

The combination of the pull-up resistors on the development board and the Qwiic hall-effect sensor will bypass the `DISABLE` pin's power cut-off circuitry. This results in the development board back-powering the Qwiic hall-effect sensor and its LED. In most circumstances, users shouldn't experience any issues, as the sensor should be within the under-voltage threshold and still reset.[^1] However, if the issue persists, users can disconnect the pull-up resistors on the Qwiic hall-effect sensor by cutting the `I2C` jumper.

[^1]: We have thoroughly tested this issue with all of our development boards and have found that the Qwiic hall-effect sensor will still reset, when disabled because the sensor will be within its under-voltage threshold.
