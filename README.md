# KeyCoverage

Kayıtlarda her alanın varlık oranını hesaplar.

## Girdi

Nesne dizisi.

## Kullanım

Python 3.11+, standart kütüphane.

```sh
python keycoverage.py input.json
python verify.py
```

Dosya verilmezse stdin okunur. Sonuç stdout üzerinde JSON olarak yazılır. Girdi hatası çıkış kodu 2 üretir.

Örnek sonuç:

```json
{
  "a": 1,
  "b": 0.5
}
```
