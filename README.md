# Chatbot AI - HTML with Javascript

### Penting: 
Chatbot kamu tidak akan dapat menghasilkan respons sampai kamu mengonfigurasinya dengan apikey Gemini. Untuk melakukan ini, cukup tambahkan apikey kamu ke variabel API_KEY di file ```script.js```. Anda bisa mendapatkan apikey gratis dari [Gemini Studio](https://aistudio.google.com/app/apikey). Apikey akan terlihat seperti ini: AIzaSyAtpnKGX14bTgmx0l_gQeatYvdWvY_wOTQ. Cukup buka file ```index.html``` di browser / website kamu.

### Script.js
```
const API_KEY = "PASTE-YOUR-API-KEY";
const API_URL = `https://generativelanguage.googleapis.com/v1/models/gemini-1.5-flash:generateContent?key=${API_KEY}`;
```
