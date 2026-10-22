# Quotation Calculator

A lightweight, browser-based tool for estimating job costs in Kenyan shillings (KES). Enter a job type, material cost, labour days, and daily labour rate to calculate labour, 16% VAT, and the estimated total.

## Requirements

- A modern web browser with JavaScript enabled
- No installation, build step, server, or internet connection

## Setup

1. Download or copy `QUOTATION_CALCULATOR.html`.
2. Open the file in a modern web browser.

The calculator runs locally in the browser. No data is uploaded or saved.

## Usage

1. Enter a job type or description.
2. Enter the material cost in KES.
3. Enter the labour duration in days and the daily labour rate in KES.
4. Select **Calculate quotation**.
5. Review the displayed materials, labour, VAT, and total.

All numeric inputs are required and must be zero or greater. Labour days use half-day increments. The VAT rate is fixed at 16%. VAT and the total are rounded independently to the nearest whole shilling; materials and labour are shown using the browser's number formatting.

## Calculation

- Labour = labour days × daily labour rate
- Subtotal = material cost + labour
- VAT = subtotal × 16%
- Total = subtotal + VAT

This provides an estimate, not an accounting or tax-compliance result. Confirm the applicable VAT rate and rounding approach for your business before using an estimate as a formal quotation.
