# Bloco-de-nota
bloco de notas

REGRAS DO FIREBASE

service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write: if true;
    }
  }
}
