# 02 · Logística y envíos: manual operativo por servicio

**Investigación:** 03/11/2026.
**Estado de la tienda (conector de Tiendanube, 03/11/2026):**
- **no hay ningún medio de envío configurado**;
- **todos los productos tienen peso 0 y medidas 0 × 0 × 0**.

Sin peso y medidas, ningún transportista integrado aparece en el checkout. Además, Envío Nube puede rechazar un reintegro por daño si el envío tiene medidas en 0.

> Este documento no compara precios (todavía no hay costo ni peso): explica cómo se usa cada servicio y qué se automatiza.

---

## 1. Qué es y por qué importa para [MARCA]
El embosador es chico y pesado, y se hace a pedido. Para cada venta tenés que:
1. cotizar el envío en el checkout;
2. generar y pagar una etiqueta;
3. embalar;
4. despachar o pedir el retiro;
5. pasarle el seguimiento al cliente;
6. reclamar si se pierde o se rompe.

Elegir mal el servicio te deja haciendo a mano lo que podría ser automático, o sin seguro ante un extravío.

## 2. Cómo funciona en Argentina hoy: servicio por servicio

### 2.1 Envío Nube (integración nativa de Tiendanube)
Fuentes: centro de ayuda de Tiendanube, artículos enlazados abajo, consultados el 03/11/2026.

- **Qué es:** la logística de Tiendanube. Despacha por **Correo Argentino, Andreani y E-Pick** (entregas rápidas en grandes ciudades). **OCA no está.**
- **Cómo se contrata:**
  - **no hay que abrir cuenta con el correo**: se activa desde el panel, en la sección "Envío Nube";
  - la activación **no tiene costo** y está en todos los planes;
  - si no aparece, escribirle a soporte "Activar Envío Nube";
  - **[No verificado]** si pide CUIT o condición fiscal: la etiqueta se paga con el saldo de Tiendanube;
  - fuente: [Cómo activar Envío Nube](https://ayuda.tiendanube.com/es_AR/envio-nube/como-activar-envio-nube-en-mi-tienda).
- **Pago:** **prepago**. Cargás saldo con Mercado Pago y cada etiqueta se descuenta.
- **Ojo:** **las cuentas nuevas arrancan con un límite de 1 etiqueta por día**, que sube con la actividad o por revisión de soporte. Fuente: [Cómo obtener las etiquetas](https://ayuda.tiendanube.com/es_AR/envio-nube/como-obtener-las-etiquetas-de-envio-nube), actualizada el 09/10/2026. Las etiquetas vencen a los 30 días.
- **Límites del paquete:** Andreani y Correo Argentino aceptan hasta 50 kg, 150 cm por lado y 250 cm de suma. E-Pick acepta hasta 10 kg y 50 cm por lado. Fuente: [Peso y dimensiones](https://ayuda.tiendanube.com/es_AR/envio-nube/peso-y-dimensiones-maximas-permitidas-para-envio-nube), actualizada el 02/11/2026.
- **Flujo de un pedido** ([Qué hacer cuando recibo una orden](https://ayuda.tiendanube.com/es_AR/envio-nube/que-debo-hacer-cuando-recibo-una-orden-con-envio-nube), 12/06/2026):
  1. Verificar el pago.
  2. Embalar.
  3. Generar la etiqueta: en Ventas > marcar órdenes > Imprimir > "Etiquetas Envío Nube", o desde Envío Nube > Lista de envíos.
  4. Despachar en una sucursal de Correo Argentino o Andreani con recepción e-commerce, o por colecta.
  5. La orden pasa sola a "Enviado" cuando el correo escanea la etiqueta. **No la marques a mano.**
  6. El código de seguimiento se carga solo y el cliente recibe el email "Confirmación de envío".
- **Impresión:**
  - etiquetas de **10 × 15 cm**, pensadas para **impresora térmica**;
  - **sirve una impresora común en A4**, pegando con cuidado para que el código de barras quede liso;
  - **la impresión masiva no está en los planes Inicial ni Esencial** (sí en Impulso).
- **Retiro a domicilio (colecta):** **solo para tiendas con alto volumen**, en días y horarios acordados. Andreani pide un remito firmado por el chofer y Correo Argentino entrega una orden de trabajo. No se toman reclamos pasadas 72 h del despacho. Fuente: [Colecta](https://ayuda.tiendanube.com/es_AR/envio-nube-gestion-de-envios/como-funciona-la-colecta-de-paquetes-con-envio-nube), 28/09/2026.
- **Seguro y reclamos:** fuente [Seguro](https://ayuda.tiendanube.com/es_AR/envio-nube/como-asegurar-mis-entregas-frente-a-danos-y-extravios-con-envio-nube), 21/10/2026.
  - *Correo Argentino:* cubierto por la Ley Postal. En pérdida total, el valor declarado o hasta 21 veces el valor del envío, lo que sea menor. **La rotura no se indemniza.**
  - *Andreani:* seguro opcional al **1 % + IVA del total de la venta**, que se suma al envío que paga el cliente. Cubre rotura, robo y extravío, con tolerancia mensual del 1 % de los envíos. Se activa en Configuración > Medios de envío > Envío Nube > Puntos de despacho > "Seguro de envío". **Viene apagado.**
  - *Plazos* (desde "Entregado"): **rotura o daño 48 h**; otros motivos 72 h.
  - *Documentación:* código de seguimiento, descripción, fotos o video del paquete con la etiqueta, abierto, el producto dañado y el embalaje. En etiquetas manuales, la factura con valor igual al declarado.
  - *Plazo para mandar CBU:* 15 días.
  - Fuente del procedimiento: [Paquete dañado](https://ayuda.tiendanube.com/es_AR/envio-nube/que-hacer-si-un-paquete-de-envio-nube-llega-danado-o-roto).

### 2.2 Correo Argentino (MiCorreo, integración directa)
- **Cómo se contrata:**
  - cuenta en **MiCorreo** (correoargentino.com.ar), registrándote con tus datos y el domicilio de despacho;
  - la app de Tiendanube **requiere un plan pago**;
  - **[No verificado]** si MiCorreo pide CUIT o condición fiscal para persona humana: el artículo de Tiendanube no lo dice; consultá a atencionclientemedio@correoargentino.com.ar;
  - fuente: [Cómo integrar MiCorreo](https://ayuda.tiendanube.com/es_AR/integracion-correo-argentino/como-integrar-correo-argentino-micorreo-a-mi-tienda), actualizada el 27/07/2026.
- **Conexión:**
  1. Instalar la app "Correo Argentino" desde la Tienda de Aplicaciones.
  2. Iniciar sesión o registrarte en MiCorreo.
  3. En Configuraciones > Medios de envío > "Correo Argentino Shipping", habilitar clásico o expreso, a domicilio o sucursal; costo o días adicionales; envío gratis.
- **Límites:** de 0,010 a 50 kg; suma de lados de 1 a 300 cm; ningún lado mayor a 200 cm.
- **Flujo:**
  1. La orden se importa a MiCorreo ("Envío de paquete > Nuevo envío" o "Pendientes").
  2. Se cotiza y se paga (crédito previo o al generar, con Mercado Pago).
  3. En "Mis envíos > Pagados" > "Generar rótulos" se descargan **hasta 60 a la vez**. Las etiquetas **solo se imprimen desde MiCorreo**, no desde Tiendanube.
  4. Al despachar, el seguimiento se carga solo y el cliente recibe un email.
  - Fuente: [Preguntas frecuentes de Correo Argentino](https://ayuda.tiendanube.com/es_AR/correo-argentino/preguntas-frecuentes-sobre-correo-argentino), 06/02/2026.
- **Retiro a domicilio (pick-up):**
  - de lunes a sábado (sábados a la mañana);
  - **con costo adicional** que baja con el volumen;
  - se pide en MiCorreo > Mi Perfil > Configuraciones > Domicilios, con franja horaria;
  - Correo revisa a mano si tu código postal tiene cobertura.
- **Seguro:** **Correo Argentino no ofrece seguro** en esta integración (misma fuente).
- **Retiro del cliente en sucursal:** 5 días hábiles. Después vuelve al origen.
- **Reclamos:** **[No verificado]** el procedimiento de MiCorreo. Si despachás por Envío Nube, aplica lo del punto 2.1.

### 2.3 Andreani
- **Cómo se contrata:**
  - necesitás **credenciales de una cuenta Andreani** (se pide desde la web de Andreani, no desde Tiendanube);
  - tipos de cuenta: **prepaga**, o **cuenta corriente** con facturación semanal o mensual acordada con un ejecutivo;
  - **[No verificado]** requisitos (CUIT, volumen mínimo, contrato) y demora del alta; consulta: atenciondigital@andreani.com.
- **Conexión (app nueva):**
  1. Tener completos los datos de facturación de Tiendanube (si no, falla).
  2. Instalar la integración de Andreani.
  3. Aceptar permisos.
  4. Entrar a "Andreani" en el menú lateral con las credenciales.
  5. Activar opciones en Configuración > Medios de envío > Otros medios de envío.
  - Requiere peso y medidas en los productos.
  - Fuente: [Nueva app de Andreani](https://ayuda.tiendanube.com/es_AR/andreani/como-instalar-la-nueva-aplicacion-de-andreani-en-mi-tiendanube), 13/08/2026.
- **Flujo:** las etiquetas se imprimen desde el panel de Andreani dentro de Tiendanube, que también procesa el pago y admite procesamiento masivo.
- **Seguro:** según la modalidad de cuenta. En cuenta corriente, se consulta con el ejecutivo.
- **Ojo:** la app anterior tiene muchas reseñas negativas: fallas de integración y etiquetas que no se generan ([ficha de la app](https://www.tiendanube.com/tienda-aplicaciones-nube/andreani2)). **Para arrancar, Andreani por Envío Nube es más simple.**

### 2.4 OCA (e-Pak)
- **Cómo se contrata:**
  - desde la app OCA e-Pak de Tiendanube > "Crear cuenta en OCA" > formulario;
  - el alta llega por email en **24 a 48 h hábiles**;
  - otra guía habla de ~7 días hábiles si se pide desde el administrador.
  - **[No verificado]** qué documentación pide (CUIT y condición fiscal); consulta: tiendanube@oca.com.ar.
- **Conexión:**
  1. Instalar la app.
  2. Iniciar sesión con email, **número de cuenta** y contraseña.
  3. Cargar los datos del remitente y el origen.
  4. Elegir la sucursal más cercana.
  5. Definir el despacho por defecto (domicilio con días y horarios de recolección, o sucursal).
  6. Elegir **operativas** (PaP TN, PaS TN, SaP TN, SaS TN).
  7. Tamaño de paquete por defecto.
  8. **Activar "Pedir teléfono de contacto" en Opciones del checkout.**
  9. Habilitar modalidades en Formas de entrega.
  - Fuente: [Cómo integrar OCA](https://ayuda.tiendanube.com/es_AR/122816-oca/como-integrar-oca-con-mi-tiendanube), 25/09/2026.
- **Retiro:** OCA puede retirar en tu domicilio u oficina, o llevás a un punto drop-off.
- **Etiquetas:** etiqueta oficial por pedido, con impresión masiva desde el administrador.
- **Seguimiento y reclamos:** **[No verificado]** No figuran en el artículo.

### 2.5 DHL
- **¿Opera dentro de Argentina?**
  - La [Guía de Servicios y Tarifas DHL Express 2025 Argentina](https://mydhl.express.dhl/content/dam/downloads/ar/es/rate-guide/service_and_rate_guide_ar_es_2025.pdf.coredownload.pdf) ofrece un **servicio "Domestic Express"** para envíos **dentro del país**, con entrega al **siguiente día laborable**, y lista cargos nacionales en pesos (por ejemplo, seguro nacional de $210 o 1 % del valor declarado).
  - **[No verificado]** La cobertura por código postal y las tarifas domésticas vigentes en 2026. DHL está enfocado en el envío **internacional**, y su red en Argentina es de unas 30 sucursales.
- **Integración con Tiendanube:**
  - la app oficial "DHL Express" sirve para **envíos internacionales**;
  - requiere una **cuenta corporativa DHL Express** + registro en DHL Express Commerce + número de cuenta, y en Argentina configurar la moneda en **USD**;
  - la app tiene 3,3/5 con 12 evaluaciones, con quejas de sincronización;
  - fuente: [Cómo integrar DHL](https://ayuda.tiendanube.com/es_AR/envios-internacionales/como-integrar-dhl-a-mi-tienda-) y [ficha de la app](https://www.tiendanube.com/tienda-aplicaciones-nube/dhl-express).
- **Sin cuenta:** se puede enviar desde una sucursal o Service Point pagando en mostrador. **[No verificado]** si esto vale para el servicio doméstico.
- **Para [MARCA]:** **no tiene sentido para envíos nacionales** de un producto de $82.500 al arrancar. Solo si algún día vendés al exterior.

### 2.6 Sin cuenta, por mostrador (Correo Argentino, Andreani, OCA)
- Podés llevar el paquete a una sucursal y pagar en el mostrador como cliente minorista.
- **Qué cambia:**
  - no hay cotización automática en el checkout: tenés que crear un **"envío personalizado"** con precio fijo o por zona;
  - cargás a mano los datos del destinatario;
  - cargás a mano el código de seguimiento en la orden;
  - no hay retiro a domicilio;
  - la tarifa minorista suele ser más alta **[No verificado]**.
- Sirve para los primeros 2 o 3 pedidos mientras configurás todo, no como sistema.

## 3. Qué aplica concretamente a [MARCA]

### 3.1 Qué se automatiza y qué queda a mano

| Tarea | Envío Nube | MiCorreo | Andreani app | OCA e-Pak | Mostrador |
|---|---|---|---|---|---|
| Cotización en el checkout | Automática | Automática | Automática | Automática | Manual (envío personalizado) |
| Generar etiqueta | 1 clic, en lote en Impulso | En MiCorreo, hasta 60 por vez | En el panel de Andreani, en lote | En lote | En el mostrador |
| Pago de la etiqueta | Saldo prepago | Crédito o Mercado Pago | Prepaga o cuenta corriente | Según cuenta | En el mostrador |
| Seguimiento al cliente | Automático | Automático | **[No verificado]** | **[No verificado]** | Manual |
| Retiro a domicilio | Solo alto volumen | Sí, con costo | **[No verificado]** | Sí | No |
| Seguro | Andreani 1 % + IVA; Correo por Ley Postal | No | Según cuenta | **[No verificado]** | Según el correo |
| Cuenta propia con el correo | **No hace falta** | Sí | Sí | Sí | No |

**Recomendación operativa para arrancar:**
- **Envío Nube**, sin cuentas propias, con seguimiento automático y la impresión en lote que habilita Impulso.
- Ofrecer **Correo Argentino** (llega a todos lados) y **Andreani con seguro activado**. El seguro es importante: la rotura no la cubre Correo y el producto vale $82.500.
- Pedir a soporte, **antes del lanzamiento**, que suban el **límite de 1 etiqueta por día**.

### 3.2 Peso y medidas: qué preguntarle al fabricante
Ver el cuestionario completo en el 07. Lo mínimo:
1. Peso del embosador solo, en gramos.
2. Peso y medidas exteriores (alto × ancho × largo en cm) del embosador **con su estuche o caja**.
3. Peso y medidas del pack regalo y de la placa de diseño extra suelta.
4. Peso de los packs de stickers de 100, 200 y 500.
5. Si lo entrega ya embalado para envío o hay que reembalar.
6. Cuántas unidades entran por caja máster, para calcular el envío del fabricante a vos.

**Rango orientativo [No verificado]:**
- Un sello seco de mano (tipo pinza) de metal suele pesar unos **250 a 600 g**.
- Con estuche o caja rígida, el paquete quedaría en **0,4 a 1 kg** y una caja de unos **15–20 × 10–15 × 6–10 cm**.
- Es solo una referencia para dimensionar la caja: **cargá en Tiendanube el dato real del fabricante**, porque Envío Nube y Mercado Libre miden el paquete y ajustan el costo si no coincide.

### 3.3 Embalaje de un producto chico y pesado
- **Caja de cartón corrugado** (simple onda alcanza para 1 kg) del tamaño justo, o caja postal troquelada (autoarmable, con mejor presentación para regalo).
- **Relleno** para que no se mueva: papel kraft arrugado, almohadillas de aire o burbuja. El peso concentrado golpea las paredes si hay aire libre.
- **El estuche del producto no es embalaje de envío:** va adentro de la caja.
- **Cinta** de embalaje marrón o transparente de 48 mm, en "H" en las dos tapas.
- Etiqueta plana sobre una cara lisa, sin cinta arriba del código de barras.
- **Dónde se consigue:** mayoristas de embalaje en La Plata y en el Gran Buenos Aires, y venta online (Mercado Libre, "cajas para envíos e-commerce"). **[No verificado]** Proveedores concretos y precios: pedir 2 o 3 presupuestos por 100 cajas.
- Recomendaciones de Envío Nube: [Cómo embalar](https://ayuda.tiendanube.com/es_AR/envio-nube/como-embalar-mis-productos-a-despachar-con-envio-nube).

### 3.4 Qué datos del cliente pedir en el checkout
- **Todos:** nombre y apellido, dirección completa (calle, número, piso o depto), localidad, provincia, **código postal**, email.
- **Teléfono:** obligatorio para OCA (opción "Pedir teléfono de contacto") y muy recomendable para todos.
- **DNI:** **[No verificado]** si el retiro en sucursal lo exige al destinatario. Envío Nube tiene un artículo sobre autorizar a otra persona a retirar ([enlace](https://ayuda.tiendanube.com/es_AR/envio-nube-seguimiento/como-autorizar-a-otra-persona-para-retirar-un-envio-de-envio-nube-en-sucursal)).
- Tiendanube pide nombre, email, dirección y código postal por defecto. Revisá en Configuración > Opciones del checkout que el teléfono sea obligatorio.

### 3.5 Qué se imprime y con qué
- **Etiqueta 10 × 15** por bulto, y en Andreani con colecta, el remito.
- **Arranque:** impresora común en A4 (4 etiquetas por hoja en algunos casos, o 1 por hoja) + tijera + cinta transparente sin tapar el código.
- **Desde unos 30 pedidos por mes:** impresora térmica de etiquetas 10 × 15. Ahorra tiempo y cinta. **[No verificado]** Modelo y precio.

## 4. Lo que tenés que hacer vos a mano
- Pedirle al fabricante los pesos y las medidas (07).
- Cargar el peso y las medidas en cada producto y variante. También lo puede hacer Claude con el prompt, una vez que tengas los datos.
- Activar Envío Nube, elegir los transportistas y **activar el seguro de Andreani**.
- Cargar saldo y pedir a soporte que suba el límite de etiquetas.
- Comprar cajas, relleno, cinta y, más adelante, una impresora térmica.
- Embalar, imprimir y llevar a la sucursal (o esperar la colecta).
- Ante un daño: sacar fotos y reclamar **dentro de las 48 h**.

## 5. Prompt para Claude Code Web

```
Leé investigacion-habilitacion/02-logistica.md del repo cunningham-lucas/Susurros-en-Relieve.
Datos del fabricante (completar): embosador con estuche [PESO_G] g, [ALTO]x[ANCHO]x[LARGO] cm; pack regalo
[...]; placa suelta [...]; stickers 100/200/500 [...]; caja de envío elegida [ALTO]x[ANCHO]x[LARGO] cm.
Tareas:
1. Con el conector de Tiendanube, actualizá peso (kg) y medidas (cm) de cada variante de cada producto con
   envío usando el peso y las medidas del paquete listo para despachar. Antes de guardar, mostrame la tabla
   de cambios y esperá mi OK.
2. Verificá con get_shipping_methods qué medios de envío quedaron activos.
3. Redactá en Markdown el procedimiento interno "Despacho diario" (checklist de 10 pasos) y el
   procedimiento "Reclamo por daño o extravío" con los plazos de 48 h y 72 h y la lista de fotos.
No actives medios de envío ni cargues saldo: eso lo hago yo. Commit en la rama de trabajo.
```

## 6. Paso a paso

| # | Paso | Quién | Demora |
|---|---|---|---|
| 1 | Pedir pesos y medidas al fabricante (07) | Vos | 1 a 2 semanas de respuesta |
| 2 | Definir la caja de envío y comprar una muestra | Vos | 1 semana |
| 3 | Pesar y medir el paquete real armado | Vos | 15 min |
| 4 | Cargar peso y medidas en todas las variantes | Claude (con tu OK) | 30 min |
| 5 | Activar Envío Nube; elegir Correo Argentino y Andreani, domicilio y sucursal | Vos | 30 min |
| 6 | Activar el seguro de Andreani | Vos | 5 min |
| 7 | Pedir a soporte que suba el límite de 1 etiqueta por día | Vos | 1 a 3 días de respuesta **[No verificado]** |
| 8 | Teléfono obligatorio en el checkout | Vos | 5 min |
| 9 | Compra de prueba a tu propia dirección: cotizar, generar etiqueta, despachar y ver que llegue el email con el seguimiento | Vos | 1 día + tránsito |
| 10 | Procedimientos internos de despacho y reclamo | Claude | 1 h |
| 11 | (Opcional) OCA o Andreani con cuenta propia si el volumen lo justifica | Vos | 2 a 7 días hábiles |

### Checklist antes del primer envío
- [ ] Peso y medidas reales cargados en todas las variantes (hoy están en 0).
- [ ] Envío Nube activo con al menos un transportista; seguro de Andreani encendido.
- [ ] Saldo cargado y límite de etiquetas ampliado.
- [ ] Teléfono obligatorio en el checkout.
- [ ] Cajas, relleno y cinta en casa; impresora probada con una etiqueta.
- [ ] Sucursal de Correo Argentino y de Andreani con recepción e-commerce identificada en La Plata.
- [ ] Política de envíos publicada con plazos de producción y envío reales (01b).
- [ ] Procedimiento de reclamo a mano (48 h por daño).
- [ ] Envío de prueba completo hecho.

## 7. [No verificado] y preguntas
**[No verificado]**
- Requisitos fiscales de MiCorreo, Andreani y OCA para persona humana.
- Seguimiento automático en las apps de Andreani y OCA.
- El procedimiento de reclamo de MiCorreo y OCA.
- Cobertura y tarifas de DHL Domestic Express.
- Rangos de peso del producto.
- Si el retiro en sucursal exige DNI.
- Proveedores de embalaje.

**Preguntas para soporte de Tiendanube (Envío Nube)**
1. ¿Cómo y cuándo se levanta el límite de 1 etiqueta por día en una cuenta nueva?
2. ¿Envío Nube pide CUIT o condición fiscal? ¿Me facturan las etiquetas a mi nombre?
3. ¿A partir de qué volumen habilitan la colecta en La Plata?
4. ¿El seguro de Andreani cubre productos personalizados por su valor de venta?

**Preguntas para Correo Argentino, Andreani y OCA** (solo si abrís cuenta propia)
1. ¿Qué requisitos tiene una persona humana monotributista para abrir cuenta? ¿Hay volumen mínimo?
2. ¿Tienen retiro a domicilio en mi código postal de La Plata? ¿Qué costo y frecuencia?
3. ¿Qué cubre el seguro y cómo es el reclamo por extravío o rotura (plazos y documentación)?

**Preguntas para el fabricante:** ver el 07.
