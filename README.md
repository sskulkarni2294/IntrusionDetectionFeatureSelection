# IntrusionDetectionFeatureSelection
Data statistics table for each data set used

### Table 1. NSL KDD [1]

|Main Attack Type|Class|KDDTrain|KDDTest|
|:----|:----|:----|:----|
|**Normal**|Normal|40000|40000|
|**DoS**|smurf|10000|10000|
| |neptune|5000|5000|
| |back|1000|1203|
| |land|10|11|
| |teardrop|100|579|
| |pod|400|164|
| |Total|16510|16957|
|**PROBE**|satan|800|789|
| |portsweep|500|540|
| |nmap|110|121|
| |ipsweep|600|647|
| |Total|2010|2097|
|**R2L**|ftp_write|4|4|
| |guess_passwd|23|30|
| |multihop|7|5|
| |imap|23|4|
| |warezclient|520|500|
| |warezmaster|10|10|
| |phf|4|0|
| |spy|2|0|
| |Total|593|553|
|**U2R**|buffer_overflow|15|15|
| |rootkit|4|6|
| |loadmodule|4|5|
| |Perl|0|3|
| |Total|23|29|
|**Attacks Total**|Attacks Total|19136|19636|
|**Total**|Total|59,136|59,636|

### Table 2. CIC-IDS2017 [2]

|Class|No. of Observation|
|:----|:----|
|**Normal** |439,683|
|**DoS slowloris** |5796|
|**DoS Slowhttptest** |5499|
|**Dos Hulk** |230,124|
|**DoS GoldenEye** |10,293|
|**Heartbleed** |11|
|**Attacks** |251,723|
|**Total**|691,406|

### Table 3. Aegan Wi-Fi Intrusion Dataset [3]

|Class|AWID_CLS_TRN|AWID_CLS_TST|
|:----|:----|:----|
|**normal**|1633190|530785|
|**injection**|65379|20079|
|**impersonation**|48522|16682|
|**flooding**|48484|8097|
|**Attacks Total**|162385|44858|
|**Total**|1795575|575643|

### References
1. M. Tavallaee, E. Bagheri, W. Lu, A.A. Ghorbani, A detailed analysis of the kdd cup 99 data set, in: 2009 IEEE Symposium on Computational Intelligence for Security and Defense Applications, IEEE, 2009, pp. 1–6, doi: 10.1109/CISDA.2009.5356528.
2. I. Sharafaldin, A.H. Lashkari, A.A. Ghorbani, Toward generating a new intrusion detection dataset and intrusion traffic characterization., in: ICISSP, 2018, pp. 108–116, doi: 10.5220/0006639801080116 .
3. Kolias C, Kambourakis G, Stavrou A, Gritzalis S. Intrusion detection in 802.11 networks: empirical evaluation of threats and a public dataset. IEEE Communications Surveys & Tutorials. 2015 Feb 12;18(1):184-208.
