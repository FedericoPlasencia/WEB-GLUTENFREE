# GlutenFree Market con Firebase

## 🚀 Instrucciones
1. Crear proyecto en Firebase (Firestore + Authentication).
2. Crear archivo `.env.local` en el root del proyecto:

```
VITE_FIREBASE_API_KEY=xxxx
VITE_FIREBASE_AUTH_DOMAIN=xxxx
VITE_FIREBASE_PROJECT_ID=xxxx
VITE_FIREBASE_STORAGE_BUCKET=xxxx
VITE_FIREBASE_MESSAGING_SENDER_ID=xxxx
VITE_FIREBASE_APP_ID=xxxx
```

3. Instalar dependencias y correr local:
```
npm install
npm run dev
```

4. Deploy a Vercel/Netlify configurando las variables de entorno.
