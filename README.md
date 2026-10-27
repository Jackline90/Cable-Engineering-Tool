# Cable Engineering Tool
A Revit add-in for electrical cable routing, IEC-based cable sizing, engineering validation, and design reporting.

## Overview

Cable Engineering Tool supports electrical cable design workflows within Autodesk Revit, combining model-data validation, cable routing, electrical calculations and reports exporting in one integrated workflow.

## Key Features

- **Revit Model Validation:** Checks relevant electrical and containment data before design calculations.
- **Cable Routing:** Graph-based routing using the Dijkstra algorithm across supported cable containment elements.
- **IEC-Based Cable Sizing:** Cable selection and electrical checks using implemented IEC equations and reference tables.
- **Electrical Calculations:** Voltage drop, short-circuit withstand, breaker , neutral conductor sizing, and earthing conductor sizing.
- **Installation Conditions:** Considers environmental temperature and cable grouping factors in cable sizing.
- **Design Reporting:** Generates Excel reports for engineering review and validation.

## Technical Stack

- C#
- Autodesk Revit API
- .NET 8 / WPF
- MVVM
- Excel-based cable catalogue import
- IEC-based electrical calculation engines

## Documentation

- Software Architecture Report — available in this repository.
- IEC Equations and Calculation Methodology Report — available in this repository.
- Testing Report — currently in preparation.

## Validation Status and Limitations

The tool is under development and testing. Its implemented calculations and workflows are being evaluated against defined test circuits and engineering reference criteria. The current testing scope does not establish exhaustive validation across all possible electrical installations and edge cases.

## Project Status

Version 1 — engineering development and testing in progress.

The source code is not included in this public portfolio repository.
