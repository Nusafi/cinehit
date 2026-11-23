# CINEHIT

Juego de mesa cronológico de películas con tarjetas QR (inspirado en la mecánica de ordenar por año).

- **Jugar:** https://nusafi.github.io/cinehit/
- Cada tarjeta impresa lleva un QR a `?card=NNN`; la app abre el clip de YouTube sin mostrar el título.
- `index.html` es la app completa. `deck.json` es el mazo de 100 películas con su clip y tiempos.
- Si YouTube borra un clip: se cambia el enlace en el mazo y se vuelve a publicar. Las tarjetas impresas siguen sirviendo.
