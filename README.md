# Handover Analyzer

A Raspberry Pi based WiFi coverage and handover analysis project for evaluating wireless infrastructure inside McDonnell Douglas Hall.

The project used a Raspberry Pi 3B+ with an Alfa monitor mode WiFi adapter to collect passive wireless scan data across hundreds of survey locations. The collected data was processed with Python, pandas, and matplotlib to evaluate signal strength, access point visibility, handover coverage, dead zones, and overall network performance.

## Project overview

Wireless coverage can look fine from a controller dashboard while still causing real issues for users in hallways, classrooms, labs, and basement areas. This project measured WiFi performance from the user side using low cost embedded hardware and field collected scan data.

The goal was to create a repeatable process for collecting, processing, and analyzing WiFi coverage data across a building.

## Hardware

- Raspberry Pi 3B+
- Alfa monitor mode WiFi adapter
- Portable power source
- Laptop for analysis and reporting

## Tools and libraries

- Python
- pandas
- matplotlib
- aircrack-ng
- monitor mode wireless scanning
- Raspberry Pi OS

## Data collected

Across the survey, the system collected:

- 952 survey points
- 194,742 wireless measurements
- 54 physical access points
- 1,111 BSSIDs
- 142 SLU-users radios

## Main findings

The analysis showed:

- 98.6 percent handover coverage
- Zero detected dead zones
- Over 95 percent of surveyed locations reporting good to excellent signal strength
- Strong access point visibility across most of the measured building areas

## What this repo includes

- Wireless scanning methodology
- Data processing scripts
- Measurement analysis workflow
- Project documentation
- Summary of network coverage and handover results

## Skills demonstrated

- Raspberry Pi based field measurement
- Wireless network analysis
- Passive WiFi scanning
- Python data processing
- pandas based data cleaning
- matplotlib visualization
- Signal strength analysis
- Infrastructure reporting

## Notes

This project was completed as a computer networks field analysis project. It demonstrates how low cost embedded hardware and Python analysis tools can be used to evaluate real wireless infrastructure from the user perspective.
