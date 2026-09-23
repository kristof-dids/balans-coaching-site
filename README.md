# Balans Coaching — zelfstandige website

Responsieve, statische website zonder Webflow-afhankelijkheid. Alle pagina’s en beelden staan in deze map. De relatieve links werken zowel op een GitHub Pages-project-URL als op het eigen domein. Publiceer de inhoud van deze map vanuit de hoofdmap van een aparte repository.

## Voor publicatie

1. Controleer alle teksten, tarieven en beschikbaarheden met Sandy Stevens. Deze zijn gebaseerd op de openbare website van 23 september 2026.
2. Controleer de gebruiksrechten van logo’s en foto’s. De huidige site gebruikte deze bestanden; de rechten zijn niet onafhankelijk geverifieerd.
3. Laat de privacyverklaring juridisch en operationeel nalopen. Een verouderde verwijzing naar "Praktijk Oosterveld" is uit de overgenomen tekst verwijderd.
4. Test de QIT-aanmeldlink. De oude Webflow-formulierverwerking is vervangen door de bestaande QIT-route, zodat klachtgegevens niet via een onbeveiligd statisch formulier worden verzonden.
5. Koppel domein, DNS en HTTPS pas na goedkeuring van de preview.

## Lokaal bekijken

```sh
python3 -m http.server 8080 -d .
```

Open daarna `http://localhost:8080/`.
