# CU-SDR-Collection-main-Octave

## Introduction

This repository is forked from CU Boulder's Open-Source Software-Defined Radio collection and modify to GNU Octave version with RTL-SDR front-end.

https://github.com/gnsscusdr/CU-SDR-Collection.git

## GNU Octave

GNU Octave is a high-level interpreted language, primarily intended for numerical computations. It provides a command-line interface for solving linear and nonlinear problems numerically, and for performing other numerical experiments.

Key features include:

*   **Free and Open-Source:** It is released under the GNU General Public License (GPL), making it free to use, distribute, and modify.
*   **MATLAB Compatibility:** It is largely compatible with MATLAB. Many scripts can be run in both environments without modification. This makes it a popular free alternative to MATLAB.
*   **Numerical Computation:** It has powerful built-in tools for matrix operations (linear algebra), calculus, polynomial manipulation, and solving differential equations.
*   **Plotting:** It can create a wide range of 2D and 3D plots for data visualization.
*   **Extensibility:** Its functionality can be extended with user-written functions or by using community-developed packages.

## RTL-SDR Front-End

RTL-SDR refers to a range of very low-cost software-defined radios that utilize DVB-T TV tuner dongles based on the Realtek RTL2832U chipset. It was discovered that these inexpensive devices could be used as general-purpose wideband SDR receivers, which has made them extremely popular among hobbyists and students.

Key aspects of using an RTL-SDR as a front-end:

*   **Accessibility:** Their low cost makes them an excellent entry point into the world of software-defined radio.
*   **Wide Frequency Range:** They can typically receive signals from approximately 24 MHz to 1.7 GHz, allowing for the reception of a wide variety of signals, including FM radio, air traffic control, and satellite signals.
*   **Function:** As a "front-end," the RTL-SDR dongle is the hardware responsible for receiving the analog radio frequency (RF) signals from an antenna, converting them into digital data, and streaming that data to a computer.
*   **Processing:** The digital signal data from the RTL-SDR is then processed by software on the host computer, which in the case of this project, is GNU Octave.

## Example Dataset

Here are the dataset in various environments:

**Open Sky, Static**

**Harsh Environment, Static**

