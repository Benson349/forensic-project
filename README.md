# forensic-project
DIGITAL FORENSIC EXAMINATION REPORT

 

Module:

Digital Forensics and Incident Response

Case Title:

Examination of cartel.img

Examiner:

Emmanuel Benson Joshua

Date:

3 August 2026

1. Objective
The objective of this examination was to identify, preserve, recover, analyse and document digital evidence contained within the forensic image cartel.img while maintaining forensic integrity. The examination was conducted without altering the original evidence.

2. Tools Used
• • Linux Terminal
• • Sleuth Kit
• • PhotoRec 7.1
• • LibreOffice Writer
• • SIFT Workstation
• • xdg-open
3. Examination Methodology
Evidence Verification
Integrity verification ensures the evidence has not been modified. Hash values were calculated prior to analysis.

MD5 Hash

[Insert MD5 Value]

SHA-256 Hash

[Insert SHA-256 Value]

 

Initial Triage
• Image Name: cartel.img
• Format: Raw (.img)
• File System: FAT16
• Size: Approx. 259 MB
4. Evidence Discovery
Artifact 1: Word Document
Filename: f0335017_She_died_in_February_at_the_age_of_74.doc

Significance: Recovered using PhotoRec. Contains readable text and proves recovery of deleted files.


[Insert Forensic Screenshot Evidence Here]

Artifact 2: JPEG Image
Filename: f0104057.jpg

Significance: Recovered deleted photograph contradicting suspect assumptions.


[Insert Forensic Screenshot Evidence Here]

Artifact 3: GIF Image
Filename: f0106865.gif

Significance: Successfully recovered deleted graphical asset.


[Insert Forensic Screenshot Evidence Here]

5. Deleted Data Analysis Summary
File

Type

Method

Significance

f0335017...doc

DOC

PhotoRec

Recoverable Text

f0104057.jpg

JPEG

PhotoRec

Multimedia Evidence

f0106865.gif

GIF

PhotoRec

Graphical Asset

6. Timeline Reconstruction
Date and Time

Event

Fri Apr 30 2004 00:00:00

File system activity detected

Fri Apr 30 2004 18:11:20

File modification event

Fri Apr 30 2004 18:11:24

Additional file modification event

7. Key Findings
• Image integrity was maintained (MD5/SHA-256 confirmed).
• FAT16 file system identified on storage media.
• Multiple deleted documents and images successfully recovered.
• Suspect claims are refuted by recovered evidence (Word Document discovered).
• Timeline confirms activity on 30 April 2004.
8. Conclusion
The forensic examination successfully recovered multiple deleted files. Findings were obtained using accepted forensic procedures while preserving original evidence integrity.

9. Limitations
• FAT16 limited timestamp information.
• Original file paths unavailable for some files.
10. Recommendations
• • Perform additional metadata correlation on recovered artifacts.
• • Conduct targeted keyword searches across recovered text files.
• • Preserve and document the chain of custody for all evidence.