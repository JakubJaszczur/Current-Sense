<p align="center">
  <a href="" rel="noopener">
 <img width=400px height=300px src="Pictures/IMG_20210406_193517.jpg" alt="Device"></a>
</p>

<h1 align="center">Current Sense</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/JakubJaszczur/Current-Sense.svg)](https://github.com/JakubJaszczur/Current-Sense/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/JakubJaszczur/Current-Sense.svg)](https://github.com/JakubJaszczur/Current-Sense/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Simple circuit to measure small currents
    <br> 
</p>

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Changelog](#changelog)
- [Pictures](#pictures)

## 1. About <a name = "about"></a>

This project was inspired by Micro Current Gold project, but this is simpler, budgetory version.

## 2. Features <a name = "features"></a>

* High gain
* Three measurement ranges (10uA, 10mA, 1A)
* Low voltage offset
* Possible voltage offset compensation

## 3. Getting Started <a name = "getting_started"></a>

To start, just use gerber files to order your own PCB, and order parts from BOM file. Device is powered by two 12V batteries.

## 4. Usage <a name="usage"></a>

Use SW3 to switch ON device. Adjust current range using SW2. To read current you can use voltmeter, or oscilloscope. To calculate current, use table below: <br/>

| Range | Max current | Voltage| Current|		   
| ------| ------------|--------|--------|
| nA    | 10uA        |1mV     |1nA     |
| uA    | 10mA        |1mV     |1uA     |
| mA    | 1A        |1mV     |0.1mA     |

## 5. Changelog <a name="changelog"></a>

2021-04-06 <b>V1.0</b> First version

## 6. Pictures <a name="pictures"></a>

