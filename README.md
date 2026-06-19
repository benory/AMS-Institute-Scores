# AMS Institute Scores

This repository contains digital score encodings for works attributed to Renaldo, prepared in Humdrum `**kern` format.

The corpus currently includes mass movements and motets, with many files associated with the manuscript source Bologna Q19.

## Contents

The repository consists of `.krn` files encoded in Humdrum `**kern`.

The collection includes:

- Mass movements from *Missa Sine nomine*
- Mass movements from *Missa Benedictus Dominus Deus*
- Motets for four and five voices

## File Format

Each score is encoded as a Humdrum `**kern` file. The files include standard Humdrum reference records such as:

- `!!!id` - repository identifier
- `!!!AGN` - genre or liturgical category
- `!!!voices` - number of voices
- `!!!COM` - composer
- `!!!SMS` - source manuscript, where applicable
- `!!!OPR` - parent work, for mass movements
- `!!!OTL` - title

Voice parts are encoded as separate `**kern` spines, typically ordered from lower to higher voices, such as Bassus, Tenor, Altus, and Superius.

## Naming Convention

Filenames generally follow this pattern:

```text
Ren<ID>-<Title>-<Movement>--<Source>.krn
