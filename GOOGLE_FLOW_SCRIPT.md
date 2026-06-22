# 🎬 Google Flow draaiboek — Middelweg 4F, Zevenhuizen

Cinematische dronevlucht die **van buiten naar binnen door het huis** beweegt:
langzaam naar voren induiken, in- en uitzoomen, vloeiend en filmisch.

Gemaakt voor **Google Flow** (Veo 3). Geen Higgsfield-credits nodig — je hebt
hiervoor een Google AI Pro/Ultra-abonnement nodig dat toegang geeft tot Flow.

---

## 🧭 Werkwijze in Flow (kort)

1. Open **labs.google/flow** → maak een nieuw project.
2. Kies model **Veo 3** (of Veo 3 Fast voor sneller/goedkoper).
3. Gebruik **"Frames to Video"**: upload een foto als **startframe**, schrijf de prompt.
4. Genereer een clip (±8 sec).
5. Klik **"Extend"** op de laatste clip om door te vliegen naar de volgende ruimte
   (plak dan de volgende prompt). Zo bouw je een doorlopende tour van ~30s+.
6. Exporteer als één video.

> **Tip:** elke clip is ~8s. 1 clip = de korte versie. 3-4 clips aan elkaar via
> Extend = de volledige "drone door het huis"-tour.

---

## 🎥 Algemene stijl (in elke prompt verwerkt)

`cinematic real-estate drone footage, smooth stabilized flowing camera motion,
slow continuous forward dolly / push-in, gentle parallax, photorealistic, soft
natural daylight, rich filmic color grading, shallow depth of field, no people,
no text, 16:9, 24fps film look`

---

## 📝 De clips (copy-paste prompts)

### CLIP 1 — Aankomst buiten  · startframe: **foto 1 (buitenaanzicht oprit)**
```
Cinematic aerial drone shot slowly flying forward over a gravel driveway toward a
modern Dutch house with a sloped roof and large black-framed glass entrance. The
camera glides steadily and smoothly forward, gently descending, pushing in toward
the front door. Soft natural daylight, blue sky with light clouds, lush green lawn,
photorealistic, filmic color grading, smooth stabilized motion, no people, no text.
```

### CLIP 2 — Entree induiken  · startframe: **foto 2 (entree close-up)**  *(of Extend van clip 1)*
```
The camera continues smoothly forward toward the tall glass entrance with vertical
wooden door panels, slowly pushing in as if about to enter the house. Subtle slow
zoom-in, steady drone-like glide, warm natural light reflecting off the glass,
photorealistic, cinematic, smooth motion, no people, no text.
```

### CLIP 3 — Hal & trap  · startframe: **foto 3 (hal/trap)**  *(of Extend van clip 2)*
```
Interior shot: the camera floats smoothly forward into a bright modern hallway with
a wooden staircase and black glass railing, herringbone wood floor, gliding past the
stairs. Slow flowing forward motion with a gentle upward tilt, soft daylight from the
side, photorealistic, cinematic real-estate look, smooth stabilized camera, no people.
```

### CLIP 4 — Woonkeuken & eethoek  · startframe: **foto 5 (open keuken/eethoek)**  *(of Extend van clip 3)*
```
The camera glides smoothly forward into a spacious open-plan living kitchen with a
dining table, designer chairs, a large kitchen island and floor-to-ceiling windows
looking out to the garden. Slow flowing forward dolly, then a gentle zoom-out to
reveal the full open space and natural light, photorealistic, cinematic, warm soft
daylight, smooth stabilized motion, no people, no text.
```

### CLIP 5 (optioneel) — Eethoek detail / uitzoom finale · startframe: **foto 4 (eethoek)**
```
Slow cinematic push-in toward the dining area with a round wooden table and natural
plants, then a smooth pull-back / zoom-out through the open living space toward the
garden windows for a final reveal. Soft golden daylight, photorealistic, filmic,
flowing stabilized camera, no people, no text.
```

---

## 🔗 Volgorde voor de volledige tour (~30-40s)

`Clip 1 (buiten)` → `Clip 2 (entree)` → `Clip 3 (hal/trap)` → `Clip 4 (woonkeuken)` →
`Clip 5 (finale uitzoom)`

Gebruik telkens **Extend** zodat de overgangen vloeiend blijven.

## ⚙️ Aanbevolen instellingen in Flow
- Model: **Veo 3** (beste kwaliteit) of **Veo 3 Fast**
- Aspect ratio: **16:9**
- Outputs per prompt: 2-4 (kies de mooiste)
- Geen audio nodig → muziek kun je later in een editor toevoegen

## 📌 Welke foto bij welke clip
| Clip | Foto |
|------|------|
| 1 — Aankomst buiten      | Foto 1 (buitenaanzicht oprit) |
| 2 — Entree               | Foto 2 (entree close-up)      |
| 3 — Hal & trap           | Foto 3 (hal/trap)             |
| 4 — Woonkeuken           | Foto 5 (open keuken/eethoek)  |
| 5 — Finale (optioneel)   | Foto 4 (eethoek)              |
