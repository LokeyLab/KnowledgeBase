# Biotage Protocol

## Changing Solvents

1. Go to the **Set up** tab on the left-hand side of the screen.
2. You will see two options: **Solvents** and **Prime**.
3. First go to the **Solvents** tab and switch the solvents to the ones you need.
4. Remove the solvent lines from the currently used solvents and place them in the **Acetone** bottle.
5. Go to the **Prime** tab. Set the path to **without cartridge** and both Solvent 1 and 2 at **50%**. 100 mL is recommended for priming the lines. Once these have been adjusted, hit **Prime**.
6. Once the acetone wash is complete, put the appropriate solvent lines in the designated solvents. Double-check which solvents you designated as Solvent 1 and 2.
7. Repeat the **Prime**, this time with your desired solvents.

## Silica Gel Column — Dry Loading

1. Choose the size of your column based on the amount you are loading:

    | Column Size | Loading Amount     |
    |-------------|--------------------|
    | 10 g        | 50 -- 100 mg       |
    | 25 g        | 100 -- 250 mg      |
    | 50 g        | 250 -- 500 mg      |
    | 100 g       | 500 mg -- 1 g      |

2. Find the appropriate parts (the column, two filters, the lid, and the spreader piece that goes between the lid and filter). Give everything a good rinse with acetone.

3. Add silica gel to the column (located next to the waste graveyard).

    !!! warning "Filter first"
        Put a filter on the bottom of the column **before** adding silica, otherwise it will fall through the bottom.

    When adding the silica, go slowly and frequently tap the side of the tube to help the silica pack properly and remove air pockets.

    !!! tip
        Do not add too much silica — if the lid cannot close properly, solvent will leak during purification.

4. Change the solvent system to the appropriate solvents for your purification.

5. Once your column is ready, see [Starting a New Method](#starting-a-new-method) to begin your run.

## Reverse Phase — C18 Columns

!!! warning "Expensive and reusable"
    C18 columns are **reusable** and **expensive**. They are stored next to the Biotage. Always keep them **capped on both ends** when not connected to the instrument.

These columns are used to purify peptides, monomers, and other compounds that require reverse-phase purification (i.e., **Water/Acetonitrile**).

1. Choose the size of your column based on the amount to purify:

    | Column Size | Loading Amount     |
    |-------------|--------------------|
    | 12 g        | 50 -- 100 mg       |
    | 30 g        | 100 -- 400 mg      |
    | 100 g       | 400 mg or more     |

2. Change the solvents to **Water** and **Acetonitrile**, both with **0.1% TFA** (trifluoroacetic acid).

    !!! note "100 g column exception"
        For the 100 g column, use **Methanol** with 0.1% TFA instead of Acetonitrile.

3. Once ready, see [Starting a New Method](#starting-a-new-method) to set up your run.

## Starting a New Method

1. Make sure the Biotage is set to the appropriate solvents. Go to the **Method** tab on the right-hand side of the menu and hit **New** to start a new method. You will be prompted to choose the kind of column you are using (remember: **C18 ultra** for reverse phase).

2. Set the gradient conditions, the UV settings, the type of test tubes (**150 mm**), and the name of the run.

    !!! tip
        It is recommended to run three column volumes of the starting equilibrium.

3. Once you have adjusted the UV, gradient, and hooked up your column, hit **Run**.

4. Load your sample:

    === "Reverse Phase"

        Hit **Load Sample**. Once loading is complete, remove the top solvent line.

        !!! danger "Backpressure warning"
            If you forget to press **Load Sample**, backpressure will build and your product will spew out the top of the column.

    === "Normal Phase (Silica)"

        It is recommended to inject directly onto the silica gel:

        1. Place a piece of glassware below the column to collect excess solvent.
        2. Unscrew the bottom solvent line to let solvent drip out faster.
        3. Once the solvent has drained a little, remove the lid and solvent spreader.
        4. When the solvent level reaches the filter, use a glass pipet to add your product to the top of the filter.
        5. Let the solvent level drop to just above the filter, then reattach the bottom solvent line.
        6. Reassemble the top of the column and attach the top solvent line.

        !!! warning
            Do not let your column run dry or your separation will be poor.

    !!! tip
        When injecting, make sure your compound is in a **minimal amount of solvent**. Excess solvent will give poor separation.

5. Once your column is hooked back up to the Biotage, hit **Gradient**.

6. While the column is running, check for leaks around the column — this could indicate a part is not secured or a solvent line is loose.
