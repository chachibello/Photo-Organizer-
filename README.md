# Photo-Organizer-

## Overview
A command-line tool that scans a folder of images and automatically organizes them into subfolders by date (YYYY/MM). Falls back to file modified time if EXIF data is missing.

## Features
- Dry-run mode (`--dry-run`)
- Moves images to `YYYY/MM/`
- Generates a `report.json` summary

## Next Steps
- Implement EXIF parser
- Add error handling
- Add unit tests
