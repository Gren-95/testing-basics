# TC-001: Edukas sisselogimine
**Kriitilisus:** High  
**Eeltingimused:** 
- Kasutaja `user@example.com` eksisteerib süsteemis
- Kasutaja on välja logitud
- Veebileht on kättesaadav

### Testi kirjeldus
Testimine, kas kasutaja saab edukalt sisse logida süsteemi, kasutades kehtivat e-posti aadressi ja parooli.

### Testi andmed
- E-post: user@example.com
- Parool: Pass123!

### Testi sammud

| Samm | Tegevus | Oodatav tulemus |
|------|---------|-----------------|
| 1    | Ava `/login` leht | Login-vorm on kuvatud |
| 2    | Sisesta e-post `user@example.com` | Väli "Email" sisaldab sisestust |
| 3    | Sisesta parool `Pass123!` | Väli "Password" sisaldab sisestust |
| 4    | Vajuta "Login" nuppu | Kasutaja suunatakse `/dashboard` lehele |
| 5    | Kontrolli, kas kasutajanimi on kuvatud | Kasutajanimi on kuvatud ülemises paremas nurgas |

### Järeltingimused
- Kasutaja on sisse logitud
- Kasutaja on suunatud dashboard'ile
- Kasutaja sessioon on aktiivne

### Märkused
- Testi käigus tuleb veenduda, et parooli väli peidab sisestatud teksti
- Vajadusel saab testi korrata erinevate kehtivate kasutajakontodega

### Seotud nõuded
- REQ-001: Kasutaja autentimine
- REQ-002: Turvaline parooli sisestus

### Seotud testid
- TC-002: Ebaõnnestunud sisselogimine
- TC-003: Parooli taastamine 