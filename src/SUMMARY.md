# A Rust Programozási Nyelv

[A Rust Programozási Nyelv](title-page.md)
[Előszó](foreword.md)
[Bevezetés](ch00-00-introduction.md)

## Kezdő lépések

- [Kezdő lépések](ch01-00-getting-started.md)
    - [Telepítés](ch01-01-installation.md)
    - [Hello, Világ!](ch01-02-hello-world.md)
    - [Hello, Cargo!](ch01-03-hello-cargo.md)

- [Egy találgatós játék programozása](ch02-00-guessing-game-tutorial.md)

- [Általános programozási koncepciók](ch03-00-common-programming-concepts.md)
    - [Változók és mutabilitás](ch03-01-variables-and-mutability.md)
    - [Adattípusok](ch03-02-data-types.md)
    - [Függvények](ch03-03-how-functions-work.md)
    - [Megjegyzések](ch03-04-comments.md)
    - [Vezérlési szerkezetek](ch03-05-control-flow.md)

- [Az ownership megértése](ch04-00-understanding-ownership.md)
    - [Mi az ownership?](ch04-01-what-is-ownership.md)
    - [Referenciák és kölcsönzés](ch04-02-references-and-borrowing.md)
    - [A szelet típus](ch04-03-slices.md)

- [Struktúrák használata kapcsolódó adatok szervezéséhez](ch05-00-structs.md)
    - [Struktúrák definiálása és példányosítása](ch05-01-defining-structs.md)
    - [Egy példaprogram struktúrák használatával](ch05-02-example-structs.md)
    - [Metódus szintaxis](ch05-03-method-syntax.md)

- [Felsorolások és mintaillesztés](ch06-00-enums.md)
    - [Felsorolás definiálása](ch06-01-defining-an-enum.md)
    - [A `match` vezérlési szerkezet](ch06-02-match.md)
    - [Tömör vezérlés `if let` segítségével](ch06-03-if-let.md)

## Alapvető Rust ismeretek

- [Növekvő projektek kezelése csomagokkal, ládákkal és modulokkal](ch07-00-managing-growing-projects-with-packages-crates-and-modules.md)
    - [Csomagok és ládák](ch07-01-packages-and-crates.md)
    - [Modulok definiálása a hatókör és láthatóság szabályozásához](ch07-02-defining-modules-to-control-scope-and-privacy.md)
    - [Elérési utak használata a modulfában lévő elemekhez](ch07-03-paths-for-referring-to-an-item-in-the-module-tree.md)
    - [Elérési utak láthatóvá tétele a `use` kulcsszóval](ch07-04-bringing-paths-into-scope-with-the-use-keyword.md)
    - [Modulok szétválasztása különböző fájlokba](ch07-05-separating-modules-into-different-files.md)

- [Általános gyűjtemények](ch08-00-common-collections.md)
    - [Értéklisták tárolása vektorokkal](ch08-01-vectors.md)
    - [UTF-8 kódolású szöveg tárolása karakterláncokkal](ch08-02-strings.md)
    - [Kulcs-érték párok tárolása hasítótáblákban](ch08-03-hash-maps.md)

- [Hibakezelés](ch09-00-error-handling.md)
    - [Helyreállíthatatlan hibák a `panic!` segítségével](ch09-01-unrecoverable-errors-with-panic.md)
    - [Helyreállítható hibák a `Result` típussal](ch09-02-recoverable-errors-with-result.md)
    - [`panic!` vagy nem `panic!`](ch09-03-to-panic-or-not-to-panic.md)

- [Generikus típusok, jellemvonások és élettartamok](ch10-00-generics.md)
    - [Generikus adattípusok](ch10-01-syntax.md)
    - [Jellemvonások: közös viselkedés definiálása](ch10-02-traits.md)
    - [Referenciák validálása élettartamokkal](ch10-03-lifetime-syntax.md)

- [Automatizált tesztek írása](ch11-00-testing.md)
    - [Hogyan írjunk teszteket](ch11-01-writing-tests.md)
    - [Tesztek futtatásának vezérlése](ch11-02-running-tests.md)
    - [Tesztek szervezése](ch11-03-test-organization.md)

- [Egy I/O projekt: parancssori program építése](ch12-00-an-io-project.md)
    - [Parancssori argumentumok fogadása](ch12-01-accepting-command-line-arguments.md)
    - [Fájl olvasása](ch12-02-reading-a-file.md)
    - [Refaktorálás a modularitás és hibakezelés javításához](ch12-03-improving-error-handling-and-modularity.md)
    - [A könyvtár funkcionalitásának fejlesztése tesztvezérelt fejlesztéssel](ch12-04-testing-the-librarys-functionality.md)
    - [Környezeti változók használata](ch12-05-working-with-environment-variables.md)
    - [Hibaüzenetek írása a szabványos hibakimenetre a szabványos kimenet helyett](ch12-06-writing-to-stderr-instead-of-stdout.md)

## Rust gondolkodásmód

- [Funkcionális nyelvi jellemzők: Iterátorok és zárások](ch13-00-functional-features.md)
    - [Zárások: Névtelen függvények, amelyek képesek a környezetük befogására](ch13-01-closures.md)
    - [Elemsorozatok feldolgozása iterátorokkal](ch13-02-iterators.md)
    - [I/O projektünk fejlesztése](ch13-03-improving-our-io-project.md)
    - [Teljesítmény összehasonlítása: Ciklusok vs. iterátorok](ch13-04-performance.md)

- [További információk a Cargo-ról és a Crates.io-ról](ch14-00-more-about-cargo.md)
    - [Fordítások testreszabása kiadási profilokkal](ch14-01-release-profiles.md)
    - [Láda publikálása a Crates.io-ra](ch14-02-publishing-to-crates-io.md)
    - [Cargo munkaterületek](ch14-03-cargo-workspaces.md)
    - [Binárisok telepítése a Crates.io-ról `cargo install` segítségével](ch14-04-installing-binaries.md)
    - [A Cargo kiterjesztése egyéni parancsokkal](ch14-05-extending-cargo.md)

- [Okos mutatók](ch15-00-smart-pointers.md)
    - [A `Box<T>` használata halmon tárolt adatokra mutatáshoz](ch15-01-box.md)
    - [Okos mutatók kezelése hagyományos referenciákként a `Deref` jellemvonással](ch15-02-deref.md)
    - [Kód futtatása takarításkor a `Drop` jellemvonással](ch15-03-drop.md)
    - [`Rc<T>`, a referenciaszámláló okos mutató](ch15-04-rc.md)
    - [`RefCell<T>` és a belső mutabilitás minta](ch15-05-interior-mutability.md)
    - [A referencia körök memóriaszivárgást okozhatnak](ch15-06-reference-cycles.md)

- [Félelemmentes párhuzamosság](ch16-00-concurrency.md)
    - [Szálak használata kód egyidejű futtatásához](ch16-01-threads.md)
    - [Üzenetküldés használata adatok átviteléhez szálak között](ch16-02-message-passing.md)
    - [Megosztott állapotú párhuzamosság](ch16-03-shared-state.md)
    - [Bővíthető párhuzamosság a `Sync` és `Send` jellemvonásokkal](ch16-04-extensible-concurrency-sync-and-send.md)

- [A Rust objektumorientált programozási jellemzői](ch17-00-oop.md)
    - [Objektumorientált nyelvek jellemzői](ch17-01-what-is-oo.md)
    - [Jellemvonás objektumok használata különböző típusú értékekhez](ch17-02-trait-objects.md)
    - [Egy objektumorientált tervezési minta implementálása](ch17-03-oo-design-patterns.md)

## Haladó témák

- [Minták és mintaillesztés](ch18-00-patterns.md)
    - [Minden hely, ahol minták használhatók](ch18-01-all-the-places-for-patterns.md)
    - [Cáfolhatóság: amikor egy minta nem illeszkedhet](ch18-02-refutability.md)
    - [Minta szintaxis](ch18-03-pattern-syntax.md)

- [Haladó funkciók](ch19-00-advanced-features.md)
    - [Nem biztonságos Rust](ch19-01-unsafe-rust.md)
    - [Haladó jellemvonások](ch19-03-advanced-traits.md)
    - [Haladó típusok](ch19-04-advanced-types.md)
    - [Haladó függvények és zárások](ch19-05-advanced-functions-and-closures.md)
    - [Makrók](ch19-06-macros.md)

- [Záró projekt: Többszálú webszerver építése](ch20-00-final-project-a-web-server.md)
    - [Egyszálú webszerver építése](ch20-01-single-threaded.md)
    - [Egyszálú szerverünk átalakítása többszálúvá](ch20-02-multithreaded.md)
    - [Kecses leállítás és takarítás](ch20-03-graceful-shutdown-and-cleanup.md)

- [Függelék](appendix-00.md)
    - [A - Kulcsszavak](appendix-01-keywords.md)
    - [B - Operátorok és szimbólumok](appendix-02-operators.md)
    - [C - Származtatható jellemvonások](appendix-03-derivable-traits.md)
    - [D - Hasznos fejlesztőeszközök](appendix-04-useful-development-tools.md)
    - [E - Kiadások](appendix-05-editions.md)
    - [F - A könyv fordításai](appendix-06-translation.md)
    - [G - Hogyan készül a Rust és a "Nightly Rust"](appendix-07-nightly-rust.md)
