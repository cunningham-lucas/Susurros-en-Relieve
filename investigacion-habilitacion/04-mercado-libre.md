# 04 · Mercado Libre con Tiendanube

**Investigación:** 03/11/2026. **Tipo de cambio de trabajo:** USD 1 = ARS 1.650 → precio de referencia **$82.500**.
Mercado Pago en la tienda propia (comisiones, plazos, configuración, cuenta aparte) está en el **05c**.

---

## 1. Qué es y por qué importa para [MARCA]
Mercado Libre es el marketplace donde busca la mayoría de los compradores en Argentina. Vender ahí te da tráfico que tu tienda nueva no tiene, a cambio de:
- comisiones más altas;
- envío gratis obligatorio desde cierto precio;
- reglas de la plataforma;
- una ficha donde **no podés poner un personalizador**.

Para un producto personalizado eso último es el punto crítico.

## 2. Cómo funciona hoy

### 2.1 Integración con Tiendanube
- **No hay integración nativa de Tiendanube con Mercado Libre.** La ayuda de Tiendanube remite a apps de terceros. Fuente: [Cómo vincular Mercado Libre](https://ayuda.tiendanube.com/es_AR/canales-de-ventas/como-vincular-mi-cuenta-de-mercado-libre-con-mi-tienda), actualizada el 25/09/2026.

| App | Qué sincroniza | Precio | Calificación |
|---|---|---|---|
| [Astroselling](https://www.tiendanube.com/tienda-aplicaciones-nube/astroselling) | Publica productos de Tiendanube en Mercado Libre de forma masiva, vincula publicaciones existentes, sincroniza **stock y/o precio** "en menos de 60 segundos", con markup | 7 días gratis; precio **[No verificado]** | 4,2 (166) |
| Grow2on | Stock y precio en masa; centraliza publicaciones, ventas, facturación y envíos | **[No verificado]** | — |
| VentiApp | Inventario, publicación masiva, órdenes | **[No verificado]** | — |
| EcomNube | Vincula por **SKU**; las ventas de Mercado Libre bajan el stock en Tiendanube; **no publica de Tiendanube a Mercado Libre** ([ayuda](https://ayuda.tiendanube.com/123518-aplicaciones-de-canales-de-venta/como-integrar-ecomnube-a-mi-tienda)) | **[No verificado]** | — |
| Ecomm-App, Contabilium | Stock y precio si ya publicaste en los dos lados | **[No verificado]** | — |

- **Qué no sincroniza (en general):**
  - **el texto de personalización**, porque Mercado Libre no tiene campos del comprador;
  - las fotos de la vista previa;
  - las reseñas.
  - **[No verificado]** Si las órdenes de Mercado Libre bajan como órdenes a Tiendanube: depende de la app.
- **Para [MARCA] el stock es "infinito"** (hecho a pedido), así que la sincronización de stock importa poco. Importa el **precio** (con markup por la comisión) y **centralizar los pedidos**.

### 2.2 Requisitos de cuenta y reputación
- Cuenta de Mercado Libre con tus datos y **datos fiscales** (CUIT y condición frente al IVA) cargados en "Información fiscal". Mercado Libre aplica impuestos según tu condición y tus inscripciones por provincia. Fuente: [Costos por vender](https://www.mercadolibre.com.ar/ayuda/costos-vender-producto_870), consultada el 03/11/2026.
- **Reputación:** arrancás **sin reputación**. Los costos de envío gratis tienen descuento para "MercadoLíderes, reputación verde **o sin reputación**". Si la reputación cae a amarilla, naranja o roja, el envío te sale más caro. Fuente: [Costos de ofrecer envíos gratis](https://www.mercadolibre.com.ar/ayuda/envios-gratis_3482).
- La reputación baja por:
  - **demoras en despachar** (crítico en un producto a pedido);
  - cancelaciones;
  - reclamos.
- **[No verificado]** Límites de publicaciones o ventas para cuentas nuevas.

### 2.3 Comisiones (fuente oficial, consultada el 03/11/2026)
Fuente: [Mercado Libre, Costos por vender un producto y opciones de cuotas](https://www.mercadolibre.com.ar/ayuda/costos-vender-producto_870).

- **Cargo por vender:** **entre 11,62 % y 17,75 %** del precio, según **categoría y provincia** (por Ingresos Brutos).
- **Costo por unidad vendida:** **solo en productos de menos de $33.000**. Con colecta, correo o puntos de despacho depende del precio, el peso y las medidas. Con Flex o acuerdo con el comprador: $1.330 / $2.740 / $3.320 según tramo. **A $82.500 no aplica.**
- **Costo por ofrecer cuotas** (se suma al cargo por vender):
  - *Cuotas con interés bajo (3 a 12):* **5 %**.
  - *Cuotas al mismo precio:* 3 cuotas **8,50 %**, 6 cuotas **12,90 %**, 9 cuotas **17,30 %**, 12 cuotas **20,80 %**.
  - *Sin cuotas:* solo el cargo por vender.
- **"Clásica" y "Premium":** la página oficial vigente ya no usa esos nombres. Estructura el costo como **cargo por vender + opción de cuotas**. Lo que antes era "Premium" equivale a publicar con cuotas sin interés, pagando el costo de cuotas. **[No verificado]** Si el panel de vendedor sigue mostrando los nombres viejos.
- **Precio mínimo:** $1.000.
- **Prueba limitada gratis:** hasta 5 ventas de productos nuevos en el último año, hasta 10 publicaciones, stock 1, 60 días, baja exposición.
- **[No verificado]** El porcentaje exacto de la categoría donde caería un embosador (probablemente "Arte, Librería y Mercería" o "Hogar"). Lo ves al crear la publicación en el simulador.
- **[No verificado]** Si los porcentajes incluyen IVA: las fuentes de terceros se contradicen.

**Ejemplo con un pedido de $82.500, sin cuotas y con un cargo hipotético del 14 %:**
- $11.550 de cargo;
- **+ el costo del envío gratis** (desconocido sin peso);
- + retenciones según tu condición.

Con 6 cuotas al mismo precio, sumá 12,90 % ($10.643).

### 2.4 Mercado Envíos
- **Envío gratis obligatorio desde $33.000** según fuentes de septiembre de 2026, por ejemplo [Algoritmo Digital](https://algoritmodigital.com.ar/?p=4171). Otra nota informa que para suscriptores Meli+ el piso bajó a $15.000 ([Noticias NQN, 10/09/2026](https://www.noticiasnqn.com.ar/noticias/2026/09/10/352025-mercado-libre-cambia-una-de-sus-condiciones-y-desde-el-lunes-habra-envios-gratis-desde-15000)). **[No verificado en fuente oficial.]** **A $82.500 vas a tener que ofrecer envío gratis**, y lo pagás vos con descuento.
- **Costo del envío gratis:** depende del **mayor entre el peso físico y el volumétrico** del paquete embalado y de tu **reputación**. Mercado Libre mide el paquete al despachar y ajusta el costo de las ventas siguientes. Fuente: [Costos de ofrecer envíos gratis](https://www.mercadolibre.com.ar/ayuda/envios-gratis_3482).
- **Logísticas** (mencionadas en la página de costos): **colecta** (te retiran), **puntos de despacho / correo** (llevás vos), **Flex** (entregás vos o tu mensajería en tu zona), **Full** (stock en depósitos de Mercado Libre; **no sirve para un producto a pedido**).
- **Flujo:** la venta entra → Mercado Libre genera la etiqueta → la imprimís desde Mercado Libre → despachás → el seguimiento lo maneja Mercado Libre.
  - **Plazo de despacho:** al ser a pedido, configurá **días de disponibilidad** ("producto a pedido" o "disponible en N días"). **[No verificado]** El máximo permitido y su efecto en la exposición.

### 2.5 Producto personalizado en Mercado Libre
- **¿Se puede?** Sí: hay tiendas activas de "artículos personalizados" ([ejemplo](https://www.mercadolibre.com.ar/tienda/dm-pins)). **[No verificado]** No encontré una página de ayuda oficial vigente sobre productos personalizados (el link conocido devolvió "no encontramos esta sección").
- **Cómo lo resuelven otros vendedores** (práctica observada, no norma):
  1. **Diseño y color como variantes** de la publicación.
  2. **El texto se pide por mensajería posventa:** en la descripción y en el título de la ficha dicen "Después de comprar, envianos por mensaje el nombre a grabar (hasta 20 caracteres)". Algunos piden confirmar antes por preguntas.
  3. **Vista previa:** se manda como imagen por la mensajería para que el comprador confirme antes de fabricar.
  4. **Plazo:** publicación con días de disponibilidad que cubran la producción.
- **Riesgos:**
  - compradores que no responden y la venta queda frenada;
  - demoras que bajan la reputación;
  - errores de tipeo sin confirmación escrita;
  - no se puede dirigir al comprador a otro canal (WhatsApp o la tienda propia) **[No verificado]**: regla habitual de Mercado Libre, ver sus políticas.
- **Devoluciones:** **[No verificado]** Si la política de devoluciones de Mercado Libre (devolución gratis) exceptúa los productos personalizados. **Es la pregunta clave para soporte de Mercado Libre** antes de publicar.

### 2.6 Facturación y declaración
- Facturás vos cada venta de Mercado Libre (Factura C) y **suma a tu facturación del monotributo** (06).
- Mercado Libre retiene o percibe impuestos según tu información fiscal (05b).

## 3. Qué aplica concretamente a [MARCA]

### 3.1 ¿Los dos canales desde el arranque o primero la tienda propia?

**Postura A: primero la tienda propia (recomendada para [MARCA])**
- El producto **depende del personalizador con vista previa**, que en Mercado Libre no existe. La experiencia en Mercado Libre es peor y genera más errores.
- El margen en Mercado Libre se come entre el 12 % y el 18 % de cargo, más el envío gratis, más las cuotas si las ofrecés. En la tienda propia la comisión de cobro es de 1 % a 7 % (05c).
- Un producto a pedido con plazo de producción **arriesga la reputación** desde la primera venta. En la tienda propia nadie te baja la exposición por demorar.
- La operación inicial (fabricante, envíos, facturación) conviene probarla con un solo canal.
- La marca y la base de clientes (emails, reseñas) quedan en tu tienda.

**Postura B: los dos desde el arranque**
- Mercado Libre trae **tráfico y confianza** que una tienda nueva sin reseñas no tiene. El comprador confía en la Compra Protegida de Mercado Libre.
- Las primeras ventas y reseñas pueden venir de ahí y validar demanda antes de invertir en publicidad.
- Con stock infinito, la sincronización es simple: una app solo para el precio.
- Sirve como **termómetro de precio** frente a competidores que ya venden embosadores.

**Recomendación:**
- Arrancar con la **tienda propia**.
- Abrir Mercado Libre **cuando estén resueltos**:
  - el plazo de producción real y estable;
  - la respuesta de Mercado Libre sobre devoluciones de personalizados;
  - el flujo de pedir el texto por mensajería con una plantilla;
  - un precio en Mercado Libre que cubra el cargo y el envío.
- Mientras tanto, se puede usar la **prueba limitada gratis** (hasta 5 ventas) para validar sin costo de cargo.

### 3.2 Qué decisiones dependen de qué dato
| Decisión | Dato | Quién lo da |
|---|---|---|
| Precio en Mercado Libre | Costo puesto, peso y medidas (para el envío gratis), categoría | Fabricante + simulador de Mercado Libre |
| Si se puede vender personalizado | Política de devoluciones y de mensajería | Soporte de Mercado Libre |
| Días de disponibilidad | Plazo de producción | Fabricante |
| App de sincronización | Si hace falta bajar las órdenes a Tiendanube | Vos |

## 4. Lo que tenés que hacer vos a mano
- Crear o validar la cuenta de vendedor en Mercado Libre: identidad, datos fiscales y cuenta de Mercado Pago.
- Decidir precio, cuotas y logística.
- Contestar cada venta con la plantilla de pedido de texto y confirmar la vista previa.
- Despachar dentro del plazo.
- Facturar cada venta.
- Contratar y pagar la app de sincronización si la usás.

## 5. Prompt para Claude Code Web

```
Leé investigacion-habilitacion/04-mercado-libre.md y 05c-cobros-banco-mercado-pago.md del repo
cunningham-lucas/Susurros-en-Relieve.
Tareas:
1. Armá una calculadora (Markdown + CSV) de precio en Mercado Libre: costo puesto, costo de envío gratis
   (celda a completar con el simulador de ML), cargo por vender (celda: % de la categoría), opción de cuotas
   (0 %, 5 %, 8,5 %, 12,9 %), retenciones estimadas (celda) → precio mínimo para igualar el margen de la
   tienda propia.
2. Redactá la plantilla de publicación: título (60 caracteres), variantes Diseño × Color, descripción que
   explique que el texto se envía por mensaje después de la compra y se confirma con vista previa, plazo de
   producción, garantía legal 6 meses, sin derecho de arrepentimiento por ser personalizado (art. 1116 CCyC)
   [a validar con ML y con el abogado].
3. Redactá los mensajes posventa: (a) pedido del texto, (b) envío de vista previa para confirmar,
   (c) aviso de despacho.
4. Verificá en el centro de ayuda de Mercado Libre la política vigente de devoluciones para productos
   personalizados y el umbral de envío gratis; citá enlace y fecha o marcá [No verificado].
No publiques nada en Mercado Libre. Commit en la rama de trabajo.
```

## 6. Paso a paso (cuando decidas abrir Mercado Libre)

| # | Paso | Quién | Demora |
|---|---|---|---|
| 1 | Preguntar a soporte de Mercado Libre por devoluciones de personalizados y mensajería | Vos | 1 a 3 días |
| 2 | Cuenta de vendedor: identidad, datos fiscales, Mercado Pago | Vos | 1 día |
| 3 | Simular una publicación para ver el % de la categoría y el costo del envío gratis con el peso real | Vos | 30 min |
| 4 | Calculadora de precio | Claude | 1 h |
| 5 | Plantilla de publicación y mensajes posventa | Claude | 1 h |
| 6 | Publicar 1 o 2 productos con la prueba limitada gratis | Vos | 1 h |
| 7 | Operar 5 ventas: pedir el texto, confirmar la vista previa, despachar en plazo, facturar | Vos | Por venta |
| 8 | Si funciona: publicación normal y app de sincronización (Astroselling u otra, en período de prueba) | Vos | 1 a 2 h |

## 7. [No verificado] y preguntas
**[No verificado]**
- La política oficial vigente de Mercado Libre sobre personalizados y devoluciones.
- El umbral oficial de envío gratis.
- Si los cargos incluyen IVA.
- El % de la categoría.
- Los límites de cuentas nuevas.
- Los precios de las apps de sincronización.
- Si las órdenes de Mercado Libre bajan a Tiendanube.

**Preguntas para soporte de Mercado Libre**
1. ¿Puedo vender un producto personalizado pidiendo el texto por mensajería después de la compra? ¿Hay alguna herramienta para que el comprador lo cargue al comprar?
2. ¿Los productos personalizados tienen devolución gratis obligatoria o están exceptuados?
3. ¿Cuántos días de disponibilidad puedo poner para un producto hecho a pedido? ¿Afecta la exposición?
4. ¿En qué categoría y con qué cargo publico un sello seco o embosador para libros?
5. ¿El cargo por vender incluye IVA?

**Preguntas para soporte de Tiendanube**
1. ¿Hay planes de una integración nativa con Mercado Libre?
2. ¿Qué app recomiendan para traer las órdenes de Mercado Libre a Tiendanube?

**Pregunta para el contador**
1. ¿Qué retenciones me hace Mercado Libre como monotributista de PBA y cómo las computo?
