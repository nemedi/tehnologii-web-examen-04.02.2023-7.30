# Tematica: REST

# Dată fiind aplicația `app` completați metodele `PUT` si `DELETE` la adresa `/ships/id`:
- Daca se incerca modificarea unei nave inexistente raspunsul trebuie sa fie `{"message": "not found"}`. Codul de raspuns va fi: `404`;
- Daca se incearca modificarea unei nave existente raspunsul trebuie sa fie `{"message": "accepted"}`. Codul de raspuns va fi: `202`;
- O cerere get ulterioara la adresa navei editate trebuie sa reflecte modificarile. Codul de raspuns va fi: `200`;
- Daca se incearca stergerea unei nave existente raspunsul trebuie sa fie `{"message": "accepted"}`. Codul de raspuns va fi: `202`;
- O cerere get ulterioara la adresa navei sterse trebuie sa returneze `{"message": "not found"}`. Codul de raspuns va fi: `404`;

# Instructiuni

# Obiectiv : Modificati `app.js` in locul marcat pentru a satiface testele

# Pasi pentru a rula testele
1. Instalati dependentele ruland `npm i`
2. Testati aplicatia ruland `npm test`