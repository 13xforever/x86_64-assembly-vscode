## 3.1.5
* Mnemonics for IBPB/IBHF

## 3.1.4
* Updates to NASM syntax up to 2.16.01 (still incomplete compared to new Sublime Text definitions)

## 3.1.1
Mnemonics update
* All extensions previously marked as future, are now incorporated to the main grammar namespace
* Current as of Intel Software Developer's Manual, June 2023
* Added Intel APX to future extensions section
* General minor syntax fixes

## 3.0.0
Following the request, language id that this package provides, was changed to be more unique.
This means some associations, custom language configuration options, and possible embedded language scopes might be reset or stop working.

## 2.3.0
Following the complete rewrite of the grammer for Sublime Text 3, this updates brings some backported changes and fixes to the legacy highlighter

## 2.2.11
Better support for datatypes
* signed types (non-nasm)
* better support for various number notations (bin, oct, dec, hex, and packed bcd)
* better support for strings
* more built-in nasm functions for type convertion and constants

## 2.2.8
Fixed highlighting conflict for ah-dh registers with hex numbers

## 2.2.4
Expanded NASM macro support
Partial support for GAS comment style

## 2.2.3
Fixed missing AMD instructions, including support for Zen

## 2.2.2
Overhauled highlighting for sections, labels, prefixes, and numbers

## 2.1.15
Intel CFE extensions

## 2.1.10
Updated with PKRU instructions

## 2.1.6
Updated the extension to support Visual Studio Code Marketplace

## 2.1.5
Small highlighting fix for some FPU instructions

## 2.1.2 - First Release for Visual Studio Code
As of right now, this bundle have:
* Basic support for nasm/yasm/tasm/gas syntaxes
* Most of the modern instruction sets (including Intel SHA/MPX/SGX)
