# 🏔️ Hotel Moderno Demonte — Camere · Ristorante · Natura

Sito ufficiale dell’**Hotel Moderno Demonte**, nel cuore della Valle Stura (CN).  
Ospitalità familiare, cucina piemontese e natura autentica: un punto di riferimento per soggiorni in montagna tra relax e tradizione.

[![Netlify Status](https://api.netlify.com/api/v1/badges/9b8c5dc8-146b-4253-8ffd-22d2944796a8/deploy-status)](https://app.netlify.com/projects/modernodemonte/deploys)

---

## 🔧 Stack Tecnico

- **Generator:** [Hugo](https://gohugo.io/) `v0.147.9`
- **Hosting/CDN:** [Netlify](https://www.netlify.com)
- **Repo:** [GitHub](https://github.com/emalinux/hotel-demonte)
- **Lingue supportate:** 🇮🇹 IT · 🇬🇧 EN
- **Tema:** Custom sviluppato da zero (`layouts/`, `partials/`, `style.css`)

---

## ⚙️ Deploy automatico

- Trigger: ogni `git push` su `main`
- Configurato tramite `netlify.toml`
- Dominio live: https://hoteldemonte.com
- Dominio preview: https://modernodemonte.netlify.app

---

## 📁 Struttura progetto

```plaintext
hotel-demonte/
├── assets/         # Risorse statiche (eventuali CSS/JS avanzati)
├── content/        # Contenuti multilingua
│   ├── it/
│   └── en/
├── layouts/        # Template Hugo (partials, baseof, list, single)
├── static/         # Immagini, favicon, CSS principale
├── hugo.toml       # Configurazione Hugo
├── netlify.toml    # Configurazione deploy Netlify
└── README.md
```
```plaintext
✨ Caratteristiche principali
	•	🌍 Multilingua IT / EN
	•	🧩 Struttura modulare con partials (hero, intro, camere, ristorante, CTA)
	•	🖼️ Galleria immagini con lightbox (GLightbox)
	•	📱 Design responsive mobile-first
	•	⚡ Performance elevate (no framework inutili)
	•	🔍 SEO base configurato (meta, hreflang, struttura pulita)
	•	🔒 HTTPS automatico (Netlify + Let’s Encrypt)
	•	🎯 UX semplice, chiara e orientata alla conversione
```

  ---

## 🧑‍💻 Autore

Realizzato con ❤️ da [Manuel – Assembler Computer](https://studio.assemblercomputer.net/)

Contatti diretti? [📧 emalinux77@gmail.com](mailto:emalinux77@gmail.com)

---

📝 Note tecniche

```plaintext
• Tema custom sviluppato da zero (no template preconfezionati)
• Multilingua gestito tramite /content/ con struttura separata
• Deploy automatico con versione Hugo controllata
• Layout riutilizzabile per progetti futuri (base Assembler)
• Ottimizzazione immagini in formato .webp
```
