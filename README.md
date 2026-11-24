# 💬 Clima de classe

Tutoria per millorar el clima de l'aula (parlar a tort i a dret, no respectar el torn de paraula…). Els alumnes **escriuen** des del mòbil, de manera anònima, i el profe revisa les respostes abans de projectar-les.

## Obrir

- **Portada (`index.html`):** «Alumnes, entreu aquí» (gran) i «Sóc el profe» (petit).
- **Profe:** `profe.html`. **Alumnes:** `movil.html`.
- **Moodle (codi fix):** el profe obre `?codi=1234` i a Moodle es posa `?c=1234`.
- **Previsualitzar:** `?demo` (profe, amb 24 alumnes simulats).

## Flux

1. **Sala oberta:** els alumnes escriuen, una pregunta per pantalla (màx. 240 caràcters). Es poden saltar preguntes.
2. **Revisar respostes (només el profe, no projectar):** surten totes, barrejades. Toca una resposta per **amagar-la** (noms de companys, insults, coses que identifiquin algú). Les amagades no es projecten.
3. **Projectar:** una diapositiva per pregunta amb les respostes (12 per diapositiva). Espai o → avança, ← torna.
4. **Final:** preguntes per decidir acords, i CSV amb les respostes projectades (sense cap identificador).

## Privacitat

- No es desa res enlloc (Supabase Realtime només fa broadcast). En tancar la sala, tot desapareix.
- Cap resposta porta nom ni identificador; es barregen abans de revisar-les.
- El profe filtra abans que res surti a la pantalla.

## Preguntes

A `preguntes.json`, tipus `text`. Hi ha 10: soroll, torn de paraula, clima, moments difícils, què molesta, autocrítica, què costa callar, sentir-se escoltat, paper del professorat i un acord concret.
