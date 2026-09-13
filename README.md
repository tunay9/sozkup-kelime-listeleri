# Söz Küp — Kelime Listeleri

Söz Küp adlı kelime bulmaca oyununda kullanılan kelime listeleri
ve harf sıklık verileri.

## Dosyalar

| Dosya | Dil | Kelime |
|---|---|---|
| words_es.txt | İspanyolca | 32.594 |
| words_fr.txt | Fransızca | 32.188 |
| words_pt.txt | Portekizce | 29.427 |
| words_ru.txt | Rusça | 32.886 |

`harf_frekans_*.json` dosyaları, her dilin 3-5 harfli kelimelerinden
hesaplanmış harf sıklıklarını içerir. Oyun harf havuzunu bunlara göre
kuruyor.

## Nasıl türetildi

Kaynak listeler sıklığa göre sıralı ilk 50.000 kelimeden oluşuyor.
Uygulanan süzgeçler:

- Yalnızca 3-8 harf arası kelimeler
- Yalnızca o dilin alfabesindeki harfler (aksanlılar dahil)
- Küfür ve müstehcen kelimeler ayıklandı
- Tekrarlar kaldırıldı, alfabetik sıraya dizildi

## Kaynak

[FrequencyWords](https://github.com/hermitdave/FrequencyWords) — Hermit Dave

Veriler [OpenSubtitles](https://opus.nlpl.eu/OpenSubtitles2018.php)
altyazı derlemesinden üretilmiştir.

## Lisans

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.tr)

Bu listeleri kullanabilir, değiştirebilir ve dağıtabilirsin. Tek şart:
kaynağı belirtmen ve türevlerini aynı lisansla paylaşman.
