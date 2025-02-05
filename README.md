# HTR_1-Timotheus

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

## Data

The data can be found at `./data/**/*xml` in ALTO format and follow [SegmOnto segmentation standards](https://segmonto.github.io). All data is produced using the eScriptorium interface and cataloged on [HTR-United](https://htr-united.github.io). The ALTO files have undergone manual correction, and the segmentation and transcription from the HTR are currently under review.

## Project 

This project focuses on the transcription and segmentation of 16th-century commentaries on the Pauline epistles. The data consists of various texts from notable authors, segmented and transcribed for further analysis. 

## Content Overview
![corpus](corpus/corpus_htr.csv)

| Identifier        | Presegmented | Segmentation | Transcription         | Resp | Files Total (Processed) | Author                        | Title                                          | Printer          | Date | Place      | Link Digital Book                                                                 | Library                              | Call Number             |
|------------------|-------------|-------------|----------------------|------|-------------------------|------------------------------|------------------------------------------------|----------------|------|-----------|----------------------------------------------------------------------------------|--------------------------------------|-------------------------|
| Aretius_1-Tim_001 | yes         | yes         | yes                  | FG   | 163 (16-178)[16-178]   | Benedictus Aretius           | *In Epistolas ad Timotheum ad Titum et ad Philemonem* | Jean Le Preux    | 1580 | Morges    | [here](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb10313792-3)           | München Bayerische Staatsbibliothek | Exeg. 53 Beibd.1        |
| Bucer_Rm_test    | yes         | yes         | WP                   | BM   | 54 (466-519)[466-486]  | Martin Bucer                | *Metaphrases et enarrationem in Epistolam ad Romanos* | Wendelin Rihel   | 1536 | Strasbourg | [here](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb11059175-0)           | Regensburg Staatliche Bibliothek    | 999/2Script.662         |
| Bucer_Eph_test   | yes         | yes         | yes (except Greek)   | NS   | 224 (1-224)[1-41]      | Martin Bucer                | *Epistolam ad Ephesios*                         | Anonymus        | 1527 | Strasbourg | [here](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb00035303-6)           | München Bayerische Staatsbibliothek | Polem. 408 Beibd.2      |
| Lefevre_Rm_test  | yes         | yes         | WP                   | MC   | 82 (203-284)[203-222]  | Jacques Lefèvre d'Étaples   | *Commentarii in epistolas d. Pauli*            | Anonymus        | 1512 | Paris      | [here](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb11059254-9)           | Regensburg Staatliche Bibliothek    | 999/2Script.801         |


### File Nomenclature

- **directory**: [exegete's name]\_[name of epistle(abbreviation of Vulgate)]\_[optional suffix or test(if the dataset is uncomplet)]  
  Example: `Aretius_1-Tim_001`,`Bucer_Eph_test`
- **file**: from mdz [urn of the book]\_[urn_of the page]\.xml
                    `bsb10313792_00016.xml`
                             
               
