## Whales_Analysis
This project oversees/manages large funds, also known as "whales".  The whales analysis is essentially a risk analysis, keeping track of risk management using daily returns, standard deviations, sharpe ratios, and betas.  

The outcome of the analysis will determine risk, risk/returns, volatality, and overall performance of particular funds (BERKSHIRE HATHAWAY INC, SOROS FUND MANAGEMENT LLC, PAULSON & CO INC, TIGER GLOBAL MANAGEMENT LLC) against the S&P 500.  

The Whales analysis will show the user charts/calculations which will provide visualization and more knowledge on which fund would be best to invest in given their preference of risk, etc.  

## Required Technologies 
Python 3.10.1
Jupyter lab 
Pandas
numpy
matplotlib
pathlib
csv files with net asset values (NAV)

## Installation Guide

Installing Python (MacOS):

Command + Space Enter Terminal in search bar and press enter Terminal should open Open Homebrew Installation website in browser (https://brew.sh/) Copy installation code at the bottom of the page Copy shown link into terminal Once Homebrew is installed, install Python Open Terminal Enter "brew install python3" into the CLI to install Python Installing Anaconda with Python (MacOS): Enter "conda create -n dev python=3.7 anaconda" into the command line terminal Return and type Y when prompted Open environment by entering "conda activate dev" Enable terminal commands through conda

Clone local Repo: git clone https://github.com/Alexisg324/Whales_Analysis.git

Install Software: 
pip install pandas
pip install pathlib 
pip install jupyter lab

![Install dependancies] (Desktop/Github_Upload/Whales_Analysis/Screenshots/installation.png)

## Usage 

As a user, I want to recieve analytics on funds' risk/reward based on the NAV csv files.  

The application will be able to provide the user with analytics, including visualization.  

Below is an example of what the analysis will look like for the user:
(Desktop/Github_Upload/Whales_Analysis/Screenshots/Visualization.png)

(Desktop/Github_Upload/Whales_Analysis/Screenshots/Visualization2.png)

## Contributers

Alexis Rose Garcia Alexisg324@gmail.com www.linkedin.com/in/alexis-rose-garcia

## License

license() A. HISTORY OF THE SOFTWARE ==========================

Python was created in the early 1990s by Guido van Rossum at Stichting Mathematisch Centrum (CWI, see http://www.cwi.nl) in the Netherlands as a successor of a language called ABC. Guido remains Python's principal author, although it includes many contributions from others.

In 1995, Guido continued his work on Python at the Corporation for National Research Initiatives (CNRI, see http://www.cnri.reston.va.us) in Reston, Virginia where he released several versions of the software.

In May 2000, Guido and the Python core development team moved to BeOpen.com to form the BeOpen PythonLabs team. In October of the same year, the PythonLabs team moved to Digital Creations, which became Zope Corporation. In 2001, the Python Software Foundation (PSF, see https://www.python.org/psf/) was formed, a non-profit organization created specifically to own Python-related Intellectual Property. Zope Corporation was a sponsoring member of the PSF.

All Python releases are Open Source (see http://www.opensource.org for the Open Source Definition). Historically, most, but not all, Python Hit Return for more, or q (and Return) to quit: releases have also been GPL-compatible; the table below summarizes the various releases.

Release Derived Year Owner GPL- from compatible? (1)

0.9.0 thru 1.2 1991-1995 CWI yes 1.3 thru 1.5.2 1.2 1995-1999 CNRI yes 1.6 1.5.2 2000 CNRI no 2.0 1.6 2000 BeOpen.com no 1.6.1 1.6 2001 CNRI yes (2) 2.1 2.0+1.6.1 2001 PSF no 2.0.1 2.0+1.6.1 2001 PSF yes 2.1.1 2.1+2.0.1 2001 PSF yes 2.1.2 2.1.1 2002 PSF yes 2.1.3 2.1.2 2002 PSF yes 2.2 and above 2.1.1 2001-now PSF yes Footnotes:

(1) GPL-compatible doesn't mean that we're distributing Python under the GPL. All Python licenses, unlike the GPL, let you distribute a modified version without making your changes open source. The Hit Return for more, or q (and Return) to quit: GPL-compatible licenses make it possible to combine Python with other software that is released under the GPL; the others don't.

(2) According to Richard Stallman, 1.6.1 is not GPL-compatible, because its license has a choice of law clause. According to CNRI, however, Stallman's lawyer has told CNRI's lawyer that 1.6.1 is "not incompatible" with the GPL.

Thanks to the many outside volunteers who have worked under Guido's direction to make these releases possible.

B. TERMS AND CONDITIONS FOR ACCESSING OR OTHERWISE USING PYTHON Starting with Python 3.8.6, examples, recipes, and other code in the documentation are dual licensed under the PSF License Version 2 and the Zero-Clause BSD license.

Some software incorporated into Python is under different licenses. Hit Return for more, or q (and Return) to quit: The licenses are listed with code falling under that license.

This LICENSE AGREEMENT is between the Python Software Foundation ("PSF"), and the Individual or Organization ("Licensee") accessing and otherwise using Python 3.10.2 software in source or binary form and its associated documentation.

Subject to the terms and conditions of this License Agreement, PSF hereby grants Licensee a nonexclusive, royalty-free, world-wide license to reproduce, analyze, test, perform and/or display publicly, prepare derivative works, distribute, and otherwise use Python 3.10.2 alone or in any derivative version, provided, however, that PSF's License Agreement and PSF's notice of copyright, i.e., "Copyright © 2001-2022 Python Software Foundation; All Rights Reserved" are retained in Python 3.10.2 alone or in any derivative version prepared by Licensee.

In the event Licensee prepares a derivative work that is based on or incorporates Python 3.10.2 or any part thereof, and wants to make the derivative work available to others as provided herein, then Licensee hereby agrees to include in any such work a brief summary of the changes made to Python 3.10.2.

PSF is making Python 3.10.2 available to Licensee on an "AS IS" basis. PSF MAKES NO REPRESENTATIONS OR WARRANTIES, EXPRESS OR IMPLIED. BY WAY OF EXAMPLE, BUT NOT LIMITATION, PSF MAKES NO AND DISCLAIMS ANY REPRESENTATION OR WARRANTY OF MERCHANTABILITY OR FITNESS FOR ANY PARTICULAR PURPOSE OR THAT THE USE OF PYTHON 3.10.2 WILL NOT INFRINGE ANY THIRD PARTY RIGHTS.

PSF SHALL NOT BE LIABLE TO LICENSEE OR ANY OTHER USERS OF PYTHON 3.10.2 FOR ANY INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES OR LOSS AS A RESULT OF MODIFYING, DISTRIBUTING, OR OTHERWISE USING PYTHON 3.10.2, OR ANY DERIVATIVE THEREOF, EVEN IF ADVISED OF THE POSSIBILITY THEREOF.

This License Agreement will automatically terminate upon a material breach of its terms and conditions.

Nothing in this License Agreement shall be deemed to create any relationship of agency, partnership, or joint venture between PSF and Licensee. This License Agreement does not grant permission to use PSF trademarks or trade name in a trademark sense to endorse or promote products or services of Licensee, or any third party.

By copying, installing or otherwise using Python 3.10.2, Licensee agrees to be bound by the terms and conditions of this License Agreement.

ZERO-CLAUSE BSD LICENSE FOR CODE IN THE PYTHON DOCUMENTATION Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM Hit Return for more, or q (and Return) to quit: LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

## Workcited:
UCB-Coding-Bootcamp (2021-2022). Module 4. UC Berkeley Fintech Extension. https://courses.bootcampspot.com/



