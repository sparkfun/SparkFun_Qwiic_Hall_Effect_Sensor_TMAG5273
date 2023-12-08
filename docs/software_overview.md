---
icon: simple/arduino
---

## Arduino IDE
!!! tip
	For first-time users, who have never programmed before and are looking to use the Arduino IDE, we recommend beginning with the <a href="https://www.sparkfun.com/products/15631">SparkFun Inventor's Kit (SIK)</a>, which is designed to help users get started programming with the Arduino IDE.

Most users may already be familiar with the Arduino IDE and its use. However, for those of you who have never heard the name *Arduino* before, feel free to check out the [Arduino website](https://www.arduino.cc/en/Guide/HomePage). To get started with using the Arduino IDE, check out our tutorials below:


<div class="grid cards" markdown align="center">

-   <a href="https://learn.sparkfun.com/tutorials/50"><figure markdown>
	![What is an Arduino?](https://cdn.sparkfun.com/c/264-148/assets/3/b/6/e/b/512e66bece395f492b000000.jpg)
	</figure>

	---

	**What is an Arduino?**</a>

-   <a href="https://learn.sparkfun.com/tutorials/61"><figure markdown>
	![Installing the Arduino IDE](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/1/arduinoThumb.jpg)
	</figure>

	---
	
	**Installing the Arduino IDE**</a>

-   <a href="https://learn.sparkfun.com/tutorials/15"><figure markdown>
	![Installing an Arduino Library](https://cdn.sparkfun.com/c/264-148/assets/b/e/4/b/2/50f04b99ce395fd95e000001.jpg)
	</figure>

	---
	
	**Installing an Arduino Library**</a>

-   <a href="https://learn.sparkfun.com/tutorials/1265"><figure markdown>
	![Installing Board Definitions in the Arduino IDE](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/2/6/5/sparkfun_boards.PNG)
	</figure>

	---
	
	**Installing Board Definitions in the Arduino IDE**</a>
</div>


??? tip "Need help setting up the RedBoard Plus?"
	### RedBoard Plus
	The following instructions should help users get started with the RedBoard Plus. For more information about the board, please check out our hookup guide below:

	<div class="grid cards" markdown align="center">

	-   <a href="https://learn.sparkfun.com/tutorials/1758">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/500-282/assets/learn_tutorials/1/7/5/8/18158-SparkFun_RedBoard_Plus-01.jpg)
		</figure>

		---

		**RedBoard Plus Hookup Guide**</a>

	</div>


	#### CH340 Driver
	Users will need to install the appropriate driver for their computer to recognize the serial-to-UART chip on their board/adapter. Most of the latest operating systems will recognize the CH340C chip on the board and automatically install the required driver.

	!!! tip
		To manually install the *latest* CH340 driver on their computer, users can download it from the [WCH website](http://www.wch-ic.com/products/CH340.html?). For more information, check out our [How to Install CH340 Drivers Tutorial](https://www.sparkfun.com/ch340).

	<div class="grid cards" markdown align="center">

	-   <a href="https://learn.sparkfun.com/tutorials/908">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/500-282/assets/learn_tutorials/9/0/8/USB-to-serial_converter_CH340-closeup.jpg)
		</figure>

		---

		**How to Install CH340 Drivers**</a>

	</div>


	#### Selecting a Board
	When selecting a board to program in the Arduino IDE, users should select the **Arduino Uno** from the **Tools** drop-down menu _(_i.e. **Tools** > **Board** > **Arduino AVR Boards** > **Arduino Uno**)_.

	<figure markdown>
	[![](./assets/img/hookup_guide/board_selection.png "Click to enlarge"){ width="400" }](./assets/img/hookup_guide/board_selection.png)
	<figcaption markdown>Select the **Arduino Uno** from the Tools drop-down menu in the Arduino IDE.</figcaption>
	</figure>

	??? info "Arduino IDE 2.x.x - *Alternative Method*"
		In the newest version of the Arduino IDE 2.`x`.`x`, users can also select their board (*green*) and port (*blue*) from the `Select Board & Port` dropdown menu (*yellow*).

		<figure markdown>
		[![](./assets/img/hookup_guide/board_selection2.png "Click to enlarge"){ width="400" }](./assets/img/hookup_guide/board_selection2.png)
		<figcaption markdown>Selecting the **Arduino Uno** and **COM5** port from the **Select Board & Port** drop-down menu in the Arduino IDE (v2.0.3).</figcaption>
	</figure>


## SparkFun TMAG5273 Arduino Library
The [SparkFun TMAG5273 Arduino library](https://github.com/sparkfun/SparkFun_TMAG5273_Arduino_Library) can be installed from the library manager in the Arduino IDE by searching for:

	SparkFun TMAG5273 Arduino library

<figure markdown>
[![](./assets/img/hookup_guide/arduino_library.png "Click to enlarge"){ width="400" }](./assets/img/hookup_guide/arduino_library.png)
<figcaption markdown>SparkFun TMAG5273 Arduino library in the library manager of the Arduino IDE.</figcaption>
</figure>

??? tip "Manually Downloading the Arduino Library"
	For users who would like to manually download and install the library, the `*.zip` file can be accessed from the [GitHub repository](https://github.com/sparkfun/SparkFun_TMAG5273_Arduino_Library) or downloaded by clicking the button below.

	<center>
	[:octicons-download-16:{ .heart } Download the Arduino Library](https://github.com/sparkfun/SparkFun_TMAG5273_Arduino_Library/archive/refs/heads/main.zip){ .md-button .md-button--primary }
	</center>

<!-- 
??? tip "Arduino IDE *(v1.x.x)*"
	In the Arduino IDE v1.x.x, the library manager will have the following appearance for the SparkFun TMAG5273 Arduino library:

	<figure markdown>
	[![](./assets/img/hookup_guide/arduino_library-legacy.png "Click to enlarge"){ width="400" }](./assets/img/hookup_guide/arduino_library-legacy.png)
	<figcaption markdown>SparkFun TMAG5273 Arduino library in the library manager of the Arduino IDE (v1.x.x).</figcaption>
	</figure>
 -->
