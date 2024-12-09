# Diplomova praca

témou diplomovej práce je predikcia budúcich nákladov (budúcej nákladovej skupiny) pacienta na základe jeho doterajších dát

## Dáta o pacientovi

### Datasety

- ambulantná zdravotná starostlivosť
- predpísané lieky


### Využívané dáta

- čas od prvého vyšetrenia
- vek pacienta
- ochorenia pacienta
- vyšetrenia pacienta
- lieky pacienta
- náklady (na vyšetrenie/liek)

## Použíté modely

- LaBSE -> embedding popisu zdravotníckeho výkonu
- RNN -> predikcia budúcich záznamov
- Decoder-only Transformer -> predikcia budúcich záznamov
- MLP -> Predikcia cenovej kategórie záznamu

## Plán práce

- embedding popisov/kódov -> hotovo
- vektorizácia celého záznamu pacienta -> hotovo
- vytvorenie časového radu záznamov pre pacienta -> hotovo
- návrh modelu (neurónovej siete) -> hotovo
- trénovanie modelov na malom datasete (lokálne) -> hotovo
- trénovanie modelov a nastavovanie hyperparametrov na veľkom datasete (server) -> január, február
- validácia celého modelu a spísanie výsledkov -> marec
- kotrola gramatiky a syntaxu -> apríl

## Priebežná verzia práce

[PDF diplomovej práce](https://github.com/MarianK-py/Diplomova_praca/blob/main/Praca/main.pdf)

## Prezentácia na seminár

[PDF prezentácie na seminár](https://github.com/MarianK-py/Diplomova_praca/blob/main/Prezentacia%20Seminar%202/x.pdf)

## Kód k projektu

[Kód diplomovej práce](https://github.com/MarianK-py/Diplomova_praca_kod) (priebežne privátne kvôli možnej prítomnosti citlivých údajov)