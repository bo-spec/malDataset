# APT Malware Dataset
This dataset contains over 3,500 malware samples that are related to 12 APT groups which alledgedly are sponsored by 5 different nation-states. This dataset was used for benchmarking different Machine Learning approaches performing authorship attribution. This dataset can be used for future benchmarks or malware research.

### Data Characteristics
The samples in the dataset are distributed as follows:

Country  | APT Group | Family | Requested | Downloaded
--- | --- | --- | ---: | ---:
China | APT 1 | | 1007 | 405
China | APT 10 | i.a. PlugX | 300 | 244
China | APT 19 | Derusbi | 33 | 32
China | APT 21 | TravNet | 118 | 106
Russia | APT 28 | *Bears* | 230 | 214
Russia | APT 29 | *Dukes* | 281 | 281
China | APT 30 | | 164 | 164
North-Korea | DarkHotel | DarkHotel | 298 | 273
Russia | Energetic Bear | Havex | 132 | 132
USA | Equation Group | Fannyworm | 395 | 395
Pakistan | Gorgon Group | Different RATs | 1085 | 961
China | Winnti | | 406 | 387
**Total** ||| **4449** | **3594**

### Remarks
All samples are named according to their SHA-256 hash and grouped by APT group. Samples are put in separate password-protected compressed folders (.zip). The password for all files is `infected`.

### Source
The malware samples are collected using open source threat intelligence reports from multiple vendors. Many threat intelligence reports were collected and a list of all filehashes used as indicators of compromise (IoC) has been collected. These hashes were used to obtain the malware samples from VirusTotal.

The file `overview.csv` contains an overview of all malware samples and the reports in which their hash-value has been found.

### Code Used for Authorship Attribution
The source code of the experiments performed for benchmarking authorship attribution performance can be found at GitHub: [APT Attribution Code](https://github.com/cyber-research/APTAttribution "APT Attribution Code").

### License
**Open Database License**

This APT Malware Dataset is made available under Open Database License whose full text can be found at http://opendatacommons.org/licenses/odbl/. Any rights in individual contents of the database are licensed under the Database Contents License whose text can be found http://opendatacommons.org/licenses/dbcl/.
