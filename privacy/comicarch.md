# Privacy Policy — ComicArch (`com.devcarmelo.comicarch`)

**Effective Date:** November 12, 2026  
**Contact:** carmelo.freelancer@gmail.com

---

## English Version

### 1. Local File Processing
ComicArch processes `.cbz`, `.cbr`, and image files **100% locally on your device** using Android's **Storage Access Framework (SAF)**. Your comic files and internal metadata are never uploaded to or stored on external servers.

### 2. Third-Party Services (AdMob & Firebase)
ComicArch does not require user accounts. The app uses:
- **Google AdMob** (optional rewarded video ads to recharge operation credits) — may collect Advertising ID, approximate IP-based region, device details, and ad interaction metrics.
- **Firebase Analytics** — collects anonymized usage telemetry (screen views, operation types, selected language, and posture state).
- **Firebase Crashlytics** — collects crash stack traces and device/OS metadata to diagnose stability issues.

### 3. Local Storage
Task history, preferences, SAF permissions, and credit balance are stored strictly on-device via Room and DataStore.

### 4. Permissions
- `INTERNET` & `ACCESS_NETWORK_STATE`: Ad loading and anonymous diagnostics.
- `POST_NOTIFICATIONS`: Optional background task progress alerts.
- `FOREGROUND_SERVICE` & `FOREGROUND_SERVICE_DATA_SYNC`: Keeps large archive jobs running reliably in WorkManager.

---

## Versión en Español

### 1. Procesamiento Local de Archivos
ComicArch procesa tus archivos `.cbz`, `.cbr` e imágenes de forma **100% local en tu dispositivo** mediante **Storage Access Framework (SAF)**. Tus cómics nunca se suben a servidores externos.

### 2. Servicios de Terceros (AdMob y Firebase)
ComicArch no solicita cuentas de usuario. La app integra:
- **Google AdMob** (anuncios recompensados opcionales para recargar créditos) — puede recopilar el ID de publicidad, región aproximada por IP, datos del dispositivo e interacciones publicitarias.
- **Firebase Analytics** — recopila métricas anónimas de uso (pantallas visitadas, tipo de operación, idioma y postura de pantalla).
- **Firebase Crashlytics** — recopila trazas de error y versión de sistema/dispositivo para corregir fallos.

### 3. Almacenamiento Local
El historial de tareas, preferencias, URIs SAF y créditos se guardan únicamente en el dispositivo mediante Room y DataStore.

### 4. Permisos
- `INTERNET` y `ACCESS_NETWORK_STATE`: Carga de anuncios y diagnósticos anónimos.
- `POST_NOTIFICATIONS`: Avisos opcionales de progreso en segundo plano.
- `FOREGROUND_SERVICE` y `FOREGROUND_SERVICE_DATA_SYNC`: Ejecución fiable de tareas pesadas en WorkManager.
