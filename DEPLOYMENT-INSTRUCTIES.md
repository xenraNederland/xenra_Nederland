# Xenra Nederland - Complete Website Deployment

## Inhoud van deze map
Deze map bevat de COMPLETE Xenra Nederland website zonder formulieren:

- `index.html` - Hoofdpagina met alle content
- `assets/` - Alle JavaScript, CSS en afbeeldingen
- Team foto's: `hilko.png`, `sara.png`, `marcel.png`, `wendy.png`, `stevie-hq.png`
- Content afbeeldingen: `legal_documents.jpg`, `professional_consultation.jpg`
- SEO bestanden: `robots.txt`, `sitemap.xml`

## Website Features
✅ Volledige Xenra website (Home, Services, Over ons, Contact, Calculator, FAQ)
✅ Alle team members met foto's
✅ Premium calculator werkend
✅ Responsive design (mobiel + desktop)
✅ Google Analytics geïntegreerd
✅ SEO geoptimaliseerd
✅ GEEN FORMULIEREN = geen technische problemen

## Contact Methoden (in website)
- **Telefoon**: 085 08 06 142 (lokaal tarief) - directe bel-links
- **Email**: info@xenra.nl - directe email-links
- **WhatsApp**: 06-44 58 49 77 (noodgevallen)
- **Openingstijden**: Ma t/m za 07:00-20:00

## Deployment Opties

### Optie 1: GitHub + Vercel (AANBEVOLEN)
1. **GitHub Repository aanmaken**:
   - Ga naar github.com
   - Nieuwe repository: `xenra-website-clean`
   - Upload ALLE bestanden uit deze map

2. **Vercel Deployment**:
   - Ga naar vercel.com
   - Import from GitHub
   - Selecteer je repository
   - Framework: "Other"
   - Build settings: LEEG LATEN
   - Deploy

3. **Custom Domain**:
   - Vercel dashboard → Settings → Domains
   - Voeg toe: `xenra.nl` en `www.xenra.nl`
   - Kopieer DNS instellingen naar MijnHost

### Optie 2: Netlify
1. Sleep deze hele map naar netlify.com/drop
2. Site settings → Domain management
3. Add custom domain: xenra.nl

### Optie 3: Direct FTP Upload
1. Upload alle bestanden naar je hosting provider
2. Zorg dat index.html in de root staat
3. Assets map ook in de root

## DNS Instellingen (MijnHost)
```
A record: xenra.nl → [IP van hosting provider]
CNAME: www.xenra.nl → [domain van hosting provider]
```

## Belangrijke Notes
- **Alle bestanden nodig**: Upload de hele map, niet alleen index.html
- **Geen server code**: Dit is 100% statische website
- **Geen database**: Alle content zit in de HTML/JS
- **Geen formulieren**: Alleen directe contact links (tel:, mailto:, whatsapp)
- **Mobile ready**: Werkt perfect op alle apparaten

## Test na Deployment
Na deployment, test deze functies:
- [ ] Website laadt volledig
- [ ] Alle team foto's zichtbaar
- [ ] Premium calculator werkt
- [ ] Telefoon links openen telefoon app
- [ ] Email links openen email app
- [ ] WhatsApp link opent WhatsApp
- [ ] Responsive design werkt op mobiel

## Support
Voor deployment hulp: contact via Replit chat

## Bestandsoverzicht
```
xenra-complete-website/
├── index.html (18KB) - Hoofdpagina
├── assets/
│   ├── index-DJeOXoB9.js (690KB) - JavaScript
│   ├── index-BUfMqFJH.css (107KB) - Styling
│   └── [afbeeldingen] (3.4MB) - Website afbeeldingen
├── [team fotos] (2.1MB) - Team member fotos
├── [content fotos] (260KB) - Content afbeeldingen
├── robots.txt - SEO
├── sitemap.xml - SEO
└── DEPLOYMENT-INSTRUCTIES.md - Deze instructies
```

**TOTAAL: ~6.5MB complete website**
**STATUS: PRODUCTIE KLAAR ✅**