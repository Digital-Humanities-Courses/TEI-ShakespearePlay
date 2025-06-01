# TEI-ShakespearePlay 

Romeo and Juliet TEI Encoding Project

A project by Qendrese Buza and Rrona Abrashi, students at the University of Geneva.

## Project Overview
This project involves the TEI (Text Encoding Initiative) encoding of selected acts from Romeo and Juliet by William Shakespeare. The work was done as part of our coursework in Digital Humanities at the University of Geneva.

We used TEI-XML to mark up the dramatic structure and relevant textual features of the play, following the guidelines provided in the Roma customization tool (ODD). The XML files were edited using Visual Studio Code and validated through the Oxygen XML Editor.

## What We Did
- Qendrese Buza encoded Act 2 of Romeo and Juliet using TEI.

- Rrona Abrashi encoded Act 1 of Romeo and Juliet using TEI.
Each act was encoded in a separate XML file, following a shared TEI customization schema created via Roma.

## Repository Structure
This repository contains the following:

- act1.xml — Act 1 TEI-encoded (by Rrona Abrashi)

- act2.xml — Act 2 TEI-encoded (by Qendrese Buza)

- tei_minimal.odd — Custom ODD schema (TEI customization)

- tei_minimal.rng — Relax NG schema generated from the ODD file

- README.md — Project description and documentation

## How We Did It
### Customization with Roma (ODD):
We created a minimal TEI customization for drama by selecting the necessary modules (core, header, textstructure, and drama).

### Encoding:
Acts 1 and 2 were encoded manually in XML using TEI elements like 'div', 'sp', 'speaker', 'stage', and more.

### Validation:
Each file was validated in Oxygen XML Editor using the custom Relax NG schema.

## Credits
This project was developed as part of the Digital Humanities curriculum at the University of Geneva.
