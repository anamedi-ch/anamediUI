# 🌿 Anamedi openEHR Frontend

Ein leichtgewichtiges, modulares und benutzerfreundliches Open-Source-Frontend für openEHR CDRs – entwickelt unter dem Anamedi-Projekt. Inspiriert von OpenEMR, aber speziell auf die moderne openEHR REST API und interoperable Gesundheitsdaten ausgelegt.

---

## 🚀 Projektstatus

> **Aktueller Stand:** In aktiver Entwicklung – erste MVP-Funktionalitäten stehen!  
> Wir freuen uns ab jetzt über erste **Contributions, Ideen und Feedback**.

---

## 🎯 Ziel

Dieses Projekt soll ein flexibles UI-Frontend für openEHR-Daten bieten, das…

- eine intuitive **Patientenverwaltung** ermöglicht
- **Behandlungsverläufe (Encounters)** einsehbar und editierbar macht
- **Compositions dynamisch** aus Templates erzeugt
- vollständig auf der **openEHR REST API** basiert
- als **Basis für Erweiterungen** (Module, Plug-ins) dienen kann

---

## 🧱 Features (MVP)

- 🔍 **Patientenübersicht:** Liste, Suche, Detailansicht
- 📁 **Encounter-Verwaltung:** Anzeige vergangener Kontakte
- ✍️ **Erfassung neuer Daten:** Dynamische Composition-Formulare
- 🧠 **Template-Unterstützung:** Basierend auf Archetypes/Templates im CDR
- 🔐 Authentifizierung (optional)

---

## 🛠️ Tech Stack

| Bereich        | Technologie                     |
|----------------|----------------------------------|
| Frontend       | [Next.js](https://nextjs.org/), TypeScript, Tailwind CSS |
| State/API      | Zustand, React Query, Axios     |
| CDR-Anbindung  | openEHR REST API (v1.0.2+)      |
| Auth (optional)| Auth.js, OAuth2 oder Keycloak   |
| Hosting        | z. B. Vercel, Docker, Infomaniak|

---
## Lizenz

Dieses Projekt steht unter der GNU Affero General Public License v3.0 (AGPL-3.0).
Die Nutzung in Praxen ist frei. Bei Änderungen oder Weiterverbreitung muss der Quellcode offengelegt bleiben.

## 🧪 Lokale Entwicklung

```bash
# 1. Repo klonen
git clone https://github.com/anamedi/ehrboard.git
cd ehrboard

# 2. Abhängigkeiten installieren
pnpm install

# 3. .env.local Datei anlegen
cp .env.example .env.local
# ➤ Trage deine openEHR API-URL ein

# 4. Starten
pnpm dev


