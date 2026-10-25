## Genetic and proteomic characterization of the glucokinase E339K variant in maturity-onset diabetes of the young type 2 (MODY2).

[Maeve López Pardo, Deolinda Pérez, Biel Porté, Unai Ros, Ariadna Sospedra]  
[Department of bioinformatics, UPC Campus Nord, Barcelona, Spain]

## Abstract
Human glucokinase (GK) is an enzyme of 465 amino acids that functions as a beta-cell glucose sensor, regulating insulin secretion and blood glucose homeostasis. An heterozigotic mutation of the gene GCK, the one encoding human glucokinase, produces a structural change in the final protein, causing Maturity Onset Diabets of the Young type 2 (MODY2). In this paper, we identify the mutation as a substitution of a single nucleotid at the chomosome 7 region 13, c.1015G>A; which creates a missense mutation E339K (PDB entry 3QIC). Glu339 and Lys339 chemically differ because they are negativelly charged and positevilly charged respectivelly.  helix and produces two consecutive confrmational changes, one 90 degrees rotaion of histeine at position  at position 339 instead of the wild type glutamic acid. Two significant conformational change happens very close to the active site because glutamic 

## Keywords
GLucokinase, E339K

## BACKGROUNDS
Maturity-onset diabetes of the young type 2 (MODY2) is a form of monogenic diabetes characterized by autosomal dominant inheritance, located in chromosome 7p13,  and non-autoimmune β-cell dysfunction. It is typically diagnosed before the age of 25 years following the detection of hyperglycaemia, and is associated with primary defects in insulin secretion. Its clinical course and management, however, depend on the gene involved. It does not require treatment expect in special circumstances. Is a stable hyperglycaemia that is rarely associated with vascular complications and generally requires no pharmacological treatment beyond lifestyle and dietary measures. 

The exact prevalence of MODY remains uncertain but it is estimated to account for 1.1 - 6.5% of paedriatic diabetes cases, with marked geographical variation largely attributable to differences in the criteria used to identify cases. GCK-MODY, HNF1A-MODY, and HNF4A-MODY account for more than 90% of MODY cases with a genetic confirmation in several studies in the UK, Europe, and the USA. 

GCK, in its normal, unaltered form encodes glucokinase, also known as hexokinase IV containing 465 amino acids. Mainly expressed in the liver and pancreatic beta cells, this protein catalyses the phosphorylation of hexose, primarily D-glucose, resulting in glucose 6-phosphate. The product, in  turn, is used for the synthesis of glycogen, utilised to store energy. Apart from catalysing the phosphorylation, it serves an important role regarding insulin, depending on its presence, the pancreas or the liver. In the former, insulin secretion is modulated by GCK, while in the latter it acts as an insulin-sensitive determinant of hepatic glucose usage, this referring to how the liver consumes glucose and uses it in relation to the level of insulin, thus insulin-sensitive. GCK, additionally, has a low affinity for glucose, operating efficiently only once there is an abundance of glucose.

GCK-MODY results from heterozygous inactivating variants in GCK. These variants raise the glucose threshold for insulin secretion by pancreatic β-cells and alter hepatic glucose handling, so that glucose is maintained at a slightly elevated but tightly regulated level. Because this hyperglycaemia is mild and rarely leads to clinically relevant micro- or macrovascular complications, GCK-MODY generally requires no treatment.


### Physiology of wild-type glucokinase
Glucokinase (GK, also called hexokinase IV) is an enzyme encoded by the *GCK* gene on chromosome 7p13. It catalyses the first step of glucose metabolism: it adds a phosphate group to glucose, using ATP, to produce glucose-6-phosphate (G6P). It is found mainly in pancreatic beta cells and in liver cells (hepatocytes). The gene has two tissue-specific promoters, so the pancreas and the liver produce slightly different versions (isoforms) of the enzyme (Postic 2001).

Other hexokinases (types I–III) bind glucose very strongly, so they already work at full speed even when there is very little glucose. Glucokinase is different in three ways: it has a low affinity for glucose (it reaches half of its maximum speed at about 8-10 mM), its activity follows an S-shaped (sigmoidal) curve with a Hill coefficient of about 1.7, and it is not significantly inhibited by its product, G6P, at normal concentrations (Matschinsky 1993, Liu 2011). Because of this, the speed of glucokinase changes with blood glucose levels within the normal range. This is why glucokinase works as the body's glucose sensor.

In pancreatic beta cells, glucokinase controls the slowest (rate-limiting) step of glucose metabolism. After a meal, blood glucose rises and glucose enters the beta cell, where glucokinase phosphorylates it. As glucose is broken down through glycolysis and in the mitochondria, the cell produces more ATP. The higher ATP/ADP ratio closes ATP-sensitive potassium (K-ATP) channels in the cell membrane. This changes the electrical charge of the membrane (depolarization), which opens calcium channels. Calcium then enters the cell and causes the release of insulin from storage granules (Thompson 2021). Since glucokinase controls the speed of this whole chain, it sets the blood glucose threshold for insulin release at about 5 mM (Matschinsky 1993).

In the liver, glucokinase helps to take up glucose and store it after meals. During fasting, when glucose is low, another protein called glucokinase regulatory protein (GKRP) binds glucokinase and keeps it inactive inside the nucleus. This stops the liver from using glucose when the body needs it. When blood glucose rises after a meal, glucokinase is released and moves to the cytoplasm, where the G6P it produces is used to make glycogen, the liver's glucose store (Postic 2001).

Glucokinase is a monomer (a single protein chain) with two parts, a large domain and a small domain, separated by a cleft where glucose binds. Without glucose, the enzyme stays mostly in an inactive "super-open" shape. When glucose binds, the enzyme slowly changes to an active "closed" shape. This slow change of shape explains why glucokinase shows an S-shaped curve even though it has only one glucose-binding site (Kamata 2004).


## METHODS
The gene FASTA files were provided to us by our professors Ricard Gonzalez, David Blázquez and Nuria Centeno, both the wild-type and mutant human glucokinase. Furthermore, two animal homolog of glucokinase, in Xenopus laevis and Ovis aeris, were obtained by BLAST. 
Sequence alignment of those FASTA files was done with BLASTn, obtaining the exact locus of the mutation, c1015G>A.

Cross-species and varial structural comparison: 

Sequence and structural comparisons between wild-type human glucokinase, the E339K variant (PDB3QIC) and its Xenopus laevis orthologue were provided by our professors as a conservation report.

The human (UniProt P35557) and sheep (NCBI NP_001274400.1) glucokinase sequences were aligned with EMBOSS Needle (EBLOSUM62 matrix, gap open 10, gap extend 0.5) (Madeira 2024). The comparison with *Xenopus laevis* was done with the conservation report provided in class, which includes a sequence alignment and a structural superposition.  

Orthologous sequences were identified with BLAST and corresponding three-dimensional structures were obtained from the Protein Data Bank and structural data bases. Structures were superimposed and their secondary structure assigned in ChimeraX, and the global Cα root-mean-square deviatiuon (RMSD) and per-residue backbone displacement were computed. 

The 3D stucture of the protein was identified using the RCSB Protein Data Bank (PDB) Sequence Search tool by querying the mutated human glucokinase sequence at 100% sequence identity. Specific structural mechanisms, including the His416 physical  collision and Ser411–Thr82 loop interaction, along with kinetic parameters were extracted directly from the primary study's text, figures, and figure legends without external molecular modeling software.



## RESULTS

## Comparison with other species

Orthologs are the same gene in different species, inherited from a common ancestor. When a position in a protein has not changed during millions of years of evolution, it is probably important for the function of the protein. To study this in glucokinase, we compared the human protein with two other species: *Xenopus laevis* (African clawed frog), an amphibian that is distantly related to humans, and *Ovis aries* (sheep), a mammal that is closely related to humans. We expected the sheep protein to be much more similar to the human protein than the frog protein.

The human and *Xenopus* proteins share 80.6% of their aligned positions, and 88.4% of the positions have amino acids from the same physicochemical group. Most of the differences are found at the beginning of the protein (the frog protein lacks the first seven residues) and in loops, which are flexible regions. Other regions are completely identical, for example residues 161–200. The secondary structure (alpha helices and beta strands) is almost the same in both species. The global RMSD between the two structures is 8.18 Å, which seems high. However, the superposition shows that one domain fits almost perfectly while the other is displaced as a block. This suggests that the two structures are in different conformations (open and closed), and not that the fold is different.

The sheep protein is much more similar to the human protein: a global alignment with EMBOSS Needle gave 96.6% identity and 98.3% similarity, with no gaps (both proteins have 465 residues). Only 16 positions are different, and most of them are changes between similar amino acids. None of them is between positions 309 and 341.

In the three species, position 339 is a glutamate (E). This means that this residue has been conserved in mammals and amphibians, so the E339K mutation changes a position that evolution has not allowed to change. In addition, the local backbone displacement at position 339 between human and *Xenopus* (3.13 Å) is larger than between the wild-type and the mutant (2.49 Å), even though the frog enzyme works normally. This suggests that the problem of E339K is not only the movement of the backbone, but the change of charge from negative to positive, which breaks the interactions of glutamate 339 with His416 and Arg422 (Liu 2011).

Glucokinase is highly conserved in vertebrates, which shows that its role as a glucose sensor is essential. Because E339 is conserved even in distantly related species, a change at this position is likely to affect the function of the enzyme, which agrees with the reduced activity of the E339K mutant and the hyperglycaemia seen in patients.

**Table X.** Comparison of human glucokinase with its orthologs.

| Species | Identity with human | Similarity with human | Residue 339 | Source |
|---|---|---|---|---|
| *Homo sapiens* (P35557) | — | — | E | — |
| *Ovis aries* (NP_001274400.1) | 96.6% | 98.3% | E | EMBOSS Needle |
| *Xenopus laevis* | 80.6% | 88.4%* | E | Class conservation report |

\*Percentage of positions with amino acids from the same physicochemical group. 

## Genomics impact of mutation

### Nucleotide change

Comparison of the wild-type and mutant sequences provided revealed a single nucleotide substitution at position 1015 of the coding sequence (c.1015G>A; reference transcript [NM_000162.X]). This position corresponds to the first nucleotide of codon 339, which changes from [GAG] to [AAG]. The substitution is a transition (a purine replaced by another purine) and does not alter the reading frame or introduce a premature stop codon. Instead, it changes the encoded amino acid, classifying it as a missense variant (p.Glu339Lys, E339K). Affected individuals are heterozygous, carrying one wild-type and one mutant allele, consistent with the autosomal dominant inheritance of MODY2.

### Amino acid substitution

The variant replaces glutamate with lysine at position 339 of the 465-residue protein (Table X). Both residues have a side chain of similar length, but with opposite chemical properties. Glutamate is an acidic residue whose carboxyl group is deprotonated at physiological pH, giving it a negative charge and the ability to act as a hydrogen-bond acceptor. Lysine is a basic residue whose terminal amino group is protonated at physiological pH, giving it a positive charge and acting as a hydrogen-bond donor. The substitution therefore reverses the local charge from −1 to +1, a net change of +2 at this position, while largely preserving side-chain size.

Glu339 is conserved in all three species analysed (*H. sapiens*, *O. aries* and *X. laevis*; Table Y), indicating that this position has been maintained across mammals and amphibians. Notably, glutamate-to-lysine exchanges are generally tolerated during evolution (BLOSUM62 score +1), which suggests that the effect of E339K depends on the specific structural environment of residue 339 rather than on the substitution itself.

## Structural mechanism and kinetic impact of the GCK E339K mutation

In individuals carrying the heterozygous E339K mutation in the GCK gene, cells express one functional wild-type allele alongside one mutated allele. In the wild-type (WT) structure, the glutamic acid residue at position 339 (Glu339) forms two key hydrogen bonds: one with His416 at a distance of 2.8 Å and another with Arg422 at 3.3 Å. These interactions stabilize helix 9 and keep His416 properly aligned. 

In the E339K mutant, Glu339 is substituted by a positively charged lysine (Lys339), so this stabilizing network is lost. 
Lys339 reorients 180º to form a new hydrogen bond, since two positive charges repel each other (His416 - Lys339), which shortens helix 9 and destabilizes the surrounding region.
The loss of the hydrogen bond with residue 339 allows the side chain of His416 to rotate by nearly 90º directly into the ATP-binding pocket. The 3D structure of the protein shows that when His416 rotates, it gets too close to the ATP binding site (just 1.5 Å away). This creates a physical collision that blocks ATP from entering (Figure 1). At the same time, the mutant enzyme undergoes accidental autophosphorylation at Serine 411 (Ser411), attaching a phosphate group to its own serine using cellular ATP.
The resulting phosphorylated serine forms a new hydrogen bond with Thr82, pulling the surrounding loop 3 Å closer to the large domain. Together, Ser411 and Thr82 act as a physical closed door that seals the entrance to the ATP pocket (Figure 2).

These structural modifications directly alter the kinetic properties of the mutant enzyme. The combined blockage by His416 and the Ser411-Thr82 interaction reduces the enzyme's affinity for ATP by 5 times, increasing the Km value from 0.32 mM in the wild-type enzyme to 1.50 mM in the mutant. Additionally, the overall relative activity drops by 80%, leaving the mutant enzyme with only 20% of its normal catalytic capacity.  This ultimately translates to glucose S{0.5} increasing  from 8.65 mM to 15.44.

Because the mutant protein loses 80% of its activity, pancreatic cells need higher blood sugar levels than normal to release insulin. This higher limit is the direct cause of high blood sugar (hyperglycemia) in MODY2 patients.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a0606261-466c-4d71-b35e-d553df7bada0" width="450" alt="Figure 1"><br>
      <sub><b>Figure 1.</b> 3D structure highlighting the 90° rotation of His416 into the ATP-binding pocket (PDB: 3QIC). Blue for Wild-type structure and orange of mutant variant.</sub>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/b98a2231-b9dc-47f1-a11a-10a1886ddcf3" width="450" alt="Figure 2"><br>
      <sub><b>Figure 2.</b> Detail of the phosphorylated Ser411 and Thr82 interaction forming the closed door mechanism. Blue for Wild-type structure and orange of mutant variant.</sub>
    </td>
  </tr>
</table>

## Discussion

**Table 2.** Kinetic parameters and fasting glucose levels associated with wild-type and E339K human glucokinase.

| Variant | Glucose S<sub>0.5</sub> (mM) | ATP K<sub>m</sub> (mM) | Relative activity | Fasting glucose concentration | Interpretation |
|---|---|---|---|---|---|
| Wild-type | 8.65 ± 0.28 | 0.32 ± 0.06 | 1.00 | 3.9–5.5 mM | Efficient ATP binding and glucose responsiveness within the physiological range set the threshold for insulin secretion at ~5 mM. |
| E339K | 15.44 ± 0.48 |  1.50 ± 0.18 | 0.20 | ~5.5–8 mM | ~5-fold weaker ATP binding and a ~2-fold higher glucose requirement reduce estimated activity to 20%, raising the β-cell glucose threshold for insulin secretion. Retention of one wild-type allele limits this to mild, stable hyperglycaemia. |

Kinetic parameters were measured in vitro using recombinant enzyme (mean ± SE of three preparations) and are taken from Liu et al. [1]. S<sub>0.5</sub> and n<sub>H</sub> (Hill coefficient) were derived from the Hill equation and K<sub>m</sub> from the Michaelis–Menten equation. Relative activity is an index calculated from k<sub>cat</sub>, S<sub>0.5</sub>, n<sub>H</sub> and ATP K<sub>m</sub>, normalised to wild-type.
<sup>a</sup> Normal fasting glucose range. <sup>b</sup> Typical range reported for GCK-MODY patients in general [X]; not measured specifically in E339K carriers.

Pregnancy can result in different problems or risks for the unborn child. The main problem arises from whether the fetus has inherited the mutation or not from one of the two progenitors. In the case that it indeed does have it, since both the mother and the child have slightly elevated glucose levels, the fetus’ liver does not sense any noticeable difference, and thus secretes the appropriate amount of insulin, resulting in a normal fetal growth. In the other case, where the fetus has not inherited the mutation, their liver detects the mother’s higher level of glucose, perceiving it as a hyperglycemia. This results in a hypersecretion of insulin, which serves as a key growth factor, consequently leading to macrosomia, the overgrowth of the fetus.

## References
1. Q. Liu, Y. Shen, S. Liu, J. Weng, and J. Liu, 'Crystal structure of E339K mutated human glucokinase reveals changes in the ATP binding site', *FEBS Letters*, vol. 585 (2011), doi: 10.1016/j.febslet.2011.03.026.
