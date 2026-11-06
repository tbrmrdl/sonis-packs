# Sonis səs paketləri

[Sonis](https://github.com/tbrmrdl/sonis) musiqi tətbiqi üçün pulsuz səs paketləri.

Bütün səslər Sonis-in synth mühərriki ilə riyazi olaraq yaradılıb. Səslər **CC0** lisenziyasındadır: istənilən məqsədlə, o cümlədən kommersiya üçün, müəllif adı göstərmədən istifadə etmək olar.

| Paket | Səs sayı | Nə üçün |
|---|---|---|
| Texno nağaralar | 30 | Kick, clap, hat, ride, rim, perkussiya, tom |
| Hard techno | 19 | Distorsiyalı kick, rumble, industrial clap, metal perc, loop |
| Bas və stab | 14 | A tonallığında bas, stab akkordları, pad |
| FX və keçidlər | 6 | Riser, downlifter, impact, sweep, reverse crash |

Tətbiq paketləri [`manifest.json`](manifest.json) faylından oxuyur. Formatı belədir:

```json
{"packs": [{"id": "...", "name": "...", "description": "...", "genre": "...", "sounds": [{"name": "...", "url": "packs/<id>/<fayl>.wav"}]}]}
```

`url` manifestə nisbətən verilir. Format: WAV, 16-bit, mono, 44.1 kHz.
