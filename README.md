# Ethiek & Technologie Casus Generator

## Features
Een professionele web-applicatie voor het genereren van ethische casussen op het gebied van technologie, specifiek ontworpen voor professionals uit verschillende vakgebieden.
- **Vakgebied selectie**: Onderwijs, Gezondheidszorg, Bedrijfsleven, Overheid, Juridisch, Media & Communicatie
- **Technologie onderwerpen**: AI, Data & Privacy, Digitale Transformatie, Cybersecurity, Automatisering, Toezicht & Monitoring
- **Realistische casussen**: Gedetailleerde, Nederlandse context-specifieke ethische dilemma's
- **Belanghebbenden analyse**: Overzicht van stakeholders met hun belangen en perspectieven
- **Veilige API**: Backend API route beschermt de Mistral AI API key
## Deployment naar Vercel
### Stap 1: Vercel CLI installeren
```bash
npm i -g vercel
```
### Stap 2: Project deployen
```bash
vercel
```
### Stap 3: Environment variabele instellen
Na deployment, stel je API key in via Vercel dashboard:
1. Ga naar je project in Vercel dashboard
2. Navigeer naar Settings > Environment Variables
3. Voeg toe: `MISTRAL_API_KEY` met je Mistral AI API key als waarde
4. Redeploy het project
### Alternatief: Via Vercel CLI
```bash
vercel env add MISTRAL_API_KEY
```
## Lokale Development
1. Clone het project
2. Installeer dependencies: `npm install`
3. Maak een `.env` bestand met: `MISTRAL_API_KEY=your_api_key_here`
4. Start development server: `npm run dev`
## API Key verkrijgen
1. Ga naar [Mistral AI Console](https://console.mistral.ai/)
2. Maak een account aan of log in
3. Navigeer naar API Keys sectie
4. Genereer een nieuwe API key
5. Gebruik deze key in je environment variabelen