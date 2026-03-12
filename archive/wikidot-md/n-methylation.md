<!-- Original: http://lokeylab.wikidot.com/wiki:n-methylation -->
# Fmoc-N-Methylation
### applicable for non-basic side chains

**Overall Reaction**

This method describes the methylation of Fmoc protected amino acids. Aliphatic sidechains are well tolerated and the reaction scales nicely to the 10g scale.[1] Acid stable sidechain protecting groups can be employed for amino acids containing nucleophilic sidechains,[2] however, installing the methyl in sequence using the Mitsunobu [in-sequence methylation](in-sequence-methylation.md) is often preferred. A variety of other methods exist however none have been found in our hands to have the same scalability and ease of work up as the oxazolidinone route.[3]

#### Step 1: Oxazolidinone Formation

**Reaction Protocol:**
- Prepare an oil bath set to 140 C
- Weigh out a 1:1 mass ratio of paraformaldehyde to amino acid (e.g. if one is using 5g Fmoc-Leu-OH, 5g of paraformaldehyde would be required)
- Add Fmoc-AA and paraformaldehyde to a round bottom flask with a stirbar and add ~75mL of toluene per 5g of Fmoc-AA
- Place the charged round bottom flask in the oil bath and equip with a reflux condenser and let the reaction mixture stir while the oil bath comes to temp.
  - NOTE: the paraformaldehyde will not fully dissolve and will remain as a white solid in solution.
- Add 0.2eq of Camphorsulfonic Acid to the reaction and allow the system to stir at reflux for >2hrs
  - NOTE: during this time the paraformaldehyde will decompose and repolymerize on the flask and condensor walls, this is normal.
  - PRO-TIP: putting a little tinfoil jacket over the round bottom portion will aid in the reflux and resulting cleanup.
- After at least 2hrs, remove the reflux condenser and allow the system to condense to ~15mL per 5g of Fmoc-AA
- Remove the roundbottom from the oil bath and allow it to cool to room temp.

**Work Up:**
- Add ~25mL of EtOAC per 5g of Fmoc-AA and filter through a cotton plug to remove residual paraformaldehyde
- Wash with 2x Saturated NaHCO3 (shake the shit out of it)
- Wash with 1x brine
- Dry over your favorite drying agent (pros use NaSO4)
- Rotovap to a viscous oil or occasionally white solid.

**Example Reaction Table:**

| Name | g | MW | mmol | eq | d | mL |
|---|---|---|---|---|---|---|
| Fmoc-Leu-OH | 5 | 353.41 | 14.15 | 1 | n/a | n/a |
| paraformaldehyde | 5 | n/a | n/a | n/a | n/a | n/a |
| CSA | 0.657 | 232.3 | 2.83 | 0.2 | n/a | n/a |

#### Step 2: Reductive Ring Opening

**Reaction Protocol:**
- Add ~6-10mL of DCM per 5g of Fmoc-AA and a stir bar to the round bottom flask and try to suspend the oil as best you can
- Carefully add an equal amount of TFA and allow the solution to stir for ~5min at Room Temperature
- Add 3eq of Triethylsilane to the reaction mixture and allow to stir overnight.
  - PRO-TIP: A septa with a flaccid balloon can be placed on the flask to prevent evaporative loss but allow for gas evolution.

**Work Up:**
- Blow down the reaction mixture to remove the bulk of the TFA, DCM and excess TES. It should form a clear goopy oil.
- Bring the resulting oil back up in EtOAC and wash 2x with H2O (shake vigorously but not shit shaker status to avoid emulsion)
- Wash 1x with brine
- Dry over your favorite drying agent (pros use NaSO4)
- Rotovap to a viscous oil or occasionally white solid.
- Sometimes precipitation from Hexanes:EtOAc mixtures can work (normally around 80% Hexanes) or blowing down from a hexanes rich mixture.
  - Some have had luck with putting the precipitation mixture on dry ice and then blowing down. YMMV.

**Example Reaction Table:**

| Name | g | MW | mmol | eq | d | mL |
|---|---|---|---|---|---|---|
| Oxazole | 5 | 365.43 | 13.68 | 1 | n/a | n/a |
| TES | 4.773 | 116.28 | 41.05 | 3 | 0.728 | 6.556 |

**Bibliography:**
1. http://pubs.acs.org/doi/abs/10.1021/jo00149a016
2. http://www.sciencedirect.com/science/article/pii/S0040403901006062
3. http://pubs.acs.org/doi/pdf/10.1021/cr030024z
4. http://pubs.acs.org/doi/full/10.1021/jo050916u
