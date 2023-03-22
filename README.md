# AzureHPCImages

## Ubuntu
```bash
$ az vm image list --all --publisher microsoft-dsvm --offer ubuntu-hpc --output table
Architecture    Offer       Publisher       Sku    Urn                                              Version
--------------  ----------  --------------  -----  -----------------------------------------------  ----------------
x64             ubuntu-hpc  microsoft-dsvm  1804   microsoft-dsvm:ubuntu-hpc:1804:18.04.2021051701  18.04.2021051701
x64             ubuntu-hpc  microsoft-dsvm  1804   microsoft-dsvm:ubuntu-hpc:1804:18.04.2021110101  18.04.2021110101
x64             ubuntu-hpc  microsoft-dsvm  1804   microsoft-dsvm:ubuntu-hpc:1804:18.04.2021120101  18.04.2021120101
x64             ubuntu-hpc  microsoft-dsvm  1804   microsoft-dsvm:ubuntu-hpc:1804:18.04.2022061601  18.04.2022061601
x64             ubuntu-hpc  microsoft-dsvm  1804   microsoft-dsvm:ubuntu-hpc:1804:18.04.2022121201  18.04.2022121201
x64             ubuntu-hpc  microsoft-dsvm  1804   microsoft-dsvm:ubuntu-hpc:1804:18.04.2023031501  18.04.2023031501
x64             ubuntu-hpc  microsoft-dsvm  2004   microsoft-dsvm:ubuntu-hpc:2004:20.04.2021051401  20.04.2021051401
x64             ubuntu-hpc  microsoft-dsvm  2004   microsoft-dsvm:ubuntu-hpc:2004:20.04.2021110101  20.04.2021110101
x64             ubuntu-hpc  microsoft-dsvm  2004   microsoft-dsvm:ubuntu-hpc:2004:20.04.2021120101  20.04.2021120101
x64             ubuntu-hpc  microsoft-dsvm  2004   microsoft-dsvm:ubuntu-hpc:2004:20.04.2022121201  20.04.2022121201
x64             ubuntu-hpc  microsoft-dsvm  2004   microsoft-dsvm:ubuntu-hpc:2004:20.04.2023011101  20.04.2023011101
x64             ubuntu-hpc  microsoft-dsvm  2004   microsoft-dsvm:ubuntu-hpc:2004:20.04.2023031501  20.04.2023031501
```

## CentOS
```bash
$ az vm image list --all --publisher OpenLogic --offer centos-hpc --output table
Architecture    Offer       Publisher    Sku       Urn                                           Version
--------------  ----------  -----------  --------  --------------------------------------------  --------------
x64             CentOS-HPC  OpenLogic    6.5       OpenLogic:CentOS-HPC:6.5:6.5.201803010        6.5.201803010
x64             CentOS-HPC  OpenLogic    6.8       OpenLogic:CentOS-HPC:6.8:6.8.201803010        6.8.201803010
x64             CentOS-HPC  OpenLogic    7.1       OpenLogic:CentOS-HPC:7.1:7.1.201803010        7.1.201803010
x64             CentOS-HPC  OpenLogic    7.1       OpenLogic:CentOS-HPC:7.1:7.1.2020101500       7.1.2020101500
x64             CentOS-HPC  OpenLogic    7.3       OpenLogic:CentOS-HPC:7.3:7.3.201803010        7.3.201803010
x64             CentOS-HPC  OpenLogic    7.3       OpenLogic:CentOS-HPC:7.3:7.3.2020101500       7.3.2020101500
x64             CentOS-HPC  OpenLogic    7.4       OpenLogic:CentOS-HPC:7.4:7.4.201807190        7.4.201807190
x64             CentOS-HPC  OpenLogic    7.4       OpenLogic:CentOS-HPC:7.4:7.4.2020101200       7.4.2020101200
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.20190327         7.6.20190327
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.20190529         7.6.20190529
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.20190721         7.6.20190721
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.201910250        7.6.201910250
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2020030200       7.6.2020030200
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2020031000       7.6.2020031000
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2020042000       7.6.2020042000
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2020062900       7.6.2020062900
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2020100800       7.6.2020100800
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2021022200       7.6.2021022200
x64             CentOS-HPC  OpenLogic    7.6       OpenLogic:CentOS-HPC:7.6:7.6.2021041900       7.6.2021041900
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.201910230        7.7.201910230
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2020031800       7.7.2020031800
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2020042000       7.7.2020042000
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2020043000       7.7.2020043000
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2020062600       7.7.2020062600
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2020100700       7.7.2020100700
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2021022400       7.7.2021022400
x64             CentOS-HPC  OpenLogic    7.7       OpenLogic:CentOS-HPC:7.7:7.7.2021041900       7.7.2021041900
x64             CentOS-HPC  OpenLogic    7_6gen2   OpenLogic:CentOS-HPC:7_6gen2:7.6.20200302     7.6.20200302
x64             CentOS-HPC  OpenLogic    7_6gen2   OpenLogic:CentOS-HPC:7_6gen2:7.6.2020042001   7.6.2020042001
x64             CentOS-HPC  OpenLogic    7_6gen2   OpenLogic:CentOS-HPC:7_6gen2:7.6.2020062901   7.6.2020062901
x64             CentOS-HPC  OpenLogic    7_6gen2   OpenLogic:CentOS-HPC:7_6gen2:7.6.2020100801   7.6.2020100801
x64             CentOS-HPC  OpenLogic    7_6gen2   OpenLogic:CentOS-HPC:7_6gen2:7.6.2021022201   7.6.2021022201
x64             CentOS-HPC  OpenLogic    7_6gen2   OpenLogic:CentOS-HPC:7_6gen2:7.6.2021041901   7.6.2021041901
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2020031801  7.7.2020031801
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2020042001  7.7.2020042001
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2020043001  7.7.2020043001
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2020062601  7.7.2020062601
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2020100701  7.7.2020100701
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2021022401  7.7.2021022401
x64             CentOS-HPC  OpenLogic    7_7-gen2  OpenLogic:CentOS-HPC:7_7-gen2:7.7.2021041901  7.7.2021041901
x64             CentOS-HPC  OpenLogic    7_8       OpenLogic:CentOS-HPC:7_8:7.8.2020121000       7.8.2020121000
x64             CentOS-HPC  OpenLogic    7_8       OpenLogic:CentOS-HPC:7_8:7.8.2021020400       7.8.2021020400
x64             CentOS-HPC  OpenLogic    7_8       OpenLogic:CentOS-HPC:7_8:7.8.2021041900       7.8.2021041900
x64             CentOS-HPC  OpenLogic    7_8-gen2  OpenLogic:CentOS-HPC:7_8-gen2:7.8.2020121001  7.8.2020121001
x64             CentOS-HPC  OpenLogic    7_8-gen2  OpenLogic:CentOS-HPC:7_8-gen2:7.8.2021020401  7.8.2021020401
x64             CentOS-HPC  OpenLogic    7_8-gen2  OpenLogic:CentOS-HPC:7_8-gen2:7.8.2021041901  7.8.2021041901
x64             CentOS-HPC  OpenLogic    7_9       OpenLogic:CentOS-HPC:7_9:7.9.2021052400       7.9.2021052400
x64             CentOS-HPC  OpenLogic    7_9       OpenLogic:CentOS-HPC:7_9:7.9.2022040100       7.9.2022040100
x64             CentOS-HPC  OpenLogic    7_9-gen2  OpenLogic:CentOS-HPC:7_9-gen2:7.9.2021052401  7.9.2021052401
x64             CentOS-HPC  OpenLogic    7_9-gen2  OpenLogic:CentOS-HPC:7_9-gen2:7.9.2022040101  7.9.2022040101
x64             CentOS-HPC  OpenLogic    8_1       OpenLogic:CentOS-HPC:8_1:8.1.2020041300       8.1.2020041300
x64             CentOS-HPC  OpenLogic    8_1       OpenLogic:CentOS-HPC:8_1:8.1.2020043000       8.1.2020043000
x64             CentOS-HPC  OpenLogic    8_1       OpenLogic:CentOS-HPC:8_1:8.1.2020062400       8.1.2020062400
x64             CentOS-HPC  OpenLogic    8_1       OpenLogic:CentOS-HPC:8_1:8.1.2020121000       8.1.2020121000
x64             CentOS-HPC  OpenLogic    8_1       OpenLogic:CentOS-HPC:8_1:8.1.2021020400       8.1.2021020400
x64             CentOS-HPC  OpenLogic    8_1       OpenLogic:CentOS-HPC:8_1:8.1.2021042000       8.1.2021042000
x64             CentOS-HPC  OpenLogic    8_1-gen2  OpenLogic:CentOS-HPC:8_1-gen2:8.1.2020041301  8.1.2020041301
x64             CentOS-HPC  OpenLogic    8_1-gen2  OpenLogic:CentOS-HPC:8_1-gen2:8.1.2020043001  8.1.2020043001
x64             CentOS-HPC  OpenLogic    8_1-gen2  OpenLogic:CentOS-HPC:8_1-gen2:8.1.2020062401  8.1.2020062401
x64             CentOS-HPC  OpenLogic    8_1-gen2  OpenLogic:CentOS-HPC:8_1-gen2:8.1.2020121001  8.1.2020121001
x64             CentOS-HPC  OpenLogic    8_1-gen2  OpenLogic:CentOS-HPC:8_1-gen2:8.1.2021020401  8.1.2021020401
x64             CentOS-HPC  OpenLogic    8_1-gen2  OpenLogic:CentOS-HPC:8_1-gen2:8.1.2021042001  8.1.2021042001
```
