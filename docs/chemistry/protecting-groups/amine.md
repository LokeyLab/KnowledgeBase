# Amine Protecting Groups

## Carbamates

The carbamates are by far the most illustrious class of amine protecting group. They are almost always installed in a single step under [Schotten-Baumann conditions](../solution-phase/schotten-baumann.md) using the chloroformate (e.g., benzyl chloroformate (Z)), carbonate (e.g., Boc2O (Boc)), or OSu (mixed) carbonate (e.g., Fmoc-OSu). The simplest carbamates (e.g., methoxycarbonyl (MOC)) are difficult to remove, but more complex carbamates provide unlimited options.

### Boc (tert-Butyloxycarbonyl)

Boc is one of the two most important amine protecting groups in peptide synthesis (along with Fmoc). It is the basis of the Boc/Bn SPPS strategy and is widely used in solution-phase synthesis.

#### Installation

Boc is installed using Boc2O (di-tert-butyl dicarbonate) under Schotten-Baumann conditions. Typical conditions: amino acid dissolved in aqueous dioxane or THF, NaOH or NaHCO3 as base, Boc2O added at room temperature.

!!! note "Melting Point"
    Boc2O has a low melting point (~22 C) and may be a liquid at room temperature. This is normal and does not affect reactivity.

#### Stability

Boc is orthogonal to most other protecting groups:

- **Acid:** Boc is removed by acids (TFA, HCl/dioxane). It is not stable to even moderate acid treatment.
- **Base:** Boc is completely stable to basic conditions, including Fmoc deprotection (piperidine/DMF).
- **Hydrogenolysis:** Boc is stable to catalytic hydrogenolysis conditions.
- **Nucleophiles:** Boc is stable to thiolates and other nucleophiles.

#### Removal

**Option 1: HCl/Dioxane**

- 4 M HCl in dioxane, room temperature, 30 min to 1 hour.
- Product is obtained as the hydrochloride salt.
- Simple and clean for solution-phase work.

**Option 2: TFA**

- Neat TFA or TFA/DCM mixtures (25-50% TFA), room temperature, 30 min.
- Include scavengers (triisopropylsilane, water, or thiol scavengers) to quench the tert-butyl cation and isobutylene generated during deprotection.
- Standard for solid-phase Boc removal.

### Fmoc (9-Fluorenylmethyloxycarbonyl)

Fmoc is the basis of the Fmoc/tBu SPPS strategy, which is the most widely used approach in modern peptide synthesis. Fmoc is removed by secondary amines through a beta-elimination mechanism.

#### Installation

**Fmoc-OSu** is the preferred reagent for Fmoc installation on amino acids. It reacts selectively with amines and avoids the dibenzofulvene (DBF) side products that can form with Fmoc-Cl under basic conditions.

**Fmoc-Cl** is cheaper but less selective. Under Schotten-Baumann conditions, the base can cause elimination of Fmoc-Cl to DBF, which can alkylate the product.

Both reagents are used under standard Schotten-Baumann conditions: amino acid in aqueous dioxane or THF, NaHCO3 or Na2CO3 as base.

#### Stability

- **Secondary amines:** Fmoc is removed by secondary amines (piperidine, diethylamine, morpholine, DBU). This is the basis of Fmoc deprotection.
- **Acid:** Fmoc is completely stable to acids, including TFA and HCl. This orthogonality to Boc is the foundation of the Fmoc/tBu strategy.
- **Hydrogenolysis:** Fmoc is stable to catalytic hydrogenolysis.
- **Nucleophiles:** Fmoc is generally stable to nucleophiles, although strong nucleophiles in polar solvents can cause slow removal.

#### Removal Mechanism

Fmoc is removed by beta-elimination. A base (typically piperidine) abstracts the fluorenyl proton, generating dibenzofulvene (DBF) and releasing the free amine as the carbamate anion, which decomposes to CO2 and the free amine. The piperidine also scavenges the DBF by conjugate addition, preventing it from reacting with the deprotected amine.

#### Solid-Phase Removal Cocktails

| Cocktail | Notes |
|---|---|
| **2% piperidine / 2% DBU in DMF** | Lab standard. The DBU accelerates deprotection while the piperidine scavenges DBF. |
| **20% piperidine in DMF** | Classic Fmoc deprotection cocktail. Works well but uses more piperidine. |
| **20% piperidine in DMF + 0.1 M HOBt** | HOBt suppresses aspartimide formation. Recommended when Asp(OtBu) is present in the sequence. |
| **50% morpholine in DMF** | Alternative to piperidine. Morpholine is less nucleophilic and may be preferred in some cases. |

!!! tip "Lab Standard"
    The Lokey Lab standard Fmoc deprotection cocktail is **2% piperidine / 2% DBU in DMF**. This cocktail provides rapid and complete Fmoc removal while minimizing piperidine consumption.

#### Solution-Phase Deprotection

For solution-phase Fmoc removal, **diethylamine in ACN** (typically 10-20%) is commonly used. Diethylamine is volatile and easily removed by evaporation. The DBF-diethylamine adduct is also volatile.

#### Bibliography

- Obkircher et al., "Fmoc Removal: Piperidine and DBU", *Org Process Res Dev*, **2008**, 12, 965-970.

### Cbz (Z, Benzyloxycarbonyl)

Z is a popular protecting group for solution-phase amine protection. Catalytic hydrogenolysis of Z-protected amines gives the free amine along with toluene and carbon dioxide. Heterogeneous catalyst may be removed by filtration and toluene by evaporation. Z is difficult to remove on the solid phase, and is typically only used when global deprotection with strong acid is used at the end of a Boc/Bn sequence.

**Stability:**

- **Acid:** Z is stable to room-temperature TFA (Boc and tBu removal). Does not perform well under repetitive TFA treatment required for Boc SPPS. Acidic removal of Z requires strong acid.
- **Base:** Stable to the mildly basic conditions of Fmoc removal.
- **Oxidizers:** Stable to oxidizing agents.
- **Reducing agents:** Z is removed by catalytic hydrogenolysis. Z is stable to NaBH4.
- **Other:** Alloc and allyl esters may be removed without affecting Z-protected amines.

**Removal:**

- **Option 1:** Z may be removed by catalytic hydrogenolysis. Transfer hydrogenation conditions may also be effective.
- **Option 2:** Z may be removed by strong acids (HBr/acetic acid, liquid HF, TFMSA, BBr3, refluxing TFA).

### pNZ (para-Nitrobenzyloxycarbonyl)

The pNZ group is removed by reduction with SnCl2 in dilute HCl/dioxane or by Na2S2O4. pNZ is very resistant to strong acids. It is orthogonal to Fmoc and Alloc as well. Use of pNZ amino acids can prevent DKP formation and aspartimide formation when deprotected on resin with SnCl2/HCl/dioxane.

### 2-Cl-Z

2-Cl-Z is frequently used for amine side chain protection in Boc/Bn peptide synthesis (and is therefore commercially available). It is more acid-stable than Z and withstands repeated treatment with TFA. It is removed with liquid HF or triflic acid, or by hydrogenolysis.

### Alloc (Allyloxycarbonyl)

Alloc is useful because its removal is orthogonal to most other protecting groups. Alloc is stable to the removal of Boc, Fmoc, and Trt. Alloc is removed by palladium-mediated transfer of the allyl group to a nucleophilic scavenger. Conditions are similar to those for the allyl ester. Alloc-Cl is cheap; Alloc-OSu is also available.

### Poc (Propargyloxycarbonyl)

The Poc protecting group is orthogonal to almost all other protecting groups. The Poc group is stable to acids (Boc removal) and bases. It is removed by sonication with tetrathiomolybdate for roughly one hour in acetonitrile. The Poc group has been reportedly used to protect amino acid chlorides for coupling without racemization.

### Teoc (2-(Trimethylsilyl)ethoxycarbonyl)

Teoc is a silicon-based protecting group for amines. It is removed by fluoride ion and by moderately strong acid (e.g., TFA). Use of fluorides will leave Boc intact, while use of acid will leave Fmoc intact. The Teoc group will not survive Boc removal.

!!! note
    Reagents for the introduction of Teoc (e.g., Teoc-Cl, Teoc-Np, Teoc-OSu) are quite expensive. Teoc should be utilized on the small scale.

### Troc (2,2,2-Trichloroethoxycarbonyl)

Troc is an old-school protecting group (1967) used to protect amines and alcohols. It is orthogonal to removal of other prominent amine protecting groups -- Boc, Fmoc, Alloc, Trt, and TFA. It is removed reductively by zinc dust in various solvents. The major advantage for solution-phase synthesis is that the reagent is removed by simple filtration. However, use of powdered zinc is a disadvantage for solid-phase synthesis. Electrolysis also removes Troc protecting groups. These conditions will not affect Boc, Fmoc, or Alloc. When amine protection is required for solution-phase chemistry, Troc should be considered. However, the Troc group undergoes side reaction when subjected to hydrogenation.

### Azoc (Azidomethoxycarbonyl)

Introduced to peptide synthesis by the Winssinger group in 2007, Azoc is a relatively new protecting group. It is removed by reduction with phosphines. It is therefore most promising for solid-phase synthesis, as phosphorus byproducts may otherwise be difficult to remove. Tributylphosphine removed Azoc within several minutes, while solution-phase removal with resin-bound triphenylphosphine required half an hour. Fmoc was unaffected by Azoc removal, while Azoc was unaffected by Fmoc removal.

!!! warning
    Azidomethyl chloroformate is explosive. The Azoc group is introduced by first acylating with chloromethyl chloroformate then reacting the crude product with inorganic azide.

A methyl ester may be cleaved with LiOH in the presence of the Azoc group although partial hydrolysis of Azoc was seen after prolonged exposure. Azoc is removed by high concentrations of TFA. Given the rapid deprotection of Azoc using phosphines and its orthogonality with Fmoc, Azoc is a powerful potential addition to our toolbox.

### Nsc (2-(4-nitrophenylsulfonyl)ethoxycarbonyl)

Proposed as a superior alternative to Fmoc in peptide synthesis. Slightly slower to deprotect in 20% piperidine/DMF, but adding 1% DBU makes up for it. Nsc is quickly removed with tris(2-aminoethyl)amine in DCM or MeOH. Unlike DBF, the vinyl sulfone resulting from Nsc deprotection does not polymerize and adduct formation with amines is irreversible (adduct formation of DBF with amines is reversible). Moreover, DMF solutions of Nsc amino acids decompose much more slowly than Fmoc amino acid stock solutions. Unfortunately, the Nsc protecting group never caught on commercially. Nsc-Cl or Nsc-OSu must be synthesized in house.

### Photolysable Protecting Groups

These protecting groups are particularly applicable to the preparation of lithographic arrays (deprotection is controlled spatially using lasers). The first amine photolysable protecting groups were oNZ and NVOC. Both require somewhat higher energy light and take several hours. More recent ones include NPPOC and MNPPOC. These may be removed in minutes at wavelengths >350 nm.

## Carboxylic Amides

In the dawn of organic synthesis, amines were protected as amides. Simple amides, such as N-acetyl and N-benzoyl, are cleaved using strong aqueous acids at high temperatures, typically. These conditions are unsuitable for peptide synthesis due to epimerization. Currently, the only significant carboxamide protecting group relevant to amino acids is the trifluoroacetyl group (TFA). The protecting groups are typically installed by acylating the amine with the anhydride or the acid chloride in the presence of base.

### Trifluoroacetyl (TFA)

Unlike most amides, the trifluoroacetyl group may be removed by brief exposure to dilute aqueous base or by sodium borohydride.

## Sulfonamides

The sulfonamides are a prominent class of amide protecting group. Most sulfonamides are very stable under acidic and basic conditions. The tosyl (Ts, p-toluenesulfonyl) group is a classic, but is difficult to remove, requiring strong acid or harsh reducing agents. However, with electron-poor aromatic systems (e.g., nitro groups or benzothiazole system), the sulfonamide may be cleaved with gentler reducing agents or nucleophiles. Sulfonamide-protected amino acids do not racemize via oxazolone formation, which means oNBS amino acids can be activated as the acid chloride without racemization. The oNBS, nosyl, and dNBS protected amines may be alkylated using either alkyl halide/base or Mitsunobu conditions, including on solid phase. Sulfonamides are prepared in a single step from the amine by reaction with the sulfonyl chloride in the presence of base. Generally, they are removed more easily from secondary amines than from primary amines.

### oNBS (o-Nitrobenzenesulfonyl) and Nosyl (Ns, p-Nitrobenzenesulfonyl)

These protecting groups are removed by thiolates, generated from the reaction of thiol with weak base, typically in DMF. This makes the oNBS group useful in SPPS on acid-sensitive resins.

### dNBS (2,4-Dinitrobenzenesulfonyl)

The dNBS protecting group is very similar to oNBS but is removed under even milder conditions. Only a slight excess of mercaptoacetic acid is required along with triethylamine in DMF. The dNBS group can be removed in the presence of an oNBS group. The dNBS group can be removed using 20 eq n-propylamine in DCM in ten minutes at room temperature.

### Bts (Benzothiazole-2-sulfonyl)

The Bts group is also removed reductively under various conditions. It has been used in some impressive solution-phase peptide syntheses. Bts-protected BCAAs are crystalline solids. Bts amino acids have been activated as their acid chlorides using thionyl chloride and coupled onto secondary amines without racemization in solution.

## Alkyl

For the most part, alkylamines are considered difficult to cleave. N-methyl may be removed with exotic reagents. The tert-butyl group is removed by acid, typically with difficulty. Deallylation is palladium-mediated. PMB has been removed with DDQ. Fluorenyl appears to be an excellent protecting group (removed from D-phenylglycinamide with DDQ followed by 1 N HCl, each for 5 minutes). Mono-alkylation of primary amines usually cannot be carried out directly. Reductive amination is an option. Sterically hindered amines, such as trityl, may be installed directly.

### Trt (Trityl)

Tritylamines are synthesized by reaction with trityl chloride in the presence of triethylamine. Dialkylation will not occur. The remaining N-H is sterically hindered. Tritylamines are cleaved by treatment with acid, usually in the presence of scavenger, usually a silane. Many acids have been used successfully, and Lewis acids have also worked (e.g., Yb(OTf)3).

## Phthalimide

Phthalimide protecting groups are used for bis-protection of primary amines. The protected amine has no acidic N-H bonds.

### TCP (Tetrachlorophthalimide)

TCP has been proposed in SPPS because it is stable to Fmoc, Boc, and Alloc removal and is removed under mild conditions (ethylenediamine-DMF (1:200) at 40 C, 1 h, in repetitive deprotections). When protecting the alpha-amine, may also be removed by hydrazine in DMF.

## Other

### ivDde (1-(4,4-Dimethyl-2,6-dioxocyclohex-1-ylidene)isovaleryl)

ivDde is a protecting group introduced in 1998. It is used for side chain amine protection in the Fmoc/tBu strategy to make branched and cyclic peptides because it is stable to Fmoc deprotection conditions but is removed by 2% hydrazine in DMF. ivDde is stable to Boc deprotection.
