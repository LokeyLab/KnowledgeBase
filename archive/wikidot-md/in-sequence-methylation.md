<!-- Original: http://lokeylab.wikidot.com/in-sequence-methylation -->
# In Sequence Methylation
### applicable for all residues that have base stable sidechain protecting groups

**Overall Reaction**

This method describes the methylation of the terminal residue on a growing peptide chain on-resin. An electron withdrawing, reductively labile protecting group on the N-terminus activates the nitrogen for Mitsunobu chemistry. If Fmoc is present on the residue of interest a protecting group exchange is employed to install either the trifluoroacetamide (TFA) group or the ortho-Nitrobenzenesulfonyl (oNBS) group. The TFA group works well and is easily removed with NaBH4 and is the go-to method.[1] However the oNBS group has been observed to methylate more efficiently and is sometimes employed for very stubborn methylations due to sequence dependent effects or bulky sidechain protecting groups. The oNBS group is more difficult to remove with 2-mercaptoethanol (**BME**) and as such is used as a last resort.[2]

#### Step 1: Mitsunobu Reaction

**Reaction Protocol:**
- In advance prepare dry MeOH, DIAD, and THF
  - PRO-TIP: pouring ~10mL of MeOH and DIAD into oven dried scint vials with molecular sieves for at least 4hrs is good enough to dry the reagents and store for 1-2months if vessel is N2 purged and secured after use.
- Dissolve the PPh3 in a minimal amount of THF and the required dry methanol.
- Wash the resin 3x with dry THF
- Add the PPh3 and MeOH solution to the resin and make sure the volume is enough to cover all the resin but not more than 1.5x the volume of the resin.
- While agitating the synthesis vial add the DIAD dropwise.
  - NOTE: The DIAD addition is exothermic and will boil the THF if added too quickly.
  - PRO-TIP: a vortexer set on a LOW setting can be employed to provide vigorous agitation while adding. Brave chemists only.
- Allow the reaction to proceed for 15min
- Wash with DMF 2x, DCM 2x and Dry THF 3x and repeat the procedure
  - NOTE: It is wise to check the completion of the reaction by LCMS at this point to make sure all of the starting material has been methylated.
  - PRO-TIP: In very stubborn methylations it is sometimes advantageous to use dry DMF as a solvent. YMMV

**Example Reaction Table:**

| Name | g | MW | mmol | eq | d | mL |
|---|---|---|---|---|---|---|
| peptide | n/a | n/a | 0.25 | 1 | n/a | n/a |
| MeOH | 0.0801 | 32.04 | 2.5 | 10 | 0.791 | 0.101 |
| PPh3 | 252.83 | 202262.29 | 1.25 | 5 | n/a | n/a |
| DIAD | 0.253 | 202.21 | 1.25 | 5 | 1.027 | 0.246 |

#### Step 2: Protecting Group Removal

**Reaction Protocol:**

**For TFA:**
- Add ~2x resin volume of EtOH (dehydrated)
- Add a spatula scoop of NaBH4 and stir with spatula
- Allow the system to bubble on the benchtop for 45min - 1hr
  - NOTE: if there is not visible gas evolution after addition of the NaBH4 then your reagents may be bad.

**For oNBS:**
- Make a solution of BME (10eq) and DBU (5eq) in NMP in a minimal volume and add it to the resin.
- Agitate the resin by rocker or shaker for 5min
- Wash the resin once with NMP and repeat the procedure 2 more times
- Wash resin 3x DMF 3x DCM
- Check by LCMS and if starting material is present repeat the above procedure

**Example Reaction Table:**

| Name | g | MW | mmol | eq | d | mL |
|---|---|---|---|---|---|---|
| peptide | n/a | n/a | 0.25 | 1 | n/a | n/a |
| DBU | 0.190 | 152.24 | 1.25 | 5 | 1.018 | 0.187 |
| BME | 0.195 | 78.133 | 2.5 | 10 | 1.114 | 0.175 |

**Bibliography:**
1. http://pubs.acs.org/doi/abs/10.1021/ol402341u (DOI: 10.1021/ol402341u)
2. http://onlinelibrary.wiley.com/doi/10.1002/psc.711/abstract (DOI: 10.1002/psc.711)
