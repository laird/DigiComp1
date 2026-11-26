# Digi-Comp I (3D-printable)

Source materials for a 3D-printable replica of the [Digi-Comp I](https://en.wikipedia.org/wiki/Digi-Comp_I), the 1960s plastic mechanical computer that ran programs with sliding and flipping parts.

This repository holds scans, CAD, and the original manual. It is a materials archive, not a ready-to-print kit with a single BOM and slicer profile.

## What's in the repo

- `manual/` — original documentation
- `Parts Scans/` — scans of the physical parts
- `DXF Files/` — 2D profiles
- `AutoCAD Drawings/` — CAD drawings
- `Digicomp Romps/` — page scans of the Digi-Comp I ROMPS game and problem book (front cover, table of contents, pages 1–32, and back cover)

## Get started

```bash
git clone https://github.com/laird/DigiComp1.git
cd DigiComp1
```

1. Read the files in `manual/` to learn how the machine is supposed to work.
2. Open the DXF or AutoCAD drawings in a CAD tool, or inspect the part scans, and build printable solids from them.
3. Export STLs and slice them for your printer.

There is no one-click "print the whole computer" model in this tree. If you add OpenSCAD or STL parts later, link them from this README.

## Further reading

- Historical site and materials: [noah.org/digicomp](https://www.noah.org/digicomp/)
- How the mechanism works: [Jack Crenshaw, "How can they learn?", Embedded.com](https://www.embedded.com/how-can-they-learn/)

(The older `http://www.embedded.com/electronics-blogs/programmer-s-toolbox/4025030/How-can-they-learn-` URL no longer serves the article reliably.)

## License

This repo has no license file. Some of the contents are scans of historical materials and may not be yours to relicense. Add a license for any original CAD or models you contribute, and keep third-party documents clearly attributed.
