# muxy organization build

This fork is part of [muxy-terminal](https://github.com/muxy-terminal). Install release APKs signed with the muxy certificate, not upstream debug builds. Package names, shared UID, and Android permission checks are preserved.

Release APKs use certificate SHA-256 `756768af514d3fa0d1c214d54dabd7b0cd088a1723a22f520b90e8e8545262ce`. CI produces unsigned build artifacts and verifies published signed APKs. Private signing material is not stored here.
