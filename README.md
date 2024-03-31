# Stratum for YiiMP
with balloon - yescrypt - yescryptR8 - yescryptR16 - yescryptR32 support trimmed for low difficulty shares

## ▶️ Installation

Requires a YiiMP Server installation.

```
git clone https://github.com/msy2008/stratum-lowdiff.git
```

* Compile
```
cd stratum-lowdiff/iniparser
make
cd ..
make
```

* Move stratum file
```
sudo mv stratum /home/yiimp-data/yiimp/site/stratum/stratum_lowdiff
```
* Move stratum file (msy2008 Yiimp Installer : https://github.com/msy2008/yiimp_install_scrypt)
```
sudo mv stratum /var/stratum/stratum_lowdiff
```

* After run addport modify run.sh with stratum_lowdiff
```
sudo vim /home/yiimp-data/yiimp/site/stratum/config/run.sh
```
* After run addport modify run.sh with stratum_lowdiff (msy2008 Yiimp Installer : https://github.com/msy2008/yiimp_install_scrypt)
```
sudo vim /var/stratum/config/run.sh
```
