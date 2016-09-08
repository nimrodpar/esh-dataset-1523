# esh-dataset-1523
The dataset used in the experiments for Esh (http://binsim.com)

The object files were attained by compiling (in different configurations) file from the following projects:
* [Coreutils](www.gnu.org/s/coreutils/)
* [OpenSSL](https://www.openssl.org/)
* [Bash](https://www.gnu.org/software/bash/)
* [ntpd](http://doc.ntp.org/4.1.0/ntpd.htm)
* [QEMU](qemu.org)
* [WireShark](https://www.wireshark.org)
* [Wget](https://www.gnu.org/software/wget/)

Our thanks goes out to these great and vital open source projects.

## Notes
* Each filename contains the creating compiler, the project name and version, the object file and the procedure it contains.
* The rest of the procedures in the object file were NOPed out and appear as stubs.
