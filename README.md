# BPRC - Broke Protocol Randomizer Tool

BPRC randomizes the rotation of objects in Broke Protocol maps to create more natural forests and bushes.

---

## Features

- Randomize rotation of selected objects  
- Add custom objects via `trees.json`  
- Object preview with images  
- Multiple themes and languages  

---

## Usage

1. Open BPRC and select any map file on your computer.  
2. Select/deselect objects to randomize.  
3. Add custom objects to `trees.json` using:  

   ```json
   ["ObjectName", ObjectID, "ImageURL"]

    Calculate ObjectID as the decimal CRC32 of the object name (e.g. via https://simplycalc.com/crc32-text.php)

    Use any valid image URL for preview

    Apply random rotation changes to your map.

Notes

    Only rotation is randomized, position stays the same.

    Backup your map before applying changes.

Thanks for using BPRC!
