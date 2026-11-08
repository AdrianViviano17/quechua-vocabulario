# Guía y Especificaciones de Audios — SimiTaqa

Este directorio contiene las grabaciones en audio con la pronunciación auténtica de las palabras y expresiones en **Quechua Cusco-Collao** para la aplicación *SimiTaqa*.

---

##Convención de Nombres de Archivo

Para garantizar que la aplicación detecte los audios correctamente desde `index.html`, los archivos deben seguir estas reglas:

1. **Nombre en minúsculas:** Sin espacios ni caracteres especiales.
2. **Reemplazo de apostrofes (`'`):** Las letras con oclusivas/glotilizadas (ej. *Ch'aska*, *T'anta*, *P'acha*) deben escribirse eliminando el apóstrofe o usando guión bajo.
   - Ejemplo: `Ch'aska` `chaska.mp3` o `ch_aska.mp3`
3. **Formato admitido:** `.mp3` (recomendado por compatibilidad universal) o `.m4a`.

---

## 📊 Lista de Referencia de Audios

| ID | Palabra Quechua | Archivo Esperado (`audio/`) | Estado |
|---|---|---|---|
| 01 | Runa | `runa.mp3` | ⏳ Pendiente / 🎤 Listo |
| 02 | Wawqi | `wawqi.mp3` | ⏳ Pendiente / 🎤 Listo |
| 03 | Pani | `pani.mp3` | ⏳ Pendiente / 🎤 Listo |
| 04 | Tura | `tura.mp3` | ⏳ Pendiente / 🎤 Listo |
| 05 | Ñaña | `nana.mp3` | ⏳ Pendiente / 🎤 Listo |
| 06 | Tayta / Yaya | `tayta.mp3` | ⏳ Pendiente / 🎤 Listo |
| 07 | Mama | `mama.mp3` | ⏳ Pendiente / 🎤 Listo |
| 08 | Wawa | `wawa.mp3` | ⏳ Pendiente / 🎤 Listo |
| 09 | Pacha | `pacha.mp3` | ⏳ Pendiente / 🎤 Listo |
| 10 | Inti | `inti.mp3` | ⏳ Pendiente / 🎤 Listo |
| 11 | Killa | `killa.mp3` | ⏳ Pendiente / 🎤 Listo |
| 12 | Mayu | `mayu.mp3` | ⏳ Pendiente / 🎤 Listo |
| 13 | Orqo | `orqo.mp3` | ⏳ Pendiente / 🎤 Listo |
| 14 | Para | `para.mp3` | ⏳ Pendiente / 🎤 Listo |
| 15 | Ch'aska | `chaska.mp3` | ⏳ Pendiente / 🎤 Listo |
| 16 | Wasi | `wasi.mp3` | ⏳ Pendiente / 🎤 Listo |
| 17 | Puku | `puku.mp3` | ⏳ Pendiente / 🎤 Listo |
| 18 | T'anta | `tanta.mp3` | ⏳ Pendiente / 🎤 Listo |
| 19 | Yaku / Unu | `yaku.mp3` | ⏳ Pendiente / 🎤 Listo |
| 20 | P'acha | `pacha_ropa.mp3` | ⏳ Pendiente / 🎤 Listo |
| 21 | Q'echi | `qechi.mp3` | ⏳ Pendiente / 🎤 Listo |
| 22 | Rikch'ay | `rikchay.mp3` | ⏳ Pendiente / 🎤 Listo |
| 23 | Hatamuy | `hatamuy.mp3` | ⏳ Pendiente / 🎤 Listo |
| 24 | Mikhuy | `mikhuy.mp3` | ⏳ Pendiente / 🎤 Listo |
| 25 | Llanq'ay | `llanqay.mp3` | ⏳ Pendiente / 🎤 Listo |
| 26 | Puñuy | `punuy.mp3` | ⏳ Pendiente / 🎤 Listo |
| 27 | T'aqsakuikuy | `taqsakuikuy.mp3` | ⏳ Pendiente / 🎤 Listo |
| 28 | T'impuchiy | `timpuchiy.mp3` | ⏳ Pendiente / 🎤 Listo |
| 29 | Allianllachu | `allianllachu.mp3` | ⏳ Pendiente / 🎤 Listo |
| 30 | Allianmi | `allianmi.mp3` | ⏳ Pendiente / 🎤 Listo |
| 31 | Sulpayki / Añay | `sulpayki.mp3` | ⏳ Pendiente / 🎤 Listo |
| 32 | Tupananchiskama | `tupananchiskama.mp3` | ⏳ Pendiente / 🎤 Listo |
| 33 | Ama suwa... | `ama_suwa.mp3` | ⏳ Pendiente / 🎤 Listo |

---

## Recomendaciones de Grabación

- **Frecuencia de muestreo:** 44.1 kHz / 16-bit.
- **Tasa de bits (Bitrate):** 128 kbps a 192 kbps (suficiente calidad reduciendo el peso del archivo).
- **Normalización de Audio:** Mantener los picos de audio entre `-1 dB` y `-3 dB` para que todos los términos tengan el mismo volumen.
- **Silencio inicial/final:** Recortar los silencios largos antes y después de hablar (máximo 0.1 a 0.2 segundos de margen).
