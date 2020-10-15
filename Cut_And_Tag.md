Load adapters onto pA-Tn5:
Dilute the ~15uM protein to 11uM while maintaining the same buffer composition. (Add mixture of HEGX+ buffer, but with 50% glycerol)

•	Adaptation of the FAQ on protocols.io and the nature paper for cut and tag:
o	Resuspend oligos to 200uM in 10mM Tris pH8, 50mM NaCl, 1mM EDTA
o	Mix 2.5uL MEB & 2.5uL MERev, anneal by heating to 95°C for 2min on PCR block, let cool slowly on benchtop for 5min to anneal oligos. Do the same for MEA & MERev. Now we have 5uL 100uM annealed MEA/Rev and 5uL 100uM MEB/Rev.
o	Add 4uL of MEA/MERev and 4uL MEB/Rev to 50uL 11uM protein
o	Incubate for 1 hour at room temp with rotation (Step1 on protocols.io)

Proceed with cut and tag.


Modified Henikoff Protocol:

1.	Prepare buffers. Same as Henikoff protocol.
a.	10uL ConA beads per sample
b.	10mL binding buffer
c.	200uL wash buffer per sample

Prep Beads and Cells

2
Gently resuspend and withdraw enough of the ConA bead slurry such that there will be 10 μL for each final sample of 100,000 cells. The following is for 16 samples.

3
Transfer 170 µL ConA bead slurry into 1.6 mL Binding buffer in a 1.5 mL tube and mix by pipetting. Place the tube on a magnet stand to clear (30 s to 2 min). 

4
Withdraw the liquid completely, and remove from the magnet stand. Add 1.5 mL Binding buffer, mix by pipetting, remove liquid from the cap with a quick pulse on a microcentrifuge.

5
Place on magnet stand to clear, withdraw liquid, and resuspend in 170 µL Binding buffer (10 μL per sample) and hold until cells are washed and ready.

6
CRITICAL STEP:All steps prior to the cell permeabilization are performed at room temperature to minimize stress on the cells. We recommend that cavitation during resuspension and vigorous vortexing be avoided.

Harvest fresh culture(s) at room temperature and count cells. The same protocol can be used for up to ~100,000 mammalian cells per sample to be sequenced.

If necessary, cells can be cryopreserved in 10% DMSO using a Mr. Frosty isopropyl alcohol chamber. For fresh or frozen tissues, we recommend adapting tissue preparation procedures developed for CUT&RUN: https://www.protocols.io/view/cut-run-with-drosophila-tissues-umfeu3n and 
https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-018-0243-8 (Figures 5-6). 

7
Centrifuge 3 min 600 x g at room temperature and withdraw liquid. 

This can be done in any 96 well plate that pellets cells well and can hold enough volume of the cell samples (at ~1M cells per mL in growing cultures, the 100K cell aliquots from step6 will be roughly 100uL volumes but this volume could vary depending on the cell density)

8
Resuspend each sample in at least 1 volume Wash buffer at room temperature, centrifuge 3 min 600 x g at room temperature and withdraw liquid.

9
Resuspend each sample in 95uL Wash buffer. Add 10 uL bead slurry, dropwise. Mix gently with repeated pipetting. Seal plate with tape or foil and place on nutator for 5-10 min.

10
After a quick spin to remove liquid from foil (<100 x g), place the PCR plate on a magnet stand to clear and withdraw the liquid. 

Bind primary antibody (2 hr to overnight)

11
Resuspend each sample in 50 uL ice-cold Antibody buffer and place on ice.

12
Add 0.5-1 µL primary antibody to each sample. Mix gently with repeated pipetting.
 
The Henikoff lab uses 1:50 - 1:100 by default, or the manufacturer’s recommended concentration for immunofluorescence.

13
Seal plate. Place on nutator at 4 °C and incubate at overnight to several days at 4 °C. Alternatively, nutate for 2 hr at room temperature. 

CRITICAL STEP: To evaluate success of the procedure without requiring library preparation, include in parallel a positive control antibody (e.g.α-H3K27me3), and optionally a negative control antibody (e.g. rabbit α-mouse IgG).

We have not noticed any difference between the efficiency of a 2 hr room temperature incubation and an overnight 4 °C incubation. We have successfully performed CUT&RUN and CUT&Tag after 4 °C incubation for up to 5 days.


Bind secondary antibody (1 hr)

14 
After a quick spin to remove liquid from cap (<100 x g), place each tube on the magnet stand to clear and pull off the liquid.
 
15
Mix secondary antibody 1:100 in Dig-wash buffer and squirt in 100 µL per sample. Gently pipette to mix and dislodge the beads from the sides of the well.
Although not needed for CUT&RUN, the secondary antibody step is required for CUT&Tag to increase the number of Protein A binding sites for each bound antibody. We have found that without the secondary antibody the efficiency is very low.

16
Place the tubes on a nutator at room temperature for 30–60 min.
00:30:00 

17
After a quick spin, place the tubes on a magnet stand to clear and withdraw the liquid.

18
Add 180 uL Dig-wash buffer. Invert 10x or gently pipette to allow the solution to dislodge most or all of the beads.

19
Repeat Steps 17-18 twice.

Bind pA-Tn5 adapter complex (1.5 hr)

20
Mix pA-Tn5 adapter complex in Dig-300 buffer to a final concentration of 1:250 for 100 µL per sample.

CRITICAL STEP: pA-Tn5 aliquots received from the CUT&RUN team are pre-loaded with adapters suitable for single- or dual-indexing on a paired-end Illumina flow-cell platform. 


21
After a quick spin, place the tubes on the magnet stand to clear and pull off the liquid.

22
Add 100 µL of pA-Tn5/Dig-300 mix and gently mix by pipetting.

The increased NaCl is necessary to avoid pA-Tn5 binding to accessible sites in chromatin, but can result in clumping, and in the presence of 0.05% digitonin can cause cell lysis. By reducing the digitonin concentration to 0.01% (from 0.05%) in the 300 mM NaCl buffer these problems are minimized. Barely visible clumps may appear when beads are suspended, but this does not appear to affect the efficiency of incubations or washes.

23
Place the tubes on a nutator at room temperature for 1 hr.

01:00:00

24
After a quick spin, place the tubes on a magnet stand to clear and pull off the liquid.

25
Add 180 uL Dig-300 buffer. Invert 10x or gently vortex to allow the solution to dislodge most or all of the beads.

26
Repeat steps 24-25 4 times.

Tagmentation (1 hr)

27
After a quick spin, place the tube on the magnet stand to clear and pull off the liquid.

28
Add 60 uL Tagmentation buffer and mix gently by pipetting.

29
Incubate at 37 ºC for 1 hr.
01:00:00

DNA Extraction (1 hr)

30
To stop tagmentation and solubilize DNA fragments, add 2 uL 0.5M EDTA, 0.6 uL 10% SDS to each sample (or 2.6 uL of master mix). Then add 1 uL of 10 mg/mL (0.5 uL of 20 mg/mL) Proteinase K to each sample.
 The proteinase K shouldn’t be added to the mastermix since it may not be stable in such a high SDS concentration. 

31
Mix by full-speed vortexing ~2 s, and incubate 1 hr 50 ºC or 37 ºC overnight to digest.
01:00:00

It is typical for the beads to form a large clump during incubation owing to the viscoelasticity of DNA. However, for abundant genome-wide epitopes, large-scale fragmentation of the genome will normally result in reduced clumping and release of beads into suspension, turning the liquid brownish relative to negative controls. 
 
Step 30) Left: H3K27me3; Right: IgG.



*Inactivate proteinase K for 10 min at 95°C. 

32
Perform column cleanup, eluting in 10 uL.
(Zmyo DNA Clean & Concentrator Kit, protocol for “PCR Product, DNA Fragment” – 5bindingbuffer:1sample) Use Zymo DNA binding buffer, for wash buffer use 80% EtOH.

Add 10 mM Tris-HCl pH8 and 1 mM EDTA containing 1/400 RNAse A to each sample:

RNAse Master Mix (per sample)
0.25 uL 1M Tris-HCl
0.06 uL 0.5M EDTA 
0.125 uL of 1/200 dilution of RNAse A
14.6 uL RNAse/DNAse-free water

Then add 15 uL of master mix to each 10 uL of eluted sample.

The large excess of RNA over DNA in the purified nucleic acid acts as a carrier during purification, but this RNA can skew estimates of DNA concentrations in the final libraries, so is best digested away prior to PCR and column clean-up.

41
Incubate 10 min 37 °C and store at 4 °C or proceed directly to the next step.
00:10:00

FINAL VOLUME- 25uL

PCR (1 hr)

42    Perform a test-run qPCR to determine whether or not the level of Threshold cycles (CT) matches what is expected. If desired, run a no-input negative control alongside samples of interest. 

Original PCR Recipe:
21 µL DNA + 2 µL Universal i5 primer (10 µM) + 2 µL uniquely barcoded i7 primers (10 µM) In a thin-wall 0.5 ml PCR tube, using a different barcode for each sample*. Save remaining DNA as a backup.

*Nextera primers or indexed primers described by Buenrostro, J.D. et al. Single-cell chromatin accessibility reveals principles of regulatory variation. Nature 523:486 (2015).

Alternative Recipe:

Master Mix (multiply by number of samples + 0.5 extra) 
*can also double once more if you wish to do 2 replicates per sample (recommended)

0.8 uL Nextera 5XX primer
0.8 uL Nextera 7XX primer
4.2 uL NEB Master Mix with 0.5X SyBr Green



Distribute 5.8uL of master mix into each well (or 11.6 if doubling) and separately add 4.2 uL of template DNA to each well (or 8.4 if doubling. Mix all in one well and divide into 2 x 10 uL reactions)

Total reaction volume- 10uL


Perform Ampure Cleanup (1.1X beads to sample volume) and quantify using a Qubit (High Sensitivity DNA)
