<!-- Original: http://lokeylab.wikidot.com/shake-flask-logk -->
# Shake Flask LogK

## Introduction

Experimental determination of lipophilicity is most commonly carried out using a "shake flask" method where the analyte of interest is dissolved in a bi-phasic mixture of two immiscible liquids and after the system reaches equilibrium the concentrations of the analyte are measured in each phase. Then, the logarithm of the ratio of The most common solvent system is Octanol/Water which has become the standard experimental measure of lipophilicity in the medicinal chemistry space often called the partition coefficient, P_oct/w.

The choice of this system was largely based on the insolubility of compounds in pure hydrocarbon systems and by introducing a hydrogen bond donor into the lipophilic phase, the scope of compounds that could be measured by insensitive detection techniques (ie UV absorbance) was increased. However, the inner, dry region of cell membranes is devoid of any hydrogen bonding groups so a more accurate solvent system to predict cell permeation is a water/hydrocarbon system. This is frequently referred to as K_hc/w. Anderson et. al. found a very good correlation between 1,9-decadiene and liposome permeability assays and as such we have employed it as the standard "HC" phase.

The logK is simply the log_10 of the ratio of the concentrations in each phase: logK_{hc/w} = log_{10}(C_{hc}/C_w)

## Assay Procedure

In general the assay has 3 major steps: 1) Sample prep 2) Separating the two layers and 3) quantification and analysis.

### Sample Prep

The total assay volume is ~1mL and done in an eppendorf(epitube)/micro-centrifuge tube.

1. Pre-saturate each phase by putting ~10mL of 1xPBS and ~10mL of hydrocarbon (ie 1,9-decadiene) in a scintillation vial and shake. Allow emulsion to separate.
2. Either lyophilize ~10nmol of compound in an epitube or put 1uL of a 10mM DMSO stock into an epitube.
3. From the pre-saturated PBS/HC vial, pipette 500uL of each into the epitube.
4. Sonicate the epitube with the analyte of interest and the two phases for 30min. An opaque emulsion will likely form.
5. Allow the sonicated mixture to sit overnight (~16hrs) to come the thermodynamic solubility product.

Note: care must be taken to minimize the amount of DMSO in the mixture. Even 1uL has a marginal effect on the result, no more than that should be included.

### Aliquot Layers

This is the most delicate part of the assay and great care must be taken in regards to technique. Even minor pipetting error can result in considerable experimental error.

1. Briefly centrifuge the epitubes to fully separate the layers and any precipitate is pelleted (16k g for 4min).
2. Carefully pipette 250uL from the top (HC) layer and dispense into a labeled epitube.
3. With a new tip, pipette 250uL from the lower aqueous layer by carefully submerging the tip into the lower aqueous portion in the middle of the tube. Do not allow the tip to contact the walls or the bottom of the tube while drawing up the aliquot. If there is a film of precipitate at the interface of the two layers, the total solubility of the compound in both phases may be too low to accurately measure.
4. (optional) Gently wipe the exterior of the pipette tip with a clean kimwipe making sure not to wick any solution from the inside of the tip.
5. Dispense the aliquot into a fresh, labeled epitube.
6. Evaporate the aliquots by either: 1) blowdown using compressed air or 2) speedvac (ie Genevac) by supporting the tubes in larger conical tubes that fit the instrument.

### Quantification and Analysis

1. Reconstitute the aliquots using an equal volume of solvent that is compatible with the detection instrumentation and will fully dissolve the compound. For our compounds, 100uL of ACN should do the trick.
2. Quantitate by the detection method of your choice.

Note: The salts in the PBS (aqueous) aliquot probably won't dissolve in the ACN. Make sure you aggressively triturate/sonicate and spin down before quantitating.

Quantification is normally performed by integrating a MS peak on a LC/MS spectrum. Since the assay is ratiometric any ionization efficiency discrepancies between species should not be an issue. However, MS detection often has a limited linear range. This is something that we blissfully ignore most of the time but a truly rigorous scientist would make a dilution series of the analyte and use the best fit to determine concentration in each phase.

## Future Work

As the wise post-doc, Aki, pointed out, the use of 1,9-decadiene may be overkill and not add much rigor to the experiment. It does add cost and time since it has a very high boiling point. It might be worth taking a look at a series of analyte's logK values in a variety of hc solvents that have lower boiling points like hexanes, cyclohexane, dodecane, etc.
