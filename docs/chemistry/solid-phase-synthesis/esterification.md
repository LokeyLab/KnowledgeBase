# Solid-Phase Esterification

This protocol describes the formation of ester bonds on solid phase for the synthesis of depsipeptides (peptides containing at least one ester bond in place of an amide bond).

## Overview

Solid-phase esterification is a two-step process:

1. **Hydroxy acid coupling** -- The hydroxy acid is coupled to the resin-bound peptide using standard amide coupling conditions.
2. **Esterification** -- The next amino acid is coupled to the hydroxyl group via DIC/DMAP-mediated ester formation.

## Step 1: Hydroxy Acid Coupling

Couple the hydroxy acid to the free amine of the resin-bound peptide using standard coupling conditions:

- **Reagents:** DIPEA, HOAt, HATU
- **Solvent:** DMF
- **Conditions:** Standard SPPS coupling (e.g., 2 eq amino acid, 2 eq HATU, 2 eq HOAt, 4 eq DIPEA in DMF, 1-2 hours)

!!! note
    The hydroxy acid is coupled through its carboxylic acid to the free amine on resin, just like a standard amino acid coupling. The free hydroxyl group will serve as the nucleophile for the subsequent esterification step.

## Step 2: Esterification (DIC/DMAP)

!!! warning "Dry Technique Required"
    This step requires anhydrous conditions. Use dry THF and ensure all glassware and resin are thoroughly dried before proceeding.

1. Wash the resin 3x with dry THF.
2. Dissolve the Fmoc-amino acid (5 eq) and DMAP (0.5 eq) in a minimal volume of dry THF.
3. Add DIC (5 eq) to the solution.
4. Add the solution to the resin.
5. Agitate overnight at room temperature.
6. Wash resin 3x DMF, 3x DCM.
7. Check by LCMS for completion. Repeat if necessary.

## Notes on Depsipeptide Synthesis

!!! warning "TFA Sensitivity"
    Ester bonds in depsipeptides are sensitive to TFA. During global deprotection with TFA cocktails, some ester bond cleavage may occur. Minimize TFA exposure time when working with depsipeptides.

!!! note "Fmoc Deprotection with HOBt"
    When performing Fmoc deprotection on a residue adjacent to an ester bond, include HOBt in the deprotection cocktail. The free piperidine generated during Fmoc removal can undergo aminolysis of the ester bond. HOBt acts as a scavenger to suppress this side reaction. A typical cocktail is 2% piperidine, 2% DBU, and 2% HOBt in DMF.
