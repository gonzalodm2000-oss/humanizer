# Humanizer: texto en español

Lee este archivo cuando el texto esté en español. Los patrones §1 a §26 de `SKILL.md` siguen valiendo, porque describen estructuras y no palabras. Aquí está lo que cambia en español: la forma que toma cada patrón, las palabras que delatan a un modelo en este idioma y los errores que vienen de pensar en inglés y traducir.

## Variante y tratamiento

Usa la variante del texto o de la muestra del usuario. Si no hay muestra y el texto es para Latinoamérica (por ejemplo, Perú), evita las formas peninsulares: vosotros, os, ordenador, móvil, coche, vale, coger, guay. Mantén un solo tratamiento, tú o usted, en todo el texto. Mezclarlos es un tell frecuente.

## Cómo aparece cada patrón en español

- **§1 No X sino Y:** no es solo X, es Y; no se trata de X, sino de Y; más que un X, es un Y; no es un mueble, es una declaración; la cola negativa ("…, sin complicaciones", "…, sin excusas").
- **§2 Cierres de una línea:** Y eso lo cambia todo. Así de simple. Punto. Ahí está la clave. Y no es casualidad. Hileras de fragmentos: "Sin límites. Sin excusas. Sin miedo."
- **§3 Frases que suenan profundas:** en el fondo, en esencia, la verdadera pregunta es, lo que realmente importa, el ADN de, el lenguaje de, X es el nuevo Y, no es un destino sino un viaje.
- **§4 Previa antes del punto:** Vamos al grano, Te lo cuento, Hablemos de, Sin más preámbulos, Ojo:, Spoiler:, Seamos sinceros, ¿La respuesta?, ¿Sabías que…? como apertura.
- **§5 Discutir con nadie:** No digo que…, Que quede claro, No me malinterpretes, Esto no significa que…
- **§7 Mismo inicio de frase:** el español omite el sujeto, así que una serie de frases que empiezan con "Ella", "Él", "Nosotros" o "Nuestro equipo" es un tell más fuerte que en inglés. Quita el pronombre: "Ofrecemos…", no "Nosotros ofrecemos…".
- **§8 Rayas:** la raya (—) es correcta en español para incisos y diálogos, pero un modelo la pone en cada párrafo. Aplica la regla de §8 a la prosa y conserva la raya de diálogo en narrativa.
- **§10 Guiones en compuestos:** no aplica. En español los compuestos casi nunca llevan guion.
- **§11 Pasiva:** el español prefiere la activa o la pasiva refleja: "La empresa anunció el cambio" o "Se anunció el cambio", no "El cambio fue anunciado por la empresa". Varias pasivas con "ser" seguidas son calco del inglés.
- **§15 Gerundio colgado:** "…, consolidándose como líder", "…, reflejando su compromiso con…", "…, permitiendo así…". Además de ser un tell, la RAE lo considera incorrecto cuando expresa una acción posterior. Divide la frase o usa un verbo conjugado.
- **§18 Evitar ser y tener:** se erige como, se posiciona como, se consolida como, funge como, constituye, brinda, posee, dispone de. "Cuenta con" es normal en fichas de producto o inmuebles; actúa solo si se repite. Usa es, son, tiene, hay.
- **§20 Títulos:** en español solo va en mayúscula la primera palabra y los nombres propios: "Cómo elegir un sofá", no "Cómo Elegir Un Sofá". Aquí no es *weak alone*: actúa a la primera. Meses y días van en minúscula.
- **§21 Comillas:** no cambies las comillas angulares («») ni las inglesas (“ ”); las dos son correctas en español. Unifica solo si el texto mezcla tipos.
- **§22 Restos de chatbot:** ¡Claro!, ¡Por supuesto!, ¡Excelente pregunta!, Aquí tienes…, Espero que te sea útil, No dudes en…, ¿Te gustaría que…?, Si necesitas algo más, avísame.
- **§23 Avisos sobre el límite del conocimiento:** según la información disponible, hasta la fecha de mi última actualización, no hay información pública sobre…, se cree que.

## Palabras típicas de IA en español (reemplaza la lista de §12)

Igual que en §12: son tells donde aparezcan, y pesan más cuando se juntan. Una palabra formal que no está aquí no es un tell por sí sola.

- **Aperturas:** en el dinámico (vertiginoso, cambiante, competitivo) mundo de; en la era digital; en el panorama actual; hoy más que nunca; en un mundo donde…
- **Conectores:** cabe destacar, cabe resaltar, es importante señalar, vale la pena mencionar, asimismo, sin lugar a dudas, sin duda alguna, en definitiva, en conclusión (al final de un texto corto), "Además," al inicio de cada párrafo.
- **Verbos:** potenciar, impulsar, optimizar, fomentar, adentrarse, sumergirse, navegar (figurado), desbloquear, elevar ("eleva tu espacio"), abrazar ("abrazar el cambio"), empoderar, aprovechar al máximo.
- **Adjetivos y sustantivos:** crucial, fundamental, clave como adjetivo ("un factor clave"), robusto, integral, holístico, transformador, vibrante, meticuloso, sinergia, ecosistema, panorama, un sinfín de, una amplia gama de, un testimonio de.
- **Frases hechas:** jugar un papel crucial (fundamental, clave), marcar la diferencia, llevar al siguiente nivel, dar un paso más allá.

## Lenguaje de venta (complementa §16)

En textos de producto, decoración, inmobiliaria o turismo: ubicado (enclavado) en el corazón de, un oasis de, una experiencia única, diseño excepcional, calidad inigualable, cuidadosamente seleccionado, pensado para ti, elegancia atemporal, donde el estilo se encuentra con la funcionalidad, piezas que cuentan una historia, transforma tu hogar, dale vida a tus espacios, déjate sorprender. Una o dos en un anuncio son normales; el tell es que cada frase sea una de estas. Di qué es la pieza, de qué está hecha, cuánto mide o cuánto cuesta, si la fuente lo dice. Si no lo dice, pídelo en vez de inventarlo.

## Calcos del inglés

Un modelo suele pensar en inglés y traducir. Busca:

- Pronombres de sujeto que el español omitiría (§7).
- Posesivos donde el español usa artículo: "levanta tu mano" en vez de "levanta la mano".
- Falsos amigos y calcos: hacer sentido, tomar lugar, jugar un rol, aplicar para un trabajo, eventualmente por "al final", remover por "quitar", asumir por "suponer", realizar por "darse cuenta", masivo por "enorme".
- Coma antes de "y" al final de una enumeración. El español no usa la coma de Oxford.
- Varios adjetivos antes del sustantivo: "una moderna, funcional y elegante cocina" en vez de "una cocina moderna y funcional".
- Falta el signo de apertura (¿ ¡) o el texto abusa de las exclamaciones.

## Ejemplo

**Antes:**
> En el dinámico mundo del diseño de interiores, cada espacio cuenta una historia. No se trata solo de muebles, se trata de crear experiencias. Nuestra nueva colección, cuidadosamente seleccionada, combina elegancia atemporal y funcionalidad, convirtiéndose en el aliado perfecto para transformar tu hogar. ¿El resultado? Espacios que inspiran. Así de simple.

**Después:**
> Presentamos nuestra nueva colección: muebles para la casa pensados para verse bien y aguantar el uso diario.

El original no da materiales, medidas ni precios, así que la versión final no los inventa. Si el usuario los tiene, pídeselos: con ellos el texto puede ser más concreto que cualquier adjetivo.
