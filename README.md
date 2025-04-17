# Ráérés Naptár – Backend

Ez az Express alapú API kapcsolatot biztosít a Google Sheets táblázathoz.

## Végpont

POST `/add-user`

Body:
```json
{
  "displayName": "Hegedűs Brúnó (PA)"
}
```

## Railway-re feltöltés után:

1. Add hozzá a környezeti változókhoz:
   - `GOOGLE_CREDENTIALS`: a JSON kulcsod escape-elve, egy sorban (mint Vercelben)

2. A frontend ezt az URL-t hívja majd:
   ```
   https://<projekted>.railway.app/add-user
   ```
