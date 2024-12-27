# A Rust programozási nyelv

*írta Steve Klabnik és Carol Nichols, a Rust közösség közreműködésével*

A szöveg ezen verziója feltételezi, hogy Rust 1.37.0 vagy újabb verziót használsz
`edition="2018"` beállítással minden projekt *Cargo.toml* fájljában a Rust 2018 Edition
idiómák használatához. Tekintsd meg az ["1. fejezet Telepítés" szakaszát][install]<!-- ignore -->
a Rust telepítéséhez vagy frissítéséhez, és nézd meg az új [E függeléket][editions]<!-- ignore -->
az edíciókkal kapcsolatos információkért.

A Rust nyelv 2018-as kiadása számos olyan fejlesztést tartalmaz, amelyek
ergonomikusabbá és könnyebben tanulhatóvá teszik a Rust-ot. A könyv ezen változata
számos módosítást tartalmaz, hogy tükrözze ezeket a fejlesztéseket:

- A 7. fejezet, "Növekvő projektek kezelése csomagokkal, ládákkal és modulokkal"
  nagyrészt át lett írva. A modulrendszer és az elérési utak működése a
  2018-as kiadásban konzisztensebbé vált.
- A 10. fejezet új szakaszokat tartalmaz "Jellemvonások mint paraméterek" és "Jellemvonásokat
  implementáló típusok visszaadása" címmel, amelyek elmagyarázzák az új `impl Trait` szintaxist.
- A 11. fejezet egy új szakaszt tartalmaz "A `Result<T, E>` használata tesztekben" címmel,
  amely bemutatja, hogyan írhatunk teszteket a `?` operátor használatával.
- A "Haladó élettartamok" szakasz a 19. fejezetből eltávolításra került, mivel a fordítóprogram
  fejlesztései még ritkábbá tették az abban a szakaszban tárgyalt szerkezeteket.
- A korábbi D függelék, "Makrók", ki lett bővítve procedurális makrókkal és
  átkerült a 19. fejezet "Makrók" szakaszába.
- Az A függelék, "Kulcsszavak", elmagyarázza az új nyers azonosítók funkcióját is,
  amely lehetővé teszi a 2015-ös és 2018-as kiadásban írt kód együttműködését.
- A D függelék most "Hasznos fejlesztőeszközök" címet viseli, és a közelmúltban
  megjelent eszközöket tárgyalja, amelyek segítenek a Rust kód írásában.
- Számos kisebb hibát és pontatlan megfogalmazást javítottunk a könyvben.
  Köszönjük az olvasóknak, akik jelezték ezeket!

Megjegyzendő, hogy *A Rust programozási nyelv* korábbi verzióiban szereplő kódok
továbbra is fordíthatók maradnak `edition="2018"` nélkül a projekt
*Cargo.toml* fájljában, még akkor is, ha frissíted a használt Rust fordítót.
Ez a Rust visszafelé kompatibilitási garanciájának köszönhető!

A HTML formátum online elérhető a
[https://doc.rust-lang.org/stable/book/](https://doc.rust-lang.org/stable/book/)
címen és offline a `rustup`-pal telepített Rust verzióknál; futtasd a `rustup docs
--book` parancsot a megnyitáshoz.

Ez a szöveg elérhető [papírkötésű és e-book formátumban a No Starch
Press kiadónál][nsprust].

[install]: ch01-01-installation.html
[editions]: appendix-05-editions.html
[nsprust]: https://nostarch.com/rust
