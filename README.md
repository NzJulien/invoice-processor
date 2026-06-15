# Multimodal AI Invoice Processor

> Upload any invoice image and instantly extract structured data using Claude Vision AI.

## Live Demo

https://nzjulien.github.io/invoice-processor

## What it does

Drop in any invoice (JPG, PNG, WEBP) and the AI extracts:

- Vendor info (name, address, email, phone, tax ID)
- Invoice metadata (number, date, due date, PO number, currency)
- Bill-to details
- All line items (description, quantity, unit price, total)
- Totals breakdown (subtotal, tax, discount, shipping, grand total)
- Payment info (bank, IBAN, SWIFT, terms)
- Confidence score + AI notes

## Export Options

- JSON download
- CSV export (line items)
- Copy JSON to clipboard

## Stack

- Vanilla HTML/CSS/JS
- Claude claude-sonnet-4-6 Vision API (multimodal)
- Zero dependencies, zero backend

## Setup

1. Open the live demo
2. Enter your Anthropic API key (sk-ant-...)
3. Drop any invoice image
4. Click Extract

Made by NzJulien
