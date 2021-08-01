# OCSInventory/GLPI-Script
Install OCSInventory, GLPI, MariaDB and OCS/GLPI plugin. <br />
<br />
This script must be run as **root**. It is also **hightly recommended** to use this script on a **fresh** installation.<br />
<br />
What can this script do ?<br />
* Install OCSInventory with MySQL.<br />
* Install GLPI with MySQL.<br />
* Install GLPI + OCSInventory with MySQL.<br />
* Choose Specific Version of OCS.<br />
* Choose Specific Version of GLPI.<br />
* Install OCSInventory, GLPI, MySQL individually.<br />
* Install Plugin to connect OCS with GLPI.<br />

# Download and use :
```shell
wget https://raw.githubusercontent.com/Lowan-S/OCSInventory_GLPI/main/install.sh
bash install.sh
```

# Supported OS :
| Operating System  | Version | Compatibility        | Recommended        | Notes                                |
| ----------------- | ------- | -------------------- | ------------------ | ------------------------------------ |
| Ubuntu            | 21.04   | :heavy_check_mark:   | :heavy_check_mark: |                                      |
|                   | 20.04   | :heavy_check_mark:   | :heavy_check_mark: |                                      |
|                   | 18.04   | :heavy_check_mark:   | :yellow_circle:    |                                      |
| Debian            | 10      | :heavy_check_mark:   | :heavy_check_mark: | **Highly recommended**               |
| CentOS Linux      | 8       | :red_circle:         | :red_circle:       | https://www.centos.org/download/     |
|                   | 7       | :red_circle:         | :red_circle:       | All CentOS won't work, I will fix it |
| CentOS Stream     | 8       | :red_circle:         | :red_circle:       | later.                               |
| Fedora            | 34      | :yellow_circle:      | :heavy_check_mark: | OCS Install is working but not GLPI  |
| ----------------- | ------- | -------------------- | -----------------> | Tested under KVM, LXC & Bare Metal   |
