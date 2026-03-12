# Parallel Artificial Membrane Permeability Assay (PAMPA)

## Product List

### Equipment

- 96-well Teflon block acceptor plate (Millipore MSSACCEPT0R)
- 96-well 0.45 um Teflon membrane donor plates (Millipore MAIPNTR10 or MAIPN4550)
- 96-well plates for HPLC-MS sampling (optional)
- 96-well plate seals — heat or sticky aluminum foil (optional)
- Deep-well (~2 mL) 96-well plate (optional)
- Development chamber (e.g., desiccator chamber without desiccant)
- 12-channel pipette, 50–300 uL (optional)
- Many extra tips, pre-racked
- Multichannel pipette solvent wells

### Chemicals

- Analytes, 200 uM in DMSO
- Lecithin (reasonably high purity is important; 90% is affordable and satisfactory)
- Dodecane (99+% purity)
- 1× PBS pH 7.4 buffer
- Methanol
- DMSO
- Propranolol, 200 uM in DMSO (optional)

## Process

### Overview

1. Prepare solutions
2. Prepare membrane plate
3. Load sample plates
4. Run assay
5. Prepare analytical samples
6. Analyze / Calculate

### Notes

The PAMPA assay is standardized to use **5% DMSO in all solutions**, increasing ease and efficiency for DMSO stocks.

**Target Concentration:** 1 uM (Orbitrap) or 10 uM (LTQ)

**Sample Limit (quadruplicate):** 24 compounds per 96-well plate

Multichannel recommended (but not necessary).

**Permeability Standards:**

| Compound | Pe (×10⁻⁶) | Std Dev | Comments |
|---|---|---|---|
| Propranolol | ? | ? | Polar; might not elute in certain chromatography methods |
| Progesterone | 7.0 | 2.4 | |
| Carbamazepine | 9.0 | 0.5 | Also useful as hydrocarbon partition coefficient standard |
| 1NMe3 | 3.0 | 1.0 | |
| CSA | 0.5 | 0.2 | |

!!! warning "Time-sensitive steps"
    There are two periods where the assay is time-sensitive — reserve some undistracted time:

    - Everything between preparing the donor plate membrane and starting the assay.
    - Transferring solutions from the finished assay to sealed plates/vials for analysis.

!!! tip
    It can be very helpful to create a plate layout spreadsheet with exact masses annotated.

### Prepare Solutions

Prepare target analyte (typically from a stock concentration in DMSO) to a dilution of 1–10 uM in a buffer of **1× PBS pH 7.4 and 5% DMSO**.

- If analyte is 200 uM in DMSO: add 50 uL to 950 uL of 1× PBS.
- Preparing these in deep-well plates makes later transfer (with a multichannel pipette) easier.
- Mix well with pipette.
- Be sure to calculate enough volume for preparing the recovery plate from this stock!

Prepare a 1% lecithin in dodecane solution in an Eppendorf tube, and sonicate until fully mixed (~5 min).

- 10 mg of lecithin in 1 mL of dodecane.
- Always prepare fresh.

### Prepare Membrane Plate

Inspect membranes for tears.

Using a pipette (single or multichannel), gently dispense 5 uL of **1% lecithin / dodecane solution** onto the donor plate membrane:

- Turn plate "upside-down" for ease of tip access.
- Gently apply single 5 uL drops of solution onto the membrane.
- Hang drop from tip right above membrane, then expel air to release drop.

!!! warning
    Do not touch the membrane with the tip!

- Multichannel pipettes can be used, but time efficiency is not urgent here.
- Ignore any observational disparities between membranes; as long as it's not a tear, the results work out consistently.
- Let the plate sit for at least 10 minutes (while preparing other samples) for the lipids to adsorb fully.

### Load Sample Plates

Using a multichannel pipette and solvent reservoir, dispense 300 uL of **1× PBS 5% DMSO buffer** into the acceptor plate wells:

- Use good pipette technique; volume disparities will influence results.
- Cover the plate with a loose cover to minimize evaporation.

Using a multichannel pipette, transfer 150 uL of the **10 uM analyte in 1× PBS 5% DMSO** into the donor plate wells:

- Gently dispense solutions into the donor plate, running the solution down the side of the well to minimize membrane disturbance.
- Use good pipette technique; volume disparities will influence results.

!!! warning "Important"
    Save (and seal) the source analyte stock for recovery analysis!

**Optional — Reverse technique:**

The analyte can be applied to the larger Teflon-block plate instead (requiring a larger volume of analyte!) in order to double the signal from the membrane plate. This is useful for especially-dilute analytes or slowly-permeating analytes. Adjust volumes appropriately in the calculations.

### Run Assay

Gently lower the donor plate wells into the acceptor plate wells.

- Confirm the absence of any bubbles; these will impair PAMPA performance.
- Gently lift and re-lower the donor plate if bubbles are observed.
- Place a plastic cover over the whole assembly (not airtight, just protective).
- Record current time / start a timer.

Gently transfer the assembly to a moist, separate chamber (not necessarily airtight).

- Wet some paper towels to lie over and under the assembly.
- Temperature control has been shown to be important for results, but we do not bother.

Allow assembly to sit for 10–20 hr.

- 14–16 hr is standard; adjust for faster- or slower-permeating analytes.
- The PAMPA Pe calculations account for assay duration.

Gently separate the plates.

- Slowly, to minimize any contamination in the acceptor plate (very full wells).
- Record total time of immersion.
- Immediately begin sample transfer.

### Prepare Analytical Samples

Repeat for the acceptor plate, donor plate, and source stock 10 uM deep-well plate ("recovery plate"):

Transfer 100 uL from each well to a labeled 96-well plate for HPLC-MS injection.

- Use good pipette technique.
- Mix well with pipette sparging!
- Switch tips between transfers.
- Seal the plate immediately upon finishing the transfer (plate sealer or sticky aluminum foil).

### Analyze / Calculate

#### Analyze

Analyze all samples within 24–48 hr after running the assay.

!!! note
    There is anecdotal evidence that compounds decompose or crash out, or that solvent levels change over time.

Create an appropriate HPLC-MS method; suggestions:

- 3–10 min total time for efficiency and generality.
- 1–1.5 min high-polarity wash (to waste; not to MS) to remove PBS buffer.
- Ramp up to (and hold at) 100% acetonitrile, ensuring good elution of analyte (and injection standard).
- Consider using single ion monitoring to increase sensitivity and ease analysis.

Consider frequent rinse methods (methanol or DMSO):

- Minimize analyte carry-over.
- Reduce analyte precipitation in the injection loop (a frequent problem with the polar PBS wash).
- Ensure that wash solvent is appropriate to solubilize analyte and PBS buffer.

Avoid sequential injection of compounds with the same mass in sequence to avoid carry-over interference.

Quantify TIC intensity; not UV absorbance.

#### Calculate

**Parameters:**

| Symbol | Description | Value |
|---|---|---|
| Msa | Active surface area of membrane (mm²) | 240 |
| Va | Volume of acceptor well (uL) | 300 |
| Vd | Volume of donor well (uL) | 150 |
| Ts | Assay run time (s) | — |
| Id | Donor intensity | — |
| Ia | Acceptor intensity | — |
| Ir | Recovery intensity | — |

**Calculations:**

**(1) Analyte Equilibrium:**

```
AnalyteEquil = ((Ia * Va) + (Id * Vd)) / (Va + Vd)
```

**(2) % Transmittance** (discard data if >95%):

```
T = Ia / AnalyteEquil
```

**(3) % Recovery** (low values represent material loss — aggregation or adherence):

```
R = ((Ia * Va) + (Id * Vd)) / (Ir * Vd)
```

**(4) Constant:**

```
C = (Vd * Va) / ((Vd + Va) * Msa * Ts)
```

**(5) Pe (×10⁻⁶)**, often displayed in log scale:

```
Pe = (-C * ln(1 - T)) * 10^-6
```
