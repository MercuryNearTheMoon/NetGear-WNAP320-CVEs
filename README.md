# NetGear WNAP320 CVEs

## Requirements:

- AttifyOS 3.0 (Optional)
- Firmware Analysis Toolkit

## Build Emulator


1. enter your firmware-analysis-toolkit folder
    ``` bash
    cd ~/tools/firmware-analysis-toolkit
    ```

2. Run the fat.py with path of rootfs.squashfs
    ``` bash
    python3 ./fat.py ~/NetGear-WNAP320-CVEs/rootfs.squashfs
    ```

The website will open in http://192.168.0.100

Default **username/password**: `admin/password`

## Known CVEs

- CVE-2016-1555
- CVE-2016-1556
- CVE-2016-1557
- CVE-2016-18805
- CVE-2016-18806
- CVE-2016-18863
- CVE-2018-21094
- CVE-2018-21096
- CVE-2018-21097
- CVE-2018-21120
- CVE-2022-31876

## References

- AttifyOS: https://github.com/adi0x90/attifyos

- Firmware Analysis Toolkit: https://github.com/attify/firmware-analysis-toolkit

- CVE-2022-31876 exploit: https://github.com/nobodyatall648/Netgear-WNAP320-Firmware-Version-2.0.3-RCE/blob/main/wnap320_v2_0_3_RCE.py

- CVEs list: https://www.opencve.io/cve?vendor=netgear&product=wnap320


## Disclaimer

This repository and its contents are intended for educational and research purposes only. The information provided here is meant to help understand security vulnerabilities and improve the security of systems. Unauthorized access to computer systems, networks, or devices is illegal and unethical. The authors and contributors are not responsible for any misuse or damage caused by the use of the information provided in this repository. Use this information responsibly and only on systems for which you have explicit permission.

By using this repository, you agree to comply with all applicable local, state, national, and international laws and regulations.
