# 06 · Facturación

**Investigación:** 03/11/2026. **Tipo de cambio de trabajo:** USD 1 = ARS 1.650 → pedido de **$82.500**.

> No soy contador. Confirmá con el contador el momento de emisión y el tratamiento de las ventas por Mercado Libre.

---

## 1. Qué es y por qué importa para [MARCA]
Cada venta tiene que tener su comprobante electrónico autorizado por ARCA, con un CAE (código de autorización). Para [MARCA] importa por cuatro razones:
1. **No facturar es causal de exclusión del monotributo** ([ARCA, Exclusión](https://www.arca.gob.ar/monotributo/ayuda/exclusion.asp)).
2. La suma de lo facturado define tu categoría (05a).
3. Lo que cobrás por Pago Nube, Mercado Pago y bancos tiene que coincidir con lo facturado.
4. Con volumen, facturar a mano se vuelve un trabajo diario.

## 2. Cómo funciona en Argentina hoy

### 2.1 Qué comprobante
- Monotributista → **Factura C**, que no discrimina IVA. Para devoluciones y anulaciones, **Nota de Crédito C**.
- A consumidor final:
  - Solo es obligatorio identificar al comprador (DNI, CUIL o CDI) si la operación es de **$10.000.000 o más** (RG 5700/2025). Fuente: [Contadores en Red, 20/01/2026](https://contadoresenred.com/facturacion-a-partir-de-que-monto-se-debe-identificar-al-consumidor-final-en-2026/).
  - Por debajo de ese monto, nombre y domicilio se pueden completar con "NR" o ceros. Fuente: [Perfil, 19/08/2026, sobre la RG 5866/2026](https://www.perfil.com/noticias/economia/factura-electronica-arca-que-cambia-cuando-debe-emitirse-y-cuales-son-los-nuevos-requisitos-a40.phtml).
  - Un pedido de $82.500 no exige identificar al cliente. **Igual conviene poner nombre y email**: hace falta para mandarle la factura y sostener un reclamo o una devolución.
- **Puntos de venta:** desde el 01/11/2026 (RG 5893/2026), los monotributistas sin punto de venta reciben uno de oficio en "Comprobantes en línea" como **"Factura en línea – Monotributo"**. Fuente: [ARCA, novedad del 31/08/2026](https://servicioscf.afip.gob.ar/publico/sitio/contenido/novedad/ver.aspx?id=5881). Si usás una app de facturación, en general necesitás **otro punto de venta tipo "Web Service"**. Para administrar puntos de venta hace falta clave fiscal nivel 3 (RG 5866/2026, según Perfil).

### 2.2 Cuándo se emite
- **[No verificado]** La regla general para venta de bienes es emitir el comprobante **al momento de la entrega del bien o acto equivalente**. La nota de Perfil sobre la RG 5866/2026 menciona "el último día del mes" en que se produjo la entrega, pero en un contexto de liquidaciones mensuales y no queda claro que aplique a ventas comunes.
- **Práctica prudente mientras el contador no diga otra cosa:** emitir la factura **cuando se confirma el pago**, y nunca después del despacho.

### 2.3 Cómo se emite: opciones

| Opción | Costo | Ventajas | Desventajas |
|---|---|---|---|
| **Comprobantes en línea** (web de ARCA, con clave fiscal) | Gratis | Oficial, sin terceros | Manual: 2 a 3 minutos por factura; hay que mandar el PDF al cliente a mano |
| **Facturador** (app de ARCA para celular o web) | Gratis | Rápido desde el celular | Manual; no se puede usar por encima de $500.000 por comprobante ([Contadores en Red](https://contadoresenred.com/facturacion-a-partir-de-que-monto-se-debe-identificar-al-consumidor-final-en-2026/)) |
| **App integrada a Tiendanube** | Abono mensual | Factura sola cada venta pagada y manda el PDF por email | Costo; depende de que la integración ande; **compatibilidad con Pago Nube** (abajo) |

### 2.4 Apps de facturación en Tiendanube
Según la [ayuda de Tiendanube](https://ayuda.tiendanube.com/es_AR/123288-mis-ventas/como-facturar-las-ventas-de-mi-tiendanube), actualizada el 09/10/2026:
- La facturación se hace **fuera** de Tiendanube.
- **Con Pago Nube, la facturación automática hoy solo funciona con Facturante.** Con las otras apps, las ventas cobradas con Pago Nube se facturan a mano.
- Apps listadas: Facturante, iFactura, Contagram, Contabilium, Xubio, Ecomm-App, Netegia, Nymeria, Tango Factura, Ecomgestión. Las primeras cuatro mandan la factura al cliente al concretarse la compra.

| App | Precio | Calificación en Tiendanube | Notas |
|---|---|---|---|
| [Facturante](https://www.tiendanube.com/tienda-aplicaciones-nube/facturante) | **[No verificado]**: la ficha no muestra el precio y la página de precios devolvió 404 | 3,8/5 (85 reseñas: 56 de 5★ y 23 de 1★) | La única automática con Pago Nube. Notas de crédito, envío por email con logo. Quejas por fallas de integración y soporte lento |
| [Factura Simple](https://www.tiendanube.com/tienda-aplicaciones-nube/facturasimple) | $19.900/mes, sin límite de comprobantes, 15 días gratis | 5,0 (1 reseña) | Factura por webhook al pagarse, notas de crédito automáticas, aviso de tope de monotributo, también factura Mercado Libre. Pide certificado de ARCA. No menciona Pago Nube |
| [Factureo](https://www.tiendanube.com/tienda-aplicaciones-nube/factureo) | Plan único, 30 días gratis; precio en factureo.pro **[No verificado]** | Sin reseñas | Factura C automática, PDF al cliente, notas de crédito automáticas, no pide clave fiscal (delegación). App nueva, de un emprendedor |
| iFactura, Contabilium, Xubio y otras | **[No verificado]** | — | Revisar ficha por ficha |

Fichas consultadas el 03/11/2026.

**¿A partir de qué volumen deja de tener sentido facturar a mano?**
- A 2 o 3 minutos por factura, **10 pedidos por mes** son unos 30 minutos por mes: se hace a mano sin problema.
- **30 pedidos** son 1,5 horas por mes: todavía manejable, pero es donde empieza a valer una app.
- **100 pedidos** son 5 horas por mes y con errores: **automatizar**.
- Corte práctico: **más de 30 o 40 pedidos por mes**, o el día que te olvides una factura.

### 2.5 Notas de crédito
- Se emiten para **anular total o parcialmente una factura**:
  - devolución por arrepentimiento (si aplica, ver 01);
  - devolución por la garantía de 90 días de la marca;
  - descuento posterior;
  - error en la factura.
- **Cambio por otro producto del mismo precio:** **[No verificado]** No hace falta nota de crédito si no cambia el importe. Si cambia, nota de crédito por la diferencia o factura nueva. Confirmalo con el contador.
- Se emiten desde el mismo sistema que la factura (Comprobantes en línea, Facturador o la app), **asociadas a la factura original**.

### 2.6 Qué guardar y cuánto tiempo
- Comprobantes emitidos y recibidos, resúmenes de Pago Nube, Mercado Pago y banco, órdenes de Tiendanube, etiquetas de envío y comunicaciones de devoluciones.
- **Plazo:** **[No verificado]** La regla general de conservación de documentación tributaria es **10 años** (por la prescripción de la Ley 11.683 y la conservación del Código Civil y Comercial). El contador te dice el plazo exacto. Recomendado: carpeta digital por año y por mes, con backup.

### 2.7 Mercado Libre
- **Facturás vos**, con tu CUIT, cada venta. Mercado Libre retiene o percibe impuestos según tu condición, pero la obligación de emitir el comprobante es del vendedor. Fuente: [Base.com, blog](https://base.com/es-AR/blog/?p=18427).
- Las ventas de Mercado Libre **suman a tu facturación** del monotributo igual que las de la tienda.
- **[No verificado]** Mercado Libre tuvo un facturador integrado para monotributistas. No pude confirmarlo: la página de ayuda devolvió "no encontramos esta sección". Factura Simple dice facturar también las ventas de Mercado Libre.

### 2.8 Qué le mandás al cliente y cuándo

| Comunicación | Obligatorio | Cuándo | Cómo |
|---|---|---|---|
| Confirmación del pedido con detalle, precio y condiciones | **Recomendado.** La información clara y detallada es obligatoria (art. 4 de la Ley 24.240) | Al comprar | Email automático de Tiendanube |
| Factura C | **Obligatorio emitirla**. **[No verificado]** si es obligatorio enviarla; en la práctica se manda | Al confirmarse el pago o al despachar | PDF por email (manual o app) |
| Aviso del derecho de arrepentimiento o de su excepción | Obligatorio informarlo (art. 1111 del CCyC; ver 01) | Antes de la compra y en la confirmación | Checkout, ficha y email |
| Código de identificación ante un pedido de arrepentimiento | **Obligatorio, dentro de 24 h** (Disposición 954/2025, art. 5) | Cuando el cliente lo pide | Por el mismo medio |
| Seguimiento del envío | Buena práctica | Al despachar | Email "Confirmación de envío" de Tiendanube (automático con Envío Nube o MiCorreo) |

### 2.9 Qué datos del cliente pedir
- **Para facturar a consumidor final por menos de $10 millones:** ninguno obligatorio. Recomendado: nombre, email y DNI opcional. Tiendanube ya pide nombre, email y dirección para el envío.
- **Si el cliente quiere factura a nombre de una empresa** (embosador con logo): CUIT y razón social. Al ser monotributista igual emitís Factura C.
  - **[No verificado]** Si Tiendanube permite activar "pedir DNI/CUIT" en el checkout: revisá Configuración > Opciones del checkout.
  - Las apps de facturación toman esos datos de la orden.

## 3. Qué aplica concretamente a [MARCA]
- **Arranque (10 a 30 pedidos por mes):**
  - Factura C a mano desde el **Facturador** o Comprobantes en línea, el mismo día del pago.
  - PDF al cliente por email.
  - Planilla mensual que cruce órdenes de Tiendanube, facturas y cobros de Pago Nube.
- **Al pasar de unos 30 a 40 pedidos por mes:**
  - si seguís con Pago Nube, **Facturante**;
  - si sumás Mercado Pago, cualquiera de las otras apps.
  - Probar en el período gratis antes de pagar.
- **Mercado Libre:** si lo sumás, elegí una app que facture las dos fuentes, o facturá Mercado Libre aparte.
- **Productos "Garantía de por vida" y "Gift Card":** son ventas sin envío.
  - La garantía se factura como cualquier venta.
  - **[No verificado]** La **gift card**: cuándo se factura, al venderla o al canjearla. Preguntalo al contador.

## 4. Lo que tenés que hacer vos a mano
- Tener clave fiscal nivel 3 y revisar tus puntos de venta en ARCA.
- Crear un punto de venta "Web Service" si usás una app. Generar y subir el certificado o hacer la delegación que pida la app.
- Emitir cada factura y nota de crédito mientras no automatices.
- Contratar y pagar la app de facturación cuando la uses.
- Guardar la documentación.

## 5. Prompt para Claude Code Web

```
Leé investigacion-habilitacion/06-facturacion.md del repo cunningham-lucas/Susurros-en-Relieve.
Tareas:
1. Verificá precios y compatibilidad con Pago Nube de Facturante, Factura Simple, Factureo, iFactura y
   Contabilium en sus fichas de la Tienda de Aplicaciones de Tiendanube y en sus webs. Actualizá la tabla 2.4
   con fecha.
2. Con el conector de Tiendanube (solo lectura), listá las órdenes pagadas del mes y generá un CSV
   "a-facturar.csv" con: número de orden, fecha de pago, nombre, email, total, medio de pago y estado de
   envío, para facturar a mano en el Facturador de ARCA.
3. Redactá en Markdown la plantilla del email que acompaña la factura (asunto, cuerpo breve, datos de
   contacto) y la del email de nota de crédito por devolución.
No emitas comprobantes ni cambies nada en la tienda. Commit en la rama de trabajo.
```

## 6. Paso a paso

| # | Paso | Quién | Demora |
|---|---|---|---|
| 1 | Revisar en ARCA los puntos de venta (debería estar "Factura en línea – Monotributo") | Vos | 15 min |
| 2 | Hacer una factura C de prueba por $1 a vos mismo **[No verificado]** si conviene; mejor practicar con la primera venta real | Vos | 10 min |
| 3 | Definir con el contador el momento de emisión y el tratamiento de la gift card | Contador | En la consulta |
| 4 | Plantillas de email de factura y nota de crédito | Claude | 30 min |
| 5 | Planilla mensual de conciliación (órdenes, facturas, cobros) | Claude | 1 h |
| 6 | Al llegar a 30 o 40 pedidos por mes: prueba gratis de Facturante (o la app que corresponda), punto de venta Web Service y vinculación | Vos | 1 a 2 h |
| 7 | Revisar cada mes que todas las órdenes pagadas tengan factura | Vos | 10 min |

## 7. [No verificado] y preguntas
**[No verificado]**
- El momento exacto de emisión según la RG vigente.
- El plazo de conservación (10 años).
- El precio de Facturante.
- El facturador de Mercado Libre.
- La facturación de gift cards.
- Si el checkout de Tiendanube pide DNI o CUIT.

**Preguntas para el contador**
1. ¿En qué momento emito la factura en una venta online a pedido: al cobrar, al despachar o al entregar?
2. La gift card, ¿se factura al venderla o al canjearla?
3. En un cambio de producto, ¿emito nota de crédito y factura nueva o nada?
4. ¿Cuánto tiempo tengo que guardar comprobantes y resúmenes?
5. Las ventas de Mercado Libre, ¿las facturo una por una o hay alguna forma consolidada?

**Preguntas para soporte de Tiendanube**
1. ¿Facturante sigue siendo la única app que factura automáticamente las ventas cobradas con Pago Nube?
2. ¿Puedo pedir DNI o CUIT opcional en el checkout?
