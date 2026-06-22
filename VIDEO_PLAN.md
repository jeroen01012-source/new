# 🎬 Drone-video plan — Middelweg 4F, Zevenhuizen

Vloeiende, cinematische dronevideo waarbij de camera langzaam **naar voren door/naar
het huis induikt**. Alles hieronder staat klaar; je hoeft alleen credits te hebben
en de foto te uploaden.

---

## ✅ Gekozen instellingen

| Onderdeel        | Keuze                                             |
|------------------|---------------------------------------------------|
| Camerabeweging   | Naar voren induiken (slow forward push-in)        |
| Sfeer / look     | Cinematisch (filmische kleurgradatie, contrast)   |
| Lengte           | 15 seconden — één doorlopende clip                |
| Geluid           | Geen audio (`sound: off`)                          |
| Beeldverhouding  | 16:9 (liggend)                                     |
| Bron             | Foto van Middelweg 4F (zelf uploaden)             |

## 🤖 Aanbevolen model

**Kling 3.0** (`kling3_0`) — beste voor cinematische, vloeiende camerabeweging.
- `mode`: `pro` (beste kwaliteit) of `std` (goedkoper)
- `sound`: `off`
- `duration`: `15`
- `aspect_ratio`: `16:9`
- `medias`: 1 foto met rol `start_image`

> Alternatief als je iets goedkoper/sneller wilt: **Seedance 2.0** (`seedance_2_0`,
> `generate_audio: false`).

## ✍️ De prompt (kant-en-klaar)

```
Cinematic aerial drone shot flying slowly and smoothly forward toward a beautiful
modern Dutch house. The camera glides steadily over a green lawn and pushes in toward
the facade, revealing architectural detail. Fluid stabilized motion, slow forward
dolly / push-in, subtle parallax, filmic color grading, soft natural light, deep rich
contrast, photorealistic, ultra-detailed, premium real-estate showcase. No text, no
people, no on-screen UI.
```

## 📋 Stappenplan zodra je credits hebt

1. **Upload de foto** van Middelweg 4F (Kling kan geen Funda-link lezen — eerst de
   afbeelding zelf uploaden).
2. Ik draai `generate_video` met het model + de prompt + instellingen hierboven.
3. Genereren duurt ±1-3 minuten.
4. Je krijgt de videolink terug.

## ⚠️ Aandachtspunten

- **Credits:** dit kost meer dan de huidige 0,96 credits op het gratis plan. Eerst
  upgraden of credits bijkopen.
- **Max 15s:** wil je toch ~30s, dan maken we 2-3 losse clips en plakken die aan
  elkaar (duurder, kleine sprongetjes tussen clips).
- **Funda:** foto's kunnen niet automatisch opgehaald worden — altijd zelf uploaden.
