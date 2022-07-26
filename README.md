# IntrusionDetectionFeatureSelection
Data statistics table for each data set used

### NSL KDD

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

### CIC-IDS2017
|Class|No. of Features|
|:----|:----|
|**Normal** |439,683|
|**DoS slowloris** |5796|
|**DoS Slowhttptest** |5499|
|**Dos Hulk** |230,124|
|**DoS GoldenEye** |10,293|
|**Heartbleed** |11|
|**Attacks** |251,723|
|**Total**|691,406|

### Aegan Wi-Fi Intrusion Dataset

|Class|AWID_CLS_TRN|AWID_CLS_TST|
|:----|:----|:----|
|**normal**|1633190|530785|
|**injection**|65379|20079|
|**impersonation**|48522|16682|
|**flooding**|48484|8097|
|**Attacks Total**|162385|44858|
|**Total**|1795575|575643|
