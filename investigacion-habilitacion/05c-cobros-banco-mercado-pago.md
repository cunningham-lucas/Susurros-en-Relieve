# 05c · Cobros: cuenta bancaria, Pago Nube y Mercado Pago

**Investigación:** 03/11/2026. **Tipo de cambio de trabajo:** USD 1 = ARS 1.650 → pedido de **$82.500**.
**Estado de la tienda (leído con el conector de Tiendanube el 03/11/2026):** el único medio de pago activo es **Pago Nube** (tarjeta de crédito, débito, transferencia y billetera). Mercado Pago no está conectado.

---

## 1. Qué es y por qué importa para [MARCA]
Para cobrar online necesitás tres cosas:
1. un **medio de pago** en la tienda: la pasarela que procesa la tarjeta o la transferencia;
2. una **cuenta donde retirar la plata** (CBU o CVU) a tu nombre y con tu CUIT;
3. que todo eso cierre con lo que facturás y declarás.

ARCA y ARBA cruzan las acreditaciones bancarias. Si en tu cuenta personal se mezclan gastos de la casa con ventas, los controles de "depósitos incompatibles" (05a) se te pueden volver en contra.

El medio de pago también decide:
- **cuánto te queda** de cada venta (comisión + plazo de cobro);
- **si podés automatizar la factura** (ver 06: con Pago Nube, solo Facturante factura automáticamente).

## 2. Cómo funciona en Argentina hoy

### 2.1 Pago Nube (el que tenés activo)
Tarifas para el **plan Impulso**, desde, más IVA. Fuente: [Pago Nube](https://www.tiendanube.com/pago-nube), publicada el 27/08/2026 y modificada el 08/10/2026.

| Medio | 1 día | 7 días | 14 días | 30 días |
|---|---|---|---|---|
| Tarjeta de crédito, débito y MODO | 5,89 % | 4,19 % | 3,29 % | 2,85 % |
| Transferencia bancaria | 0,99 % (acreditación en 1 día) | | | |

- **Sin costo por transacción de Tiendanube:** en ventas con Pago Nube ese costo está 100 % bonificado.
- **Requisitos:**
  - DNI o pasaporte argentino;
  - CUIT o CUIL del titular;
  - cuenta bancaria o CVU **a nombre del mismo titular**;
  - **validación de identidad** para poder retirar.
  - Fuente: búsqueda en el centro de ayuda, [Cómo activar Pago Nube](https://ayuda.tiendanube.com/es_AR/pago-nube-2/como-activar-pagonube-en-mi-tienda). **[No verificado en detalle]**: un fragmento menciona criterios como "15 días desde la primera venta, $600.000 facturados y 10 ventas", pero no queda claro si son para la validación o para otra cosa.
- **Retenciones:** según tu condición fiscal, Pago Nube puede aplicar retenciones de IIBB (misma fuente).

### 2.2 Mercado Pago (Checkout Pro, integrado a Tiendanube)
Comisiones según plazo de disponibilidad, más IVA. Fuente: [Mercado Pago, checkout](https://www.mercadopago.com.ar/herramientas-para-vender/check-out), sin fecha visible, consultada el 03/11/2026.

| Al instante | 10 días | 18 días | 35 días |
|---|---|---|---|
| 6,29 % | 4,39 % | 3,39 % | 1,49 % |

- Mercado Pago aclara que los costos pueden variar según los impuestos provinciales, el medio de pago del cliente y el plazo elegido. Las **cuotas sin interés** (Cuota Simple) tienen costo aparte.
- **Costo por transacción de Tiendanube:** en **Impulso es 1 %** sobre ventas con medios externos como Mercado Pago. Se descuenta en Mercado Pago como "Uso de plataforma de terceros". Fuente: [Tiendanube, costos por transacción](https://ayuda.tiendanube.com/es_AR/123484-costos-por-transaccion/que-son-los-costos-por-transaccion-de-tiendanube), actualizada el 25/03/2026. **[No verificado]** Si ese 1 % lleva IVA.
- **Cuenta:** la cuenta de Mercado Pago es gratuita y tus clientes no necesitan cuenta para pagar.
- **¿Cuenta aparte o la personal?** Técnicamente podés usar tu cuenta personal de Mercado Pago, pero se mezcla con tus movimientos personales. Recomendación: **una cuenta de Mercado Pago dedicada a [MARCA]**. **[No verificado]** Si Mercado Pago permite dos cuentas con el mismo CUIT; si no, separá por la cuenta bancaria de destino. Preguntalo en la ayuda de Mercado Pago.

### 2.3 Cuánto te queda de un pedido de $82.500 (solo la comisión del cobro, IVA incluido)

| Opción | Comisión + IVA | Costo Tiendanube | Total | % del pedido |
|---|---|---|---|---|
| Pago Nube tarjeta, 14 días | $3.284 | $0 | $3.284 | 4,0 % |
| Pago Nube tarjeta, 1 día | $5.880 | $0 | $5.880 | 7,1 % |
| Pago Nube transferencia | $988 | $0 | $988 | 1,2 % |
| Mercado Pago al instante | $6.279 | $825 | $7.104 | 8,6 % |
| Mercado Pago 18 días | $3.384 | $825 | $4.209 | 5,1 % |
| Mercado Pago 35 días | $1.487 | $825 | $2.312 | 2,8 % |

No incluye retenciones de IIBB ni de otros impuestos, que dependen de tu encuadre (05b).

### 2.4 Cuenta bancaria
- Para retirar de Pago Nube o de Mercado Pago necesitás un CBU o CVU **a tu nombre**. Una cuenta compartida exige certificado de cotitularidad en Pago Nube.
- **[No verificado]** No revisé condiciones de cuentas "para emprendedores" o monotributistas de cada banco. Los requisitos habituales son:
  - DNI;
  - constancia de CUIT o monotributo;
  - a veces, constancia de domicilio.
- Muchas cuentas digitales se abren online en el día. Pedí las condiciones en tu banco.
- **Recomendado, no obligatorio:** una cuenta (o CVU) **solo para [MARCA]**, donde entren las ventas y salgan los pagos al fabricante, al correo y a las apps. Facilita la conciliación, la recategorización y la defensa ante una recategorización de oficio.

## 3. Qué aplica concretamente a [MARCA]
- **Recomendación para arrancar: Pago Nube solo.**
  - Es lo que ya está activo.
  - Es más barato que Mercado Pago a plazos comparables y no paga el 1 % de Tiendanube.
  - Tiene transferencia al 0,99 %.
- **La contra de Pago Nube es la facturación automática:** solo Facturante la hace con Pago Nube (06). A 10 o 30 pedidos por mes, facturar a mano es manejable. Arriba de eso, Facturante o cambiar de pasarela.
- **Sumar Mercado Pago como segunda opción** tiene sentido si los clientes la piden (mucha gente paga con dinero en cuenta o cuotas de Mercado Pago), o si vendés por Mercado Libre (04), donde cobrás sí o sí por Mercado Pago.
- **Plazo de acreditación:** a pedido y con fabricante tercerizado, el plazo condiciona tu caja: pagás al fabricante antes de cobrar. Elegí el plazo con el costo del producto en la mano: **14 días** suele ser el equilibrio en Pago Nube, pero depende de cuándo le pagás al fabricante.

**Qué decisiones dependen de qué dato**
| Decisión | Dato | Quién lo da |
|---|---|---|
| Plazo de acreditación | Cuándo y cómo le pagás al fabricante | El fabricante |
| Pago Nube solo o + Mercado Pago | Si vas a vender en Mercado Libre; si vas a facturar automático | Vos (04 y 06) |
| Cuenta nueva | Si tu cuenta actual mezcla gastos personales | Vos |
| Retenciones | Encuadre de IIBB | Contador (05b) |

## 4. Lo que tenés que hacer vos a mano
- Completar la validación de identidad de Pago Nube (DNI y, según el caso, selfie o biometría).
- Cargar el CBU o CVU de retiro a tu nombre.
- Elegir el plazo de acreditación en el panel de Pago Nube.
- Abrir la cuenta bancaria o de Mercado Pago dedicada, si decidís separar.
- Si sumás Mercado Pago:
  - iniciar sesión en Mercado Pago desde Tiendanube y autorizar la conexión;
  - configurar plazos y cuotas.
- Aceptar los términos de cada pasarela.

## 5. Prompt para Claude Code Web

```
Leé investigacion-habilitacion/05c-cobros-banco-mercado-pago.md del repo cunningham-lucas/Susurros-en-Relieve.
Tareas (sin cambiar nada en la tienda):
1. Verificá en https://www.tiendanube.com/pago-nube y en
   https://www.mercadopago.com.ar/herramientas-para-vender/check-out si las comisiones cambiaron;
   actualizá las tablas 2.1, 2.2 y 2.3 con fecha.
2. Con el conector de Tiendanube (solo lectura), listá los medios de pago activos y confirmá el plan.
3. Armá una calculadora en Markdown y CSV: precio de venta, costo del producto puesto, costo de envío,
   comisión del medio de pago según plazo, costo por transacción de Tiendanube, cuota del monotributo
   prorrateada por pedido según escenario (10, 30, 100 pedidos por mes) → margen por pedido. Dejá el costo
   del producto y el envío como celdas a completar.
Marcá [No verificado] lo que no confirmes. Commit en la rama de trabajo.
```

## 6. Paso a paso

| # | Paso | Quién | Demora |
|---|---|---|---|
| 1 | Decidir si abrís una cuenta bancaria o CVU dedicada | Vos | — |
| 2 | Abrirla (online en el banco o en Mercado Pago) | Vos | De 1 día a 1 semana **[No verificado]** |
| 3 | Pago Nube: completar datos del titular, CUIT, CBU o CVU y validación de identidad | Vos | 30 min + validación |
| 4 | Elegir el plazo de acreditación | Vos | 5 min |
| 5 | Compra de prueba con tarjeta y con transferencia, y reembolso desde el panel | Vos | 30 min |
| 6 | (Opcional) Conectar Mercado Pago desde Configuración > Medios de pago | Vos | 15 min |
| 7 | Calculadora de margen | Claude | 1 h |
| 8 | Confirmar con el contador las retenciones esperadas | Contador | En la consulta |

## 7. [No verificado] y preguntas
**[No verificado]**
- Los criterios exactos de validación de identidad de Pago Nube.
- Si el 1 % de Tiendanube lleva IVA.
- Las condiciones de cuentas para emprendedores en bancos.
- Si Mercado Pago permite una segunda cuenta con el mismo CUIT.

**Preguntas para soporte de Tiendanube / Pago Nube**
1. ¿Qué requisitos exactos tiene la validación de identidad para retirar y cuánto demora?
2. ¿Qué retenciones de IIBB aplica Pago Nube a un monotributista de PBA en el régimen simplificado? ¿Y en Convenio Multilateral?
3. ¿Cómo se hace un reembolso parcial o total y en cuánto le llega al cliente?
4. ¿Facturante sigue siendo la única app que factura automáticamente con Pago Nube?

**Pregunta para el contador**
1. ¿Me conviene una cuenta separada para el emprendimiento? ¿Qué movimientos no debería mezclar?
