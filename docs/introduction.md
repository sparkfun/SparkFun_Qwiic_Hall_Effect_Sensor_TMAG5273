---
icon: material/book-open-page-variant
---

# Introduction

Do you have a project that could use an inconspicuous [HID](https://en.wikipedia.org/wiki/Human_interface_device) (human interface device)? Ever wanted to tamper-proof your window alarm (i.e. contact sensors) from teenagers sneaking out or home intruders? Do you have a mechanical switch that keeps failing?

<section class="grid cards" markdown>

-   <a href="https://www.sparkfun.com/products/23880">
	**SparkFun Linear 3D Hall-Effect Sensor - TMAG5273 (Qwiic)**<br>
	**SKU:** SEN-23880

	---

	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/2/3/7/23880-Linear-3D-Hall-Effect-Sensor-1x1-Feature-new.jpg)
	</figure></a>

	<center>
	[![QR code to product page](./assets/img/qr_code/product-23880.png){ .tinyqr }&nbsp;&nbsp;Purchase from SparkFun :fontawesome-solid-cart-plus:{ .heart }](https://www.sparkfun.com/products/23880){ .md-button .md-button--primary }
	</center>

-   <a href="https://www.sparkfun.com/products/23881">
	**SparkFun Mini Linear 3D Hall-Effect Sensor - TMAG5273 (Qwiic)**<br>
	**SKU:** SEN-23881

	---

	<figure markdown>
	![Product image](https://cdn.sparkfun.com/assets/parts/2/4/2/3/8/23881-Linear-3D-Hall-Effect-Sensor-Mini-Feature-new.jpg)
	</figure></a>

	<center>
	[![QR code to product page](./assets/img/qr_code/product-23881.png){ .tinyqr }&nbsp;&nbsp;&nbsp;Purchase from SparkFun :fontawesome-solid-cart-plus:{ .heart }](https://www.sparkfun.com/products/23881){ .md-button .md-button--primary }
	</center>

</section>

If you answered yes to any of those questions, the TMAG5273 from [Texas Instruments](https://www.ti.com) could be the solution to your problems. The [TMAG5273](](./assets/component_documentation/tmag5273.pdf)) is low-power 3D [hall-effect sensor](https://en.wikipedia.org/wiki/Hall_effect_sensor) that is perfect for detecting and measuring changes in a nearby magnetic field. With a linear, magnetic range configurable to either ±40 mT or ±80 mT and TI's integrated angle calculation engine (CORDIC), the TMAG5273 can be used in various applications:

* Detecting motor movement
* Creating a [HID](https://en.wikipedia.org/wiki/Human_interface_device) (human interface device) *(i.e. joysticks, knobs, scroll wheels, etc.)*
* Replacing various mechanical switches (i.e. rotary encoders, contact switches, reed switches, etc.)*

In addition, the included magnetic tamper detection and wake-up/threshold settings can be configured to trigger interrupts through the I<sup>2</sup>C interface or only with the dedicated interrupt pin.



## :fontawesome-solid-list-check:&nbsp;Required Materials
To get started, users will need a few items. Now some users may already have a few of these items, feel free to modify your cart accordingly.

<div class="annotate" markdown>

* Computer with an operating system (OS) that is compatible with all the software installation requirements
* A compatible microcontroller/Arduino board; we recommend the [SparkFun RedBoard Plus](https://www.sparkfun.com/products/18158).
* [USB 3.1 Cable A to C - 3 Foot](https://www.sparkfun.com/products/14743) - Used to interface with the RedBoard Plus (1)
* [SparkFun Qwiic Cable Kit](https://www.sparkfun.com/products/15081) (2)
* [SparkFun Hall-Effect Sensor - TMAG5273](https://www.sparkfun.com/products/23880) (3)
* [Magnet Square - 0.25"](https://www.sparkfun.com/products/8643) (4)


</div>

1. If your computer doesn't have a USB-A slot, then choose an appropriate cable or adapter.
2. Check out our [other Qwiic cable options](https://www.sparkfun.com/search/results?term=qwiic+cable).
3. The [mini version](https://www.sparkfun.com/products/23881) of this product is panel-mount compatible.
4. Check out the [other magnets](https://www.sparkfun.com/categories/322) in our catalog.


<div class="grid cards" markdown>

-   <a href="https://www.sparkfun.com/products/14743">
	<figure markdown>
	![USB 3.1 Cable A to C - 3 Foot](https://cdn.sparkfun.com/assets/parts/1/2/9/7/2/14743-USB_3.1_Cable_A_to_C_-_3_Foot-01.jpg)
	</figure>

	---

	**USB 3.1 Cable A to C - 3 Foot**<br>
	CAB-14743</a>

-   <a href="https://www.sparkfun.com/products/18158">
	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/7/4/8/7/18158-SparkFun_RedBoard_Plus-01.jpg)
	</figure>

	---

	**SparkFun RedBoard Plus**<br>
	DEV-18158</a>

-   <a href="https://www.sparkfun.com/products/15081">
	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/3/4/3/1/15081-_01.jpg)
	</figure>

	---

	**SparkFun Qwiic Cable Kit**<br>
	KIT-15081</a>

-   <a href="https://www.sparkfun.com/products/23880">
	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/2/3/7/23880-Linear-3D-Hall-Effect-Sensor-1x1-Feature-new.jpg)
	</figure>

	---

	**SparkFun Linear 3D Hall-Effect Sensor - TMAG5273 (Qwiic)**<br>
	SEN-23880</a>

	??? tip "Button Casing"
		The button casing appears to be ferromagnetic. Therefore, a strong magnetic field *(i.e. from a rare Earth magnet)* could potentially exert enough force to rotate or lift the board.

-   <a href="https://www.sparkfun.com/products/23880">
	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/2/3/8/23881-Linear-3D-Hall-Effect-Sensor-Mini-Feature-new.jpg)
	</figure>

	---

	**SparkFun Mini Linear 3D Hall-Effect Sensor - TMAG5273 (Qwiic)**<br>
	SEN-23881</a>

-   <a href="https://www.sparkfun.com/products/8643">
	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/7/8/5/08643-02-L.jpg)
	</figure>

	---

	**Magnet Square - 0.25"**<br>
	COM-08643</a>

	??? danger "Metal Casing"
		The casing for rare Earth magnets, such as these, is often conductive. Users should take precautions to avoid shorting out the components or electrical contacts.

</div>


??? note "Headers and Wiring"
	To add headers or hookup wires, users will need [soldering equipment](https://www.sparkfun.com/categories/49) and [headers](https://www.sparkfun.com/categories/381)/[wire](https://www.sparkfun.com/search/results?term=hook-up+wire).


	!!! tip "New to soldering?"
		Check out our [How to Solder: Through-Hole Soldering](https://learn.sparkfun.com/tutorials/5) tutorial for a quick introduction!

		<div class="grid cards" markdown align="center">

		-   <a href="https://learn.sparkfun.com/tutorials/5">
			<figure markdown>
			![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg)
			</figure>

			---

			**How to Solder: Through-Hole Soldering**</a>

		</div>


	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/9325">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/7/3/09325_9161-Solder_Lead_Free_-_100-gram_Spool-01.jpg)
		</figure>

		---

		**Solder Lead Free - 100-gram Spool**<br>
		TOL-09325</a>

	-   <a href="https://www.sparkfun.com/products/14228">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/2/1/7/3/14228-01.jpg)
		</figure>

		---

		**Weller WLC100 Soldering Station**<br>
		TOL-14228</a>


	-   <a href="https://www.sparkfun.com/products/14579">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/2/7/2/5/14579-Chip_Quik_No-Clean_Flux_Pen_-_10mL-01.jpg)
		</figure>

		---

		**Chip Quik No-Clean Flux Pen - 10mL**<br>
		TOL-14579</a>


	-   <a href="https://www.sparkfun.com/products/116">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/0/6/00116-02-L.jpg)
		</figure>

		---

		**Break Away Headers - Straight**<br>
		PRT-00116</a>

	-   <a href="https://www.sparkfun.com/products/11375">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/7/1/2/0/11375-Hook-Up_Wire_-_Assortment__Solid_Core__22_AWG_-01.jpg)
		</figure>

		---

		**Hook-Up Wire - Assortment (Stranded, 22 AWG)**<br>
		PRT-11375</a>

	</div>


??? note "Jumper Modification"
	To modify the [jumpers](../hardware_overview/#jumpers), users will need [soldering equipment](https://www.sparkfun.com/categories/49) and/or a [hobby knife](https://www.sparkfun.com/categories/379).


	!!! tip "New to jumper pads?"
		Check out our [Jumper Pads and PCB Traces Tutorial](https://learn.sparkfun.com/tutorials/664) for a quick introduction!

		<div class="grid cards" markdown align="center">

		-   <a href="https://learn.sparkfun.com/tutorials/664">
			<figure markdown>
			![Tutorial thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg)
			</figure>

			---

			**How to Work with Jumper Pads and PCB Traces**</a>

		</div>


	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/9325">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/7/3/09325_9161-Solder_Lead_Free_-_100-gram_Spool-01.jpg)
		</figure>

		---

		**Solder Lead Free - 100-gram Spool**<br>
		TOL-09325</a>

	-   <a href="https://www.sparkfun.com/products/14228">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/2/1/7/3/14228-01.jpg)
		</figure>

		---

		**Weller WLC100 Soldering Station**<br>
		TOL-14228</a>


	-   <a href="https://www.sparkfun.com/products/14579">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/2/7/2/5/14579-Chip_Quik_No-Clean_Flux_Pen_-_10mL-01.jpg)
		</figure>

		---

		**Chip Quik No-Clean Flux Pen - 10mL**<br>
		TOL-14579</a>


	-   <a href="https://www.sparkfun.com/products/9200">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/6/4/6/09200-Hobby_Knife-01.jpg)
		</figure>

		---

		**Hobby Knife**<br>
		TOL-09200</a>

	</div>




## :material-bookshelf:&nbsp;Suggested Reading

As a more sophisticated product, we will skip over the more fundamental tutorials (i.e. [**Ohm's Law**](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law) and [**What is Electricity?**](https://learn.sparkfun.com/tutorials/what-is-electricity)). However, below are a few tutorials that may help users familiarize themselves with various aspects of the board.

<div class="grid cards" markdown align="center">

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

-   <a href="https://learn.sparkfun.com/tutorials/1758">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/7/5/8/18158-SparkFun_RedBoard_Plus-01.jpg)
	</figure>

	---

	**RedBoard Plus Hookup Guide**</a>

	??? tip "<div align="left">USB Driver<div>"
		<article class="grid cards" markdown align="center">

		-   <a href="https://learn.sparkfun.com/tutorials/908">
			<figure markdown>
			![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/9/0/8/USB-to-serial_converter_CH340-closeup.jpg)
			</figure>

			---

			**How to Install CH340 Drivers**</a>

		</article>

-   <a href="https://learn.sparkfun.com/tutorials/112">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/1/2/thumb.jpg)
	</figure>

	---

	**Serial Terminal Basics**</a>

-   <a href="https://learn.sparkfun.com/tutorials/62">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/2/Input_Output_Logic_Level_Tolerances_tutorial_tile.png)
	</figure>

	---

	**Logic Levels**</a>

-   <a href="https://learn.sparkfun.com/tutorials/82">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/8/2/I2C-Block-Diagram.jpg)
	</figure>

	---

	**I2C**</a>

-   <a href="https://learn.sparkfun.com/tutorials/5">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg)
	</figure>

	---

	**How to Solder: Through-Hole Soldering**</a>

-   <a href="https://learn.sparkfun.com/tutorials/664">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg)
	</figure>

	---

	**How to Work with Jumper Pads and PCB Traces**</a>

</div>
