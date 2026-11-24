# 💬 Busquem solucions (clima de classe)

Tutoria per millorar el clima de l'aula (parlar a tort i a dret, torn de paraula…). **Sense mòbils:** el profe projecta una pregunta cada vegada i els alumnes escriuen la resposta en un full, sense nom. Dues parts: primer **què passa** (autocrítica, perquè se n'adonin) i després **què ens ajudaria** (solucions i acord).

- `index.html`: portada, 10 preguntes d'una en una i una pantalla final de comiat (els alumnes lliuren el full al profe; no es posa en comú). Cada pregunta surt **parada** i el profe prem **▶ Play** (o Espai) per engegar el seu temporitzador (3 min); **no es pot passar a la següent fins que s'acaba** (sona un avís). **P** pausa, **S** salta la pregunta (sortida d'emergència del profe), **F** pantalla completa, ← torna enrere.
- `full.html`: full per imprimir amb les preguntes i espai per escriure.
- `preguntes.json`: preguntes i minuts (`min` general, o `min` dins d'una pregunta per canviar-lo només en aquella).
