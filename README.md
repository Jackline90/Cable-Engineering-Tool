# Cable Engineering Tool

A Revit add-in for electrical cable routing, IEC-based cable sizing, engineering validation, and design reporting.

## Overview

Cable Engineering Tool supports electrical cable design workflows within Autodesk Revit by integrating model-data validation, cable routing, electrical calculations, and automated report generation into a unified workflow.

## Key Features

- **Revit Model Validation:** Checks relevant electrical and cable containment data before proceeding with design calculations.
- **Cable Routing:** Graph-based routing using Dijkstra's algorithm across supported cable containment elements.
- **Installation Environment Analysis:** Analyzes cable containment locations to determine installation ambient temperature conditions, supports temperature-factor assignment, and allows engineering review and adjustment of estimated values.
- **IEC-Based Cable Sizing:** Performs cable selection and electrical checks using implemented IEC equations and reference tables.
- **Electrical Calculations**: Performs voltage drop calculations, short-circuit current calculations, cable thermal withstand verification, circuit-breaker checks, neutral conductor sizing, and earthing conductor sizing.
- **Cable Installation Factors:** Considers installation temperature and cable grouping conditions when calculating cable current-carrying capacity.
- **Design Reporting:** Generates Excel reports for engineering review and validation.

## Technical Stack

- C#
- Autodesk Revit API
- .NET 8 / WPF
- MVVM
- Excel-based cable catalogue import
- IEC-based electrical calculation engines

## Documentation

- **Software Architecture Report:** Available in this repository.
- **IEC Equations and Calculation Methodology Report:** Available in this repository.
- **Testing Report:** Currently in preparation.

## Validation Status and Limitations

The tool is currently under development and testing. Its implemented calculations and workflows are being evaluated against defined test circuits and engineering reference criteria.

The current testing scope does not establish exhaustive validation across all possible electrical installations and edge cases.

## Project Status

**Version 1 — Engineering Development and Testing in Progress**

The source code is not included in this public portfolio repository.
