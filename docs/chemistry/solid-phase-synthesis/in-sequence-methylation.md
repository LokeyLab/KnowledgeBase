# In-Sequence Methylation

### Applicable for all residues with base-stable side chain protecting groups

## Overall Reaction

This method describes the methylation of the terminal residue on a growing peptide chain on-resin. An electron-withdrawing, reductively labile protecting group on the N-terminus activates the nitrogen for Mitsunobu chemistry. If Fmoc is present on the residue of interest, a protecting group exchange is employed to install either the trifluoroacetamide (TFA) group or the ortho-nitrobenzenesulfonyl (oNBS) group.

The TFA group works well and is easily removed with NaBH4 and is the go-to method.[^1] However, the oNBS group has been observed to methylate more efficiently and is sometimes employed for very stubborn methylations due to sequence-dependent effects or bulky side chain protecting groups. The oNBS group is more difficult to remove with 2-mercaptoethanol (BME) and as such is used as a last resort.[^2]

## Step 1: Mitsunobu Reaction

### Reaction Protocol

1. In advance, prepare dry MeOH, DIAD, and THF.

    !!! tip
        Pouring ~10 mL of MeOH and DIAD into oven-dried scintillation vials with molecular sieves for at least 4 hours is good enough to dry the reagents and store for 1-2 months if the vessel is N2-purged and secured after use.

2. Dissolve the PPh3 in a minimal amount of THF and the required dry methanol.
3. Wash the resin 3x with dry THF.
4. Add the PPh3 and MeOH solution to the resin and make sure the volume is enough to cover all the resin but not more than 1.5x the volume of the resin.
5. While agitating the synthesis vial, add the DIAD dropwise.

    !!! warning
        The DIAD addition is exothermic and will boil the THF if added too quickly.

    !!! tip
        A vortexer set on a LOW setting can be employed to provide vigorous agitation while adding. Brave chemists only.

6. Allow the reaction to proceed for 15 min.
7. Wash with DMF 2x, DCM 2x, and dry THF 3x, then repeat the procedure.

    !!! note
        It is wise to check the completion of the reaction by LCMS at this point to make sure all of the starting material has been methylated.

    !!! tip
        In very stubborn methylations, it is sometimes advantageous to use dry DMF as a solvent. Your mileage may vary.

### Example Reaction Table

| Name | g | MW | mmol | eq | d | mL |
|---|---|---|---|---|---|---|
| Peptide | n/a | n/a | 0.25 | 1 | n/a | n/a |
| MeOH | 0.0801 | 32.04 | 2.5 | 10 | 0.791 | 0.101 |
| PPh3 | 252.83 | 202262.29 | 1.25 | 5 | n/a | n/a |
| DIAD | 0.253 | 202.21 | 1.25 | 5 | 1.027 | 0.246 |

## Step 2: Protecting Group Removal

### For TFA Group

1. Add ~2x resin volume of EtOH (dehydrated).
2. Add a spatula scoop of NaBH4 and stir with spatula.
3. Allow the system to bubble on the benchtop for 45 min to 1 hour.

    !!! note
        If there is not visible gas evolution after addition of the NaBH4, then your reagents may be bad.

### For oNBS Group

1. Make a solution of BME (10 eq) and DBU (5 eq) in NMP in a minimal volume and add it to the resin.
2. Agitate the resin by rocker or shaker for 5 min.
3. Wash the resin once with NMP and repeat the procedure 2 more times.
4. Wash resin 3x DMF, 3x DCM.
5. Check by LCMS and if starting material is present, repeat the above procedure.

### Example Reaction Table (oNBS Removal)

| Name | g | MW | mmol | eq | d | mL |
|---|---|---|---|---|---|---|
| Peptide | n/a | n/a | 0.25 | 1 | n/a | n/a |
| DBU | 0.190 | 152.24 | 1.25 | 5 | 1.018 | 0.187 |
| BME | 0.195 | 78.133 | 2.5 | 10 | 1.114 | 0.175 |

## Bibliography

1. [Biron et al., Org Lett 2013](http://pubs.acs.org/doi/abs/10.1021/ol402341u) (DOI: 10.1021/ol402341u)
2. [Miller et al., J Pep Sci 2006](http://onlinelibrary.wiley.com/doi/10.1002/psc.711/abstract) (DOI: 10.1002/psc.711)

[^1]: http://pubs.acs.org/doi/abs/10.1021/ol402341u
[^2]: http://onlinelibrary.wiley.com/doi/10.1002/psc.711/abstract
