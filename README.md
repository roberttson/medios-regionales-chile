# 📰 Medios Regionales Chile

Lista curada de medios de comunicación digitales chilenos, organizados por región. Cubre las 15 regiones del país con foco en medios locales e independientes.

> Proyecto construido en colaboración con la comunidad. Si conoces un medio que no está en la lista, abre un [Issue](../../issues) o envía un Pull Request.

---

## 🎯 Espíritu del proyecto

**Descentralizar la información.**

Chile tiene una concentración mediática cr*minal: la mayoría de los medios con mayor alcance están radicados en Santiago y cubren el país desde una sola perspectiva. Este proyecto nace para visibilizar los medios que informan desde los territorios, con una mirada local y propia.

Por eso este listado **no incluye**:
- Medios nacionales (El Mercurio, La Tercera, TVN, etc.)
- Medios digitales de alcance nacional (Desconcierto, El Mostrador, etc.)
- Medios comunales de la Región Metropolitana — que además prácticamente no existen, lo que dice mucho del centralismo

Lo que sí incluye: medios regionales, provinciales y comunales de las 15 regiones fuera de la RM, priorizando los más pequeños, locales e independientes.

---

## 📊 Estadísticas

| | |
|---|---|
| **Total medios** | 115 |
| **Regiones cubiertas** | 15 |
| **Región con más medios** | Araucanía (12) |
| **Región con menos medios** | Aysén (3) |

> El 47.5% de las comunas chilenas son desiertos informativos sin medios locales activos *(Fundación Gabo, 2024)*

---

## 🚀 Cómo usar esta lista

### Opción 1 — Importar OPML a tu lector RSS (recomendado)

El archivo `medios_chile.opml` contiene todos los medios listos para importar en cualquier lector RSS, organizados por carpetas por región.

**Inoreader** (gratuito hasta 150 feeds)
1. Crea una cuenta en [inoreader.com](https://inoreader.com)
2. Ve a **Preferencias → Contenido**
3. Busca la opción **Import OPML**
4. Sube el archivo `medios_chile.opml`

**Feedly** (gratuito hasta 100 feeds)
1. Crea una cuenta en [feedly.com](https://feedly.com)
2. Clic en tu nombre → **Import OPML**
3. Sube el archivo `medios_chile.opml`

**Miniflux** (open source, sin límites)
1. Instala Miniflux en tu servidor
2. Ve a **Settings → Import**
3. Sube el archivo `medios_chile.opml`

---

### Opción 2 — Usar el CSV directamente

El archivo `medios_final.csv` tiene la siguiente estructura:

```
nombre,region,url,categoria
El Morrocotudo,Arica y Parinacota,https://www.elmorrocotudo.cl,Regional
Diario El Longino,Tarapacá,https://diariolongino.cl,Regional
...
```

---

## 🗺️ Medios por región

| Región | Medios |
|--------|--------|
| Arica y Parinacota | 11 |
| Tarapacá | 7 |
| Antofagasta | 8 |
| Atacama | 8 |
| Coquimbo | 6 |
| Valparaíso | 9 |
| O'Higgins | 8 |
| Maule | 8 |
| Ñuble | 8 |
| Biobío | 7 |
| Araucanía | 12 |
| Los Ríos | 4 |
| Los Lagos | 10 |
| Aysén | 3 |
| Magallanes | 6 |

---

## 🤝 Cómo contribuir

### Agregar un medio
1. Haz fork del repositorio
2. Edita `medios_final.csv` agregando una línea:
   ```
   Nombre del medio,Región,https://url-del-medio.cl,Regional
   ```
3. Envía un Pull Request con una breve descripción del medio

### Reportar un medio caído
Abre un [Issue](../../issues) con el nombre del medio y la URL correcta si la conoces.

### Criterios para incluir un medio
- Cubre una región, provincia o comuna específica fuera de la RM
- Publica noticias de interés público local con regularidad
- No es un agregador de contenido nacional
- No pertenece a una cadena centralizada que replica el mismo contenido en múltiples dominios

---

## 📄 Licencia

Libre uso bajo licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Puedes usarlo, modificarlo y redistribuirlo citando la fuente.

---

*Última actualización: marzo 2026*
