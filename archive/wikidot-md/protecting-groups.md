<!-- Original: http://lokeylab.wikidot.com/wiki:protecting-groups -->
# Protecting Groups

- Amine
  - Carbamate
    - [Boc](boc.md)
    - [Fmoc](fmoc.md)
    - Cbz (Z)
    - pNZ
    - 2-Cl-Z
    - Alloc
    - Poc (Propargyloxycarbonyl)
    - Teoc (2-(Trimethylsilyl)ethoxycarbonyl)
    - Troc
    - Azoc
    - Photolysable carbamates: oNZ, NVOC, NPPOC
  - Amide
    - [TFA](tfa.md) (Trifluoroacetyl)
  - Sulfonamide
    - [oNBS](onbs.md)
  - Miscellaneous
    - Trityl (Trt)
    - ivDde
    - TCP
- Carboxylic Acid
  - Me (Methyl)
  - tBu (tert-Butyl)
  - [Allyl](allyl.md)
  - Propargyl
  - Bn (Benzyl)
  - PMB
  - DMB
  - pNB
  - Trt
  - 2CT
  - Fm
  - TCE
  - TMSE
  - Dmnb

# Amine Protecting Groups

## Carbamates
The carbamates are by far the most illustrious class of amine protecting group. They are almost always installed in a single step under [Schotten-Baumann conditions](schotten-baumann-reaction.md) using the chloroformate (e.g. benzyl chloroformate (Z)), carbonate (e.g. Boc2O (Boc)), or OSu (mixed) carbonate (e.g. FmocOSu)). The simplest carbamates (e.g. methoxycarbonyl (MOC)) are difficult to remove, but more complex carbamates provide unlimited options.

### Cbz (Z, Benzyloxycarbonyl)
Z is a popular protecting group for solution-phase amine protection. Catalytic hydrogenolysis of Z-protected amines gives the free amine along with toluene and carbon dioxide. Heterogeneous catalyst may be removed by filtration and toluene by evaporation. Z is difficult to remove on the solid phase, and is typically only used when global deprotection with strong acid is used at the end of a Boc/Bn sequence.

**Stability:**
- Acid: Z is stable to room-temperature TFA (Boc and tBu removal). Does not perform well under repetitive TFA treatment required for Boc SPPS. Acidic removal of Z requires strong acid.
- Base: stable to the mildly basic conditions of Fmoc removal
- Oxidizers: stable to oxidizing agents
- Reducing agents: Z is removed by catalytic hydrogenolysis. Z is stable to NaBH4.
- Other: Alloc and allyl esters may be removed without affecting Z-protected amines.

**Removal:**
- Option 1: Z may be removed by catalytic hydrogenolysis. Transfer hydrogenation conditions may also be effective.
- Option 2: Z may be removed by strong acids (HBr/acetic acid, liquid HF, TFMSA, BBr3, refluxing TFA).

### pNZ (para-Nitrobenzyloxycarbonyl)
The pNZ group is removed by reduction with SnCl2 in dilute HCl/dioxane or by Na2S2O4. pNZ is very resistant to strong acids. It is orthogonal to Fmoc and Alloc as well. Use of pNZ amino acids can prevent DKP formation and aspartimide formation when deprotected on resin with SnCl2/HCl/dioxane.

### 2-Cl-Z
2-Cl-Z deserves mention because it is frequently used for amine side chain protection in Boc/Bn peptide synthesis (and are therefore commercially available). It is more acid-stable than Z and withstands repeated treatment with TFA. It is removed with liquid HF or triflic acid, or by hydrogenolysis.

### Alloc (allyloxycarbonyl)
Alloc is useful because its removal is orthogonal to most other protecting groups. Alloc is stable to the removal of Boc, Fmoc, and Trt. Alloc is removed by palladium-mediated transfer of the allyl group to a nucleophilic scavenger. Conditions are pretty much the same as those for the allyl ester. Alloc-Cl is cheap; Alloc-OSu is also available.

### Poc (Propargyloxycarbonyl)
The Poc protecting group is orthogonal to almost all other protecting groups. The Poc group is stable to acids (Boc removal) and bases. It is removed by sonication with tetrathiomolybdate for roughly one hour in acetonitrile. The Poc group has been reportedly used to protect amino acid chlorides for coupling without racemization.

### Teoc (2-(Trimethylsilyl)ethoxycarbonyl)
Teoc is a silicon-based protecting group for amines. It is removed by fluoride ion and by moderately strong acid (e.g. TFA). Use of fluorides will leave Boc intact, while use of acid will leave Fmoc intact. The Teoc group will not survive Boc removal.

Unfortunately, reagents for the introduction of Teoc (e.g. Teoc-Cl, Teoc-Np, Teoc-OSu) are quite expensive. Teoc should be utilized on the small scale.

### Troc (2,2,2-Trichloroethoxycarbonyl)
Troc is an old-school protecting group (1967) used to protect amines and alcohols. It is orthogonal to removal of other prominent amine protecting group - Boc, Fmoc, Alloc, Trt, and TFA. It is removed reductively by zinc dust in various solvents. The major advantage of this method for solution-phase synthesis is that the reagent is removed by simple filtration. However, use of powdered zinc is a disadvantage for solid-phase synthesis. Electroysis also removes Troc protecting groups. These conditions will not affect Boc, Fmoc, or Alloc. When amine protection is required for solution-phase chemistry, Troc should be considered. However, the Troc group undergoes side reaction when subjected to hydrogenation.

### Azoc (Azidomethoxycarbonyl)
Introduced to peptide synthesis by the Winssinger group in 2007, Azoc is a relatively new protecting group. It is removed by reduction with phosphines. It is therefore most promising for solid-phase synthesis, as phosphorus byproducts may otherwise be difficult to remove. Tributylphosphine removed azoc within several minutes, while solution-phase removal with resin-bound triphenylphosphine required half an hour. Fmoc was unaffected by Azoc removal, while Azoc was unaffected by Fmoc removal.

Unfortunately, azidomethyl chloroformate is explosive. The Azoc group is introduced by first acylating with chloromethyl chloroformate then reacting the crude product with inorganic azide. A methyl ester may be cleaved with LiOH in the presence of the Azoc group although partial hydrolysis of Azoc was seen after prolonged exposure. Azoc is removed by high concentrations of TFA. Given the rapid deprotection of Azoc using phosphines and its orthogonality with Fmoc, Azoc is a powerful potential addition to our toolbox.

### Nsc (2-(4-nitrophenylsulfonyl)ethoxycarbonyl)
Proposed as a superior alternative to Fmoc in peptide synthesis. Slightly slower to deprotect in 20% piperidine/DMF, but adding 1% DBU makes up for it. Nsc is quickly removed with tris(2-aminoethyl)amine in DCM or MeOH. Unlike DBF, the vinyl sulfone resulting from Nsc deprotection does not polymerize and adduct formation with amines is irreversible (adduct formation of DBF with amines is reversible). Moreover, DMF solutions of Nsc amino acids decompose much more slowly than Fmoc amino acid stock solutions. Unfortunately, the Nsc protecting group never caught on commercially. Nsc-Cl or Nsc-OSu must be synthesized in house.

### Photolysable protecting groups
These protecting groups are particularly applicable to the preparation of lithographic arrays (deprotection is controlled spatially using lasers). The first amine photolysable protecting groups were oNZ and NVOC. Both require somewhat higher energy light and take several hours. More recent ones include NPPOC and MNPPOC. These may be removed in minutes at wavelengths >350nm.

## Carboxylic amides
In the dawn of organic synthesis, amines were protected as amides. Simple amides, such as N-acetyl and N-benzoyl, are cleaved using strong aqueous acids at high temperatures, typically. These conditions are unsuitable for peptide synthesis due to epimerization. Currently, the only significant carboxamide protecting group relevant to amino acids is the trifluoroacetyl group (TFA). The protecting groups are typically installed by acylating the amine with the anhydride or the acid chloride in the presence of base.

### Trifluoroacetyl ([TFA](tfa.md))
Unlike most amides, the trifluoroacetyl group may be removed by brief exposure to dilute aqueous base or by sodium borohydride.

## Sulfonamides
The sulfonamides are a prominent class of amide protecting group. Most sulfonamides are very stable under acidic and basic conditions. The tosyl (Ts, p-toluenesulfonyl) group is a classic, but is difficult to remove, requiring strong acid or harsh reducing agents. However, with electron-poor aromatic systems (e.g. nitro groups or benzothiazole system), the sulfonamide may be cleaved with gentler reducing agents or nucleophiles. Sulfonamide-protected amino acids do not racemize via oxazolone formation, which means oNBS amino acids can be activated as the acid chloride without racemization. The oNBS, nosyl, and dNBS protected amines may be alkylated using either alkyl halide/base or Mitsunobu conditions, including on solid phase. Sulfonamides are prepared in a single step from the amine by reaction with the sulfonyl chloride in the presence of base. Generally, they are removed more easily from secondary amines than from primary amines.

### oNBS (o-nitrobenzenesulfonyl) and Nosyl (Ns, p-nitrobenzenesulfonyl)
These protecting groups are removed by thiolates, generated from the reaction of thiol with weak base, typically in DMF. This makes the oNBS group useful in SPPS on acid-sensitive resins.

### dNBS (2,4-dinitrobenzenesulfonyl)
The dNBS protecting group is very similar to oNBS but is removed under even milder conditions. Only a slight excess of mercaptoacetic acid is required along with triethylamine in DMF. The dNBS group can be removed in the presence of an oNBS group. The dNBS group can be removed using 20eq n-propylamine in DCM in ten minutes at room temperature.

### Bts (Benzothiazole-2-sulfonyl)
The Bts group is also removed reductively under various conditions. It has been used in some impressive solution-phase peptide syntheses. Bts-protected BCAAs are crystalline solids. Bts amino acids have been activated as their acid chlorides using thionyl chloride and coupled onto secondary amines without racemization in solution.

## Alkyl
For the most part, alkylamines are considered difficult to cleave. N-methyl may be removed with exotic reagents. The tert-butyl group is removed by acid, typically with difficulty. Deallylation is Palladium-mediated. PMB has been removed with DDQ. Fluorenyl appears to be an excellent protecting group (removed from D-phenylglycinamide with DDQ followed by 1N HCl, each for 5 minutes). Mono-alkylation of primary amines usually cannot be carried out directly. Reductive amination is an option. Sterically hindered amines, such as trityl, may be installed directly.

### Trt (Trityl)
Tritylamines are synthesized by reaction with trityl chloride in the presence of triethylamine. Dialkylation will not occur. The remaining N-H is sterically hindered. Tritylamines are cleaved by treatment with acid, usually in the presence of scavenger, usually a silane. Many acids have been used succesfully, and Lewis acids have also worked (e.g. Yb(OTf)3).

## Phthalimide
Phthalimide protecting groups are used for bis-protection of primary amines. The protected amine has no acidic N-H bonds.

### TCP (Tetrachlorophthalimide)
TCP has been proposed in SPPS because it is stable to Fmoc, Boc, and Alloc removal and is removed under mild conditions (ethylenediamine-DMF (1:200) at 40 C, 1 h, in repetitive deprotections). When protecting the alpha-amine, may also be removed by hydrazine in DMF.

## Other

### ivDde (1-(4,4-dimethyl-2,6-dioxocyclohex-1-ylidene)isovaleryl)
ivDde is a bizarre protecting group introduced in 1998. ivDde is used for side chain amine protection in the Fmoc/tBu strategy to make branched and cyclic peptides because it is stable to Fmoc deprotection conditions but is removed by 2% hydrazine in DMF. ivDde is stable to Boc deprotection.

# Carboxylic Acid Protecting Groups

## Alkyl esters
Alkyl esters are the most prominent type of carboxylate protecting group. Most of the carbamates used to protect amines have an analogous ester used for protecting the carboxylate. Esters are more easily cleaved with aqueous base than are carbamates. They are easily installed and allow a wide variety of deprotection conditions. Usually, formation entails DCC/DMAP ester coupling or alkylation of carboxylate using alkyl halide. The Mitsunobu reaction is another option.

### Me (Methyl)
Installation and removal of the methyl protecting group is usually straightforward. Deprotection requires aqueous base. Base-mediated epimerization at the alpha-carbon of amino acids is a concern but the methyl remains one of the most popular C-terminus protecting groups in solution because LiOH generally does not cause epimerization. The methyl ester can usually be cleaved in the presence of other esters. However, if the conformation of an amide is constrained such that there is loss of resonance, even amides may be unexpectedly cleaved by LiOH. Chemists have gone to extreme lengths to cleave methyl esters while keeping delicate molecules intact and labile chiral centers unepimerized.

### tBu (tert-Butyl)
The tBu group is a staple in SPPS (the Fmoc/tBu method). tBu esters are installed under a variety of conditions: isobutylene/H2SO4, tBuOH/DCC/DMAP, etc. Many classical esterification techniques may fail. Unlike most esters, tBu is not readily cleaved with base or nucleophile and is therefore fully orthogonal to Fmoc. tBu is removed by acids. Usually moderately strong acids are required, but formic acid at room temperature has been used. Including scavengers is generally a good idea to quench reactive tBu cation and isobutylene. The tBu group should not be affected by any conditions that do not include fairly competent Bronsted or Lewis acids. Any environment of sufficient acidity to remove a Boc group will also cleave a tBu ester. Often, amino acids with a tBu carboxylate protecting group are commercially available.

### Allyl
The allyl ester is frequently used by our lab as an Fmoc and acid orthogonal carboxylate protecting group.

### Propargyl
Propargyl deserves mention because its removal with benzyltriethylammonium tetrathiomolybdate in acetonitrile is very orthogonal to almost any other protecting group. Protection (pargyl bromide, K2CO3) and deprotection are compatible with Boc, Fmoc, Z, and allyl ester. Only a slight excess of the tetrathiomolybdate is required. This protecting group appears to be compatible with classical solution-phase peptide synthesis (DCC/HOBt/NMM/MeCN), although compatibility with Fmoc deprotection may not be as good.

### Bn (Benzyl)
Benzyl esters are prepared by methods typical of esters. Benzyl esters are useful because they may be cleaved by hydrogenolysis, including transfer hydrogenolysis. The combination of silane and Pd(OAc)2 converted Boc-L-allylglycine benzyl ester to Boc-L-allylglycine silyl ester (easily hydrolyzed) in 100% yield.

### PMB (para-Methoxybenzyl)

### DMB (2,4-Dimethoxybenzyl)

### pNB (para-Nitrobenzyl)

### Tr (Trityl)
Trityl esters are extremely labile to acids and should not be regarded as a general use protecting group. However, the conditions of Fmoc SPPS are consistently basic, and trityl protecting groups are useful, particularly trityl-type resins. Trityl esters are cleaved with weak or dilute acids. The trityl-type protecting groups afford excellent protection against nucleophilic attack, unlike most esters.

### 2CT (2-Chlorotrityl)
Mainly recognized as the basis for 2-chlorotrityl polystyrene resin used heavily in most peptide synthesis labs, 2CT is a highly acid-sensitive protecting group (although not as sensitive as trityl). 2CT esters are easily formed from 2-chlorotrityl chloride and carboxylate salts. 2CT resin is usually cleaved using 1 or 2% TFA in DCM or 20-30% HFIP in DCM.

### Fm (Fluorenyl)
The Fm protecting group is removed under conditions similar to those used to remove Fmoc (piperidine or diethylamine in DMF or DCM). It is essentially the carboxylic acid protecting counterpart to the Fmoc group. It is installed and removed from the C-terminus without epimerization.

### TCE (2,2,2-Trichloroethyl)
The TCE ester is formed under the usual conditions and cleaved rapidly using various metals (usually zinc dust) in various solvents. The zinc is then removed by filtration.

### TMSE (2-Trimethylsilylethyl)
TMSE is removed with fluoride sources or acids. Shockingly, the TMSE ester has been retained during Boc removal - Boc was removed in the presence of TMSE protection using 4M HCl (probably in dioxane) in 99% yield. However, if simultaneous Boc and TMSE removal is desired, 10% TFA/DCM may be used. It has been used in the synthesis of complex cyclic peptides. TMSE is compatible with catalytic hydrogenation conditions.
