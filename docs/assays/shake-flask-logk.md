# Shake Flask LogK

## Introduction

Experimental determination of lipophilicity is most commonly carried out using a "shake flask" method where the analyte of interest is dissolved in a biphasic mixture of two immiscible liquids. After the system reaches equilibrium, the concentrations of the analyte are measured in each phase. The logarithm of the ratio of the concentrations gives the partition coefficient. The most common solvent system is octanol/water, which has become the standard experimental measure of lipophilicity in medicinal chemistry, often called the partition coefficient, P_oct/w.

The choice of this system was largely based on the insolubility of compounds in pure hydrocarbon systems. By introducing a hydrogen bond donor into the lipophilic phase, the scope of compounds that could be measured by insensitive detection techniques (e.g., UV absorbance) was increased. However, the inner, dry region of cell membranes is devoid of any hydrogen bonding groups, so a more accurate solvent system to predict cell permeation is a water/hydrocarbon system. This is frequently referred to as K_hc/w. Anderson et al. found a very good correlation between 1,9-decadiene and liposome permeability assays, and as such we have employed it as the standard "HC" phase.

The logK is simply the log₁₀ of the ratio of the concentrations in each phase:

```
logK_hc/w = log₁₀(C_hc / C_w)
```

## Assay Procedure

In general the assay has three major steps:

1. Sample prep
2. Separating the two layers
3. Quantification and analysis

### Sample Prep

The total assay volume is ~1 mL and is done in an Eppendorf (epitube) / micro-centrifuge tube.

1. Pre-saturate each phase by putting ~10 mL of 1× PBS and ~10 mL of hydrocarbon (e.g., 1,9-decadiene) in a scintillation vial and shake. Allow the emulsion to separate.
2. Either lyophilize ~10 nmol of compound in an epitube, or put 1 uL of a 10 mM DMSO stock into an epitube.
3. From the pre-saturated PBS/HC vial, pipette 500 uL of each into the epitube.
4. Sonicate the epitube with the analyte of interest and the two phases for 30 min. An opaque emulsion will likely form.
5. Allow the sonicated mixture to sit overnight (~16 hrs) to reach the thermodynamic solubility product.

!!! warning
    Care must be taken to minimize the amount of DMSO in the mixture. Even 1 uL has a marginal effect on the result — no more than that should be included.

### Aliquot Layers

!!! warning
    This is the most delicate part of the assay. Great care must be taken with technique — even minor pipetting error can result in considerable experimental error.

1. Briefly centrifuge the epitubes to fully separate the layers and pellet any precipitate (16k × g for 4 min).
2. Carefully pipette 250 uL from the top (HC) layer and dispense into a labeled epitube.
3. With a new tip, pipette 250 uL from the lower aqueous layer by carefully submerging the tip into the lower aqueous portion in the middle of the tube. Do not allow the tip to contact the walls or the bottom of the tube while drawing up the aliquot. If there is a film of precipitate at the interface of the two layers, the total solubility of the compound in both phases may be too low to accurately measure.
4. (Optional) Gently wipe the exterior of the pipette tip with a clean Kimwipe, making sure not to wick any solution from the inside of the tip.
5. Dispense the aliquot into a fresh, labeled epitube.
6. Evaporate the aliquots by either:
    - Blowdown using compressed air, or
    - SpeedVac (e.g., Genevac) by supporting the tubes in larger conical tubes that fit the instrument.

### Quantification and Analysis

1. Reconstitute the aliquots using an equal volume of solvent that is compatible with the detection instrumentation and will fully dissolve the compound. For our compounds, 100 uL of ACN should work.
2. Quantitate by the detection method of your choice.

!!! note
    The salts in the PBS (aqueous) aliquot probably will not dissolve in ACN. Make sure you aggressively triturate/sonicate and spin down before quantitating.

!!! note
    Quantification is normally performed by integrating an MS peak on an LC/MS spectrum. Since the assay is ratiometric, any ionization efficiency discrepancies between species should not be an issue. However, MS detection often has a limited linear range. A truly rigorous approach would be to make a dilution series of the analyte and use the best fit to determine concentration in each phase.

## Future Work

As noted by Aki, the use of 1,9-decadiene may be overkill and not add much rigor to the experiment. It does add cost and time since it has a very high boiling point. It might be worth examining a series of analytes' logK values in a variety of hydrocarbon solvents that have lower boiling points, such as hexanes, cyclohexane, dodecane, etc.

---

## Alternative Procedure

This section describes an alternative logK protocol with slightly different volumes and timing.

### Prepare Ahead of Time

Add 1× PBS and 1,9-decadiene to a vial and vortex to saturate the decadiene with water and vice versa. Let stand (it takes about an hour for the layers to separate). Refrigerate if desired.

!!! tip
    Dilute your samples ahead of time. Volumes cannot be accurately dispensed below 5 uL, so dilute concentrated stocks in a stepwise manner. Stock concentrations of 200 uM work well for logK, PAMPA, and fSol.

### The Assay

Your compound of interest will be partitioned between decadiene (a hydrocarbon) and 1× PBS. The logarithm of the ratio [sample]_decadiene : [sample]_1×PBS is logK.

LogK experiments don't need to be a full mL but should be at least 500 uL. A total of 600 uL works well (300 uL each of 1× PBS and decadiene).

1. Place 3 uL of your 200 uM sample in an empty 1.5 mL Eppendorf.
2. Vortex your samples right before dispensing.
3. Place 300 uL each of 1× PBS and decadiene (from the pre-saturated layers) into the Eppendorf.
4. Vortex for 20 minutes.
5. Sonicate for 20 minutes.
6. Centrifuge for 20 minutes on maximum speed (14,000 rpm).

The layers are now separated.

### Separating the Layers

!!! warning
    Be very careful when separating the layers. Slight contamination of the aqueous layer with decadiene will be a big problem.

Transfer 100–150 uL of each layer into a separate Eppendorf. It does not matter which volume you choose, but you should collect the same volume of each.

- **Top (HC) layer:** Pipette from the middle of the layer. Do not let the tip touch the sides of the Eppendorf.
- **Bottom (aqueous) layer:** Pull a tiny bit of air into the tip, and expel once you are in the center of the aqueous layer. This prevents decadiene from being pulled into the aqueous aliquot. Once you have pulled your volume, consider wiping the outside of the tip with a Kimwipe before releasing into the separate Eppendorf.

### Evaporation and Reconstitution

Evaporate the solvent overnight. You can use the Genevac or do a blowdown.

The next day:

- **Decadiene layer:** Add 100 uL of DMSO. This can go directly on the Orbitrap.
- **PBS layer:** Take up in 100 uL DMSO, then vortex, sonicate, and centrifuge. Withdraw some DMSO without disturbing the pellet — this can go on the Orbitrap.
