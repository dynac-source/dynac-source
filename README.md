- 👋 Welcome to the new DYNAC home page!
- 👀 Please feel free to check this page out if you're interested in a freeware linear accelerator beam dynamics program (open source code, works on MAC, Windows and Linux).
- 🌱 This git-hub page is work in progress.
- 💞️ Let me know if you're looking to collaborate on the further development of DYNAC.
- 📫 You can reach me at dynacatgithub at gmail.com

<!---
dynac-source/dynac-source is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# DYNAC-Home Page

**DYNAC: A multiparticle Beam Simulation Code for linear accelerators and beam transport lines**  
The computer code DYNAC contains a set of very accurate quasi-Liouvillian beam dynamics equations, introduced in 1994. It is applicable to protons, heavy ions and non-relativistic electrons. Long accelerating elements with complex and/or asymmetric longitudinal electromagnetic fields (e.g. superconducting cavities) may be treated as one cavity (in stead of individual cells) with this analytical method. This is achieved through the concept of the "equivalent accelerating field" [^1].

With the release of DYNAC V6R8, a numerical method became available in addition to the analytical method described above. The V6R8 version also already supported multi-charge state beams for a variety of beam line elements. This capability has been benchmarked against other beam dynamics codes [^2]. In the V6R9 version, the electrostatic dipole was added. In the following versions there are various enhancements, such as an improved treatment of the RMS section in an RFQ and some corrections. Further benchmarking is reported in [^3] and [^4]. In V6R17 a thick lense model was added for multi-harmonic bunchers. The source code for V7R0 was changed to f90, a first step towards f90 conversion. Performance was improved in terms of execution time of the routines related to the RFQ and the numerical cavity model.

DYNAC has several space charge routines, including a 3D space charge routine called HERSC [^5]. This routine derives from the typical procedure adopted in mathematical physics; the problem is transposed from some point to point correspondence onto a functional space spanned by a finite sequence of 3D Hermite functions, where the analytical set of beam self-field equations is found without any sort of restriction or basic hypothesis. 

You can **download DYNAC and its Graphical User Interface DGUI** from the [DYNAC V7R2 download page](https://github.com/dynac-source/DYNAC-download) 

**Older revisions of DYNAC**  
You can download DYNAC V7R1 and its Graphical User Interface DGUI from the [DYNAC V7R1 download page](https://github.com/dynac-source/DYNAC-download-V7R1)

**MORE INFORMATION**  
More information on DYNAC can be found in the following presentations:  
[Presentation made at SNS in November 2002](https://github.com/dynac-source/DYNAC-download/blob/main/dynac_presentation.pdf) (PDF format, 0.9 MB)  
[Presentation made at GSI in April 2015](https://github.com/dynac-source/DYNAC-download/blob/main/GSI_DYNAC_2015_Apr.pdf) (PDF format, 2.9 MB)  

Detailed descriptions of some of the elements and methodologies used are available:  
Electron gun: [EGUN in DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/egun_bode_2010_07_03.pdf)  
RFQ: [RFQ in DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/RFQ_2018_05_14.pdf)  
Cavity: [Description of the numerical method used in CAVNUM](https://github.com/dynac-source/DYNAC-download/blob/main/cavity_bode_2016_10_03.pdf)  
Relativistic electrons and synchrotron radiation: [Synchrotron radiation in DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/synch_rad_2010_07_03.pdf) 

**CONTACT**  
Eugene Tanke 
Email: dynacatgithub at gmail.com 

**REFERENCES**  
[^1]: [LINAC2002 Conference paper on DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/LINAC2002_TH429.PDF) (PDF format)  
[^2]: [LINAC2012 Conference paper on DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/LINAC2012_thpb065.pdf) (PDF format)  
[^3]: [LINAC2014 Conference paper on DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/LINAC2014_thpp043.pdf) (PDF format)  
[^4]: [LINAC2016 Conference paper on DYNAC](https://github.com/dynac-source/DYNAC-download/blob/main/LINAC2016_MOPRC007.pdf) (PDF format)  
[^5]: [LINAC2002 Conference paper on HERSC](https://github.com/dynac-source/DYNAC-download/blob/main/LINAC2002_TH424.PDF) (PDF format)  

**Date of most recent page update**  
03-Jan-2024
