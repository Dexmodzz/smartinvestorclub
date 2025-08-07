# Vite React TypeScript Project

Questo progetto è un'applicazione React con TypeScript utilizzando Vite come bundler.

## Deploy su Railway

Questo progetto è configurato per essere facilmente deployato su [Railway](https://railway.app/).

### Prerequisiti

- Un account su Railway
- Railway CLI installato (opzionale)

### Passi per il Deploy

1. **Crea un nuovo progetto su Railway**

   - Vai su [Railway](https://railway.app/) e accedi al tuo account
   - Clicca su "New Project"
   - Seleziona "Deploy from GitHub repo"
   - Seleziona il repository contenente questo progetto

2. **Configura le variabili d'ambiente (se necessario)**

   - Nella dashboard del progetto, vai alla sezione "Variables"
   - Aggiungi le variabili d'ambiente necessarie (vedi `.env.example`)

3. **Deploy**

   - Railway rileverà automaticamente la configurazione nel file `railway.json`
   - Il deploy avverrà automaticamente

### Deploy Manuale con Railway CLI

```bash
# Installa Railway CLI (se non l'hai già fatto)
npm i -g @railway/cli

# Accedi a Railway
railway login

# Collega il progetto locale al progetto Railway
railway link

# Deploy
railway up
```

## Sviluppo Locale

```bash
# Installa le dipendenze
npm install

# Avvia il server di sviluppo
npm run dev

# Build per produzione
npm run build

# Anteprima della build di produzione
npm run preview
```