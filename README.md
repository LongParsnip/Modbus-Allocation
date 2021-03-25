# Modbus-Allocation, v1.01
This is an automated excel modbus allocation sheet I made for managing allocations when working with a PanelView PV800 and Micro800 PLC.

## Version Summary:
* v1.00: Original Release
* v1.01: Code speed execution improved, automatic list generation added.

## Instructions:
1. Download sheet.
2. Ensure macros are enabled.
3. I have left my last project prefilled as a guide, press the 'Clear Register' button to clear the register.
4. Enter your Variable names in the 'Var Name' column, select the data table they belong to and if the register width is not 1 (for REAL types) then enter 2 as the register width.
5. Modbus register list will update as you go.



## Warnings:
1. Do not insert rows or move existing allocations around / reorder the var names. The allocations are made sequentially, if you move anything the addresses will change.
2. Do not add/remove columns, the ranges are specified as hard strings so unless you want to go and update the VBA project manually don't do this.
