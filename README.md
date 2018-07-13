# corpActions

Being a budding quant trader, one of the initial challenges I faced was adjusting daily values of NSE scrips when corporate action occurred.

The key corporate actions when there is a big price correction happen are
1. Bonuses
2. Splits

The corporate correction adjustment factors in corpActions.csv to apply adjustments to historic data

How to use?
Apply adjustment factors (3rd column) to all historic values 'before' the Ex-Date (first column). The scrip names are in second column

To start, the list only contains adjustments for current set of FnO scrips. Looking forward to contributors in expanding the list!

