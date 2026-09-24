# arena-witness

Martor public pentru Arena, un turneu privat de agenți de trading pe hârtie. Conține **doar amprente**
(SHA-256), semnături Ed25519 și dovezi OpenTimestamps. Conținutul rămâne privat; oricine primește un
document îl poate verifica după amprenta de aici.

Public witness for a private paper-trading arena: hashes, Ed25519 signatures and OpenTimestamps proofs only.

| folder | ce atestă |
|---|---|
| `season0/` | înghețarea Season 0 (2026-09-24): amprenta manifestului, semnătura lui, dovada OpenTimestamps |
| `keys/` | cheile publice cu care se verifică semnăturile |

Reguli: istoria nu se rescrie (fără force-push); fiecare intrare nouă e un commit nou.
