# Složenka → QR platba

Vyfotíš složenku, aplikace přečte QR Platbu (nebo text pomocí OCR), zkontroluje číslo účtu a vytvoří QR Platbu, kterou můžeš sdílet nebo uložit.

Celá aplikace je jeden soubor `index.html` (jsQR, qrcode-generator a Tesseract.js se načítají z jsDelivr).

## Na iPhonu
Otevři v Safari adresu stránky, pak Sdílet → Přidat na plochu. Kamera vyžaduje HTTPS.

## Omezení
- OCR se může splést, hlavně u částky a symbolů. Údaje vždy porovnej s papírem.
- Bez service workeru, vyžaduje internet.
