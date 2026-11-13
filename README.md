# Forensic Evidence Bench

A single-file, offline, browser-based teaching bench for digital evidence integrity.
Prepared by Nawar Alseelawi for the awareness workshop at the University of Basra,
College of Engineering, Department of Electrical Engineering.

Live page: https://nawaralseelawi.github.io/forensic-evidence-bench/

## What it does

- Computes SHA-256, SHA-1 and SHA-512 of any file with the Web Crypto API.
- Compares a file hash against a reference hash and shows the number of differing bits out of 256 (avalanche effect).
- Detects the true file type from magic bytes, independent of the extension.
- Reads EXIF and PDF metadata.
- Runs Error Level Analysis (ELA) on JPEG images.
- Compares two images pixel by pixel.

## What it does not do

- It is not a deepfake detector and it gives no "fake probability" score.
- It does not decide whether evidence is authentic. It exposes technical indicators that a qualified examiner must interpret.

## Privacy

Everything runs locally in the browser. No file leaves the device, there is no backend and no analytics.

## Test pack

`Basra_Test_Pack.zip` holds sample files for every panel (hash and bit difference, true file type, EXIF, ELA, PDF metadata, pixel comparison) with a short guide inside.
Direct download: https://nawaralseelawi.github.io/forensic-evidence-bench/Basra_Test_Pack.zip

Transfer the zip itself, not the extracted files, through messaging apps: they rewrite file dates and strip metadata.

## Usage

Open `index.html` in any modern browser, online through the live page or offline from a local copy.
