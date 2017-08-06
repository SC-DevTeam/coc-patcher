Stripped version of https://github.com/royale-proxy/cr-patcher. 
Follow the instructions on the linked repo to use this patcher.

Changes:
* Stripped. Will patch only the ARM library. No checks on md5 as its supposed to be used by people that know what they are doing
* Patch the new encryption since 9.105.10 
* Enjoy

Limitations/bugs:
* Update is broken. I'll debug why later, you will need to install the original (unpatched) apk and let it update. Replace the patched libg in /data/data

Patch logic:
* http://www.giovanni-rocca.com/clash-clans-supercell-new-encryption-reverse-engineering/
