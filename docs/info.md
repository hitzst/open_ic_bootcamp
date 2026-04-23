<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

To start counting, the EN (enable) pin must be set HIGH and the R (reset) pin LOW. Then, each pulse on the IN (input) pin will increase the binary representation of the outputs by 1. Four output bits are available (B0-B3). Setting the EN pin LOW will disable counting. Setting the R pin HIGH will reset all output pins to LOW (0).

## How to test

Set the EN pin to HIGH and attach a pulse generator to the IN pin. The output bits should now count up.
Set the EN pin to LOW and the R pin to HIGH. The output bits should now all show LOW.
