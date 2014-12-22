Updates for Invoice-Ninja
---


This is a fork of the original [invoice-ninja](https://github.com/nCrazed/invoice-ninja).

This fork introduces some new features, primarily some calculators for missing values. I'll make some pull requests as I go, to see if they make it into the official package.

The original is installed via NPM, but if you want to try the changes presented here you can clone this repo into your app in place of the original.

Planned features are:

* Calculators for rows (working on feature branch)
 * Plug in Quantity and Rate, and Amount is generated automatically
 * Same thing works for other values missing, supply two, the third is generated.
* Calculators for ending items:
 * Subtotal of all rows
 * Taxes based on percentage
 * Total Balance based on all previous fields