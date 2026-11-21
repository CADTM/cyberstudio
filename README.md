> Tu estudio completo en el navegador. Sin instalar nada. Graba, tunea, samplea y exporta.

**🔴 En vivo:** https://cadtm.github.io/cyberstudio/
**📦 Repo:** https://github.com/CADTM/cyberstudio.git

---

## 🚀 Abrir en 1 click

1. Entra a **https://cadtm.github.io/cyberstudio/**
2. Dale permiso al micrófono
3. Ponte audífonos y dale **REC**

No necesita backend, no necesita instalar nada. Todo corre con Web Audio API.

---

## 🔥 Qué trae

### 🎚️ 8 Pistas
- Mute / Solo / Rec por pista
- Fader de volumen, Pan, VU animado
- Importar WAV / MP3 con drag & drop
- Grabación real con micrófono

### 🎹 Sinte Polifónico
- Teclado virtual de 2 octavas + teclado de PC (A-L blancas)
- 2 osciladores: Sine, Saw, Square, Triangle con Detune
- Filtros Low / High / Band-pass, Cutoff + Resonance
- ADSR visual, LFO
- **Presets:** Neon Lead, Cyber Bass, Pad Espacial, Pluck Tijuana, 808 Sub

### 🎤 Autotune Pro
- Key + Escala (Mayor, Menor, Cromática, Pentatónica)
- Retune Speed: `0 = Robot tipo Travis / Cher` → `100 = Natural`
- Humanize, Vibrato, Bypass para comparar
- Visual: nota detectada vs nota corregida

#### Presets de Autotune
| Preset | Uso |
| :--- | :--- |
| **Travis Robot** | Retune 0, efecto robot extremo |
| **Cher Hard Tune** | Retune 0, vibrato 0 |
| **Tijuana Corrido Tumbado** | G Minor, Retune 20 |
| **Natural Pop** | Retune 80, corrección suave |
| **R&B Suave** | Retune 65, humanize alto |

> Puedes guardar **tus propios presets** con nombre. Se guardan en tu navegador.

### 🎤 Sampler Vocal
- Graba tu voz directo al sampler (3 seg por toma)
- Importa WAV / MP3
- 16 slots, Pitch -12 a +12 semitonos
- **Modo Chromatic:** toca tu voz como instrumento en todo el teclado C3-B4
- **Chop:** divide tu sample en 8 partes automáticamente
- Reverse, Loop, Speed 0.5x - 2x, Attack / Release

### 🥁 Pads 808
16 pads sintéticos: Kick 808, Snare, HiHat, Clap, Open Hat, Rim, Tom, Shaker, 808 Bass, Cowbell, Crash y más.

### 🎛️ Master
- VU estéreo, Vol Master
- BPM 60-200, Metrónomo
- Exportar mezcla a WAV

---

## 🎤 Flujo rápido para grabar un tema

```bash
1. Pon BPM 120 + Key G Minor
2. Tira tu beat con los Pads 808
3. Graba tu voz en Pista 1 con REC
4. Pon Autotune > Tijuana Corrido Tumbado
5. Graba un "yeah" en el Sampler > Modo Chromatic
6. Toca tu adlib con el teclado
7. Exporta a WAV
```

---

## 🛠️ Tecnologías

- **HTML5 + CSS3 + JavaScript puro** — sin frameworks pesados
- **Web Audio API** — osciladores, filtros, gain, pitch-shifting
- **MediaRecorder API** — grabación real del micro
- **LocalStorage** — presets de autotune guardados

---

## 📁 Estructura

```
cyberstudio/
├── index.html    # Todo el estudio en un solo archivo
├── README.md     # Este archivo
```

---

## 💻 Correr en local

```bash
git clone https://github.com/CADTM/cyberstudio.git
cd cyberstudio
# Abre index.html con doble click o con Live Server
```

---

## 🤝 Contribuir

¿Tienes un preset chido o un beat? Haz fork, súbelo y abre un PR.

---

## 👨‍💻 Autor

**CADTM / Cybercadtm** — Tijuana, B.C. 🇲🇽
- GitHub: [@CADTM](https://github.com/CADTM)
- Proyecto: CyberStudio

---

### ⭐ Si te latió, dale Star al repo
