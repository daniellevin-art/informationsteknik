# Bilder i kursboken

## Egna illustrationer (SVG, färdiga)

| Fil | Används i |
|---|---|
| `it-tre-perspektiv.svg` | Kap 1, de tre perspektiven |
| `it-tidslinje.svg` | Kap 1, historik |
| `enhet-och-moln.svg` | Kap 1, mobilitet och moln |

Färger: turkos `#509dab`, mörk turkos `#2f6e7a`, orange `#e38812`, mörk orange (text) `#a85f05`.

## Foton att ladda ner (public domain)

Spara som angivet filnamn i `images/`:

| Spara som | Källa |
|---|---|
| `eniac.jpg` | https://commons.wikimedia.org/wiki/File:Eniac.jpg |
| `transistor.jpg` | https://commons.wikimedia.org/wiki/File:Replica-of-first-transistor.jpg |

Ange "U.S. Army Photo" vid ENIAC-bilden (står redan i kapitlet).

## Infoga en bild – snabbreferens

```markdown
![Bildtext som syns under bilden.](images/fil.svg){#fig-namn width="70%" fig-alt="Beskrivning för skärmläsare."}
```

Hänvisa i text med `@fig-namn` → blir "Figur 1.2".

Två bilder bredvid varandra, med ram (för foton):

```markdown
::: {layout-ncol=2 .foto}
![Text A](images/a.jpg){#fig-a}

![Text B](images/b.jpg){#fig-b}
:::
```

Liten bild i marginalen:

```markdown
![Text](images/fil.jpg){.column-margin}
```

Reflektionsruta (orange):

```markdown
::: {.reflektera}
Fråga till eleven …
:::
```
