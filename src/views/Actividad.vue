<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      // Para cuestionario usar: ActividadController(:cuestionario="cuestionario") 
      // Para parrafo usar: ActividadController(:parrafo="parrafo")
      ActividadController(:cuestionario="cuestionario")
  </template>

<script>
import ActividadController from '@ecored-sena/base-kit/plugin/components/actividad/ActividadController.vue'

export default {
  name: 'ActividadDidactica',
  components: {
    ActividadController,
  },
  data: () => ({
    cuestionario: {
      tema: 'Destrezas en el punto de pago',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> verificar la comprensión de los conceptos fundamentales relacionados con el recaudo en el punto de pago, la base y apertura de caja, la validación de transacciones, la legalidad y seguridad de los medios de pago, el arqueo de caja, las devoluciones, el empaque de productos y la clasificación de envases y embalajes.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto:
            'El recaudo en el punto de pago se entiende principalmente como:',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La acción de culminar con amabilidad la experiencia de compra, registrando con agilidad y precisión los artículos seleccionados.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'La actividad de exhibir productos en las góndolas del establecimiento.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'La programación de campañas promocionales antes de la apertura del almacén.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'El proceso de ordenar únicamente la bodega antes de atender clientes.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 2,
          texto: 'La finalidad del recaudo en caja es:',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Reemplazar los protocolos definidos por la compañía.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Brindar excelente servicio al cliente mediante el correcto registro y cobro de la mercancía.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Evitar informar al cliente sobre el valor total de su compra.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Registrar únicamente productos que tengan descuento.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 3,
          texto: 'La base de caja corresponde a:',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'El reporte final que se entrega al supervisor al cerrar la jornada.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El listado de productos que no tienen código de barras.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'La primera cantidad de dinero en billetes y monedas para dar cambio a los clientes.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'El material de empaque que se entrega al cajero al iniciar el turno.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 4,
          texto:
            'Antes de dirigirse al puesto de pago con la base, el cajero debe:',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Empacar la mercancía del cliente anterior.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Guardar el dinero sin contarlo para ahorrar tiempo.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Solicitar al cliente que pague por otro medio.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Verificar que la cantidad recibida coincida con el valor asignado en el sistema.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 5,
          texto:
            'Durante la validación de transacciones, una práctica adecuada consiste en:',
          imagen: require('@/assets/actividad/imagen05.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Mantener concentración en el registro sin descuidar lo que ocurre alrededor del puesto de pago.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Registrar los productos sin revisar su estado físico.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Ubicar la mercancía de cualquier forma porque ya pertenece al cliente.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Ignorar los productos con tapa o cajas cerradas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 6,
          texto:
            'Al registrar productos como vajillas, huevos o bombillos, el cajero debe:',
          imagen: require('@/assets/actividad/imagen6.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Pasarlos rápidamente sin intervención del cliente.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Verificar su estado para prevenir reclamos, averías o inconsistencias.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Empacarlos siempre con productos de aseo del hogar.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Evitar revisar el producto aunque esté destapado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 7,
          texto: 'El desactivador de <i>tags</i> se utiliza para:',
          imagen: require('@/assets/actividad/imagen7.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Calcular el precio final de los artículos sin código.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Emitir comprobantes de pago electrónicos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Desactivar dispositivos de seguridad y evitar que se activen alarmas al salir del almacén.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Clasificar frutas y verduras por maduración.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 8,
          texto: 'El precio se define como:',
          imagen: require('@/assets/actividad/imagen8.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El material usado para empacar un producto.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El número de artículos que se compran en una transacción.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La bolsa seleccionada para transportar la mercancía.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'La cantidad de dinero necesaria para adquirir un bien o servicio.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 9,
          texto: 'Un medio de pago permite:',
          imagen: require('@/assets/actividad/imagen9.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Adquirir productos o servicios y cancelar deudas mediante instrumentos físicos o electrónicos.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Eliminar la necesidad de validar las transacciones.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Sustituir la revisión de productos al momento de registrar.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Evitar el arqueo de caja al final de la jornada.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 10,
          texto:
            'Al elegir entre diferentes medios de pago, dos aspectos básicos para el cliente son:',
          imagen: require('@/assets/actividad/imagen10.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El color de la bolsa y la ubicación de la caja.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El incentivo costo-beneficio y las condiciones de seguridad o confiabilidad.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'El tamaño del almacén y el tipo de estantería.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'La marca del uniforme y la decoración del puesto de pago.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto: 'Un método de pago en línea seguro funciona como:',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Una lista manual de precios para productos sin código.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Un inventario físico de los productos registrados.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Un instrumento que permite recibir pagos pasando por un puente que regula y autoriza el flujo del dinero.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Una forma de evitar el uso de comprobantes de pago.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 12,
          texto:
            'Los niveles de seguridad de pago en línea mencionados en el componente son:',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Efectivo, bono y cheque.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Primario, secundario y terciario.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Precio, promoción y plaza.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Modo seguro o 3D Secure, modo mixto y modo normal o sin 3D Secure.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 13,
          texto: 'El arqueo o cierre de caja tiene como propósito:',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Verificar si el efectivo y los comprobantes físicos coinciden con los valores reportados en la venta de caja.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Decidir qué productos deben exhibirse en la entrada del almacén.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Cambiar las normas de medios de pago definidas por la empresa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Eliminar las devoluciones de mercancía.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 14,
          texto: 'Un faltante de dinero en caja puede originarse cuando:',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El cajero cobra un valor mayor al cliente.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Se dan devoluciones superiores, se pierden comprobantes o no se registran descuentos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'El cajero entrega menos cambio del correspondiente.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Se contabilizan entradas adicionales no reportadas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 15,
          texto: 'Un sobrante de dinero puede presentarse cuando:',
          imagen: require('@/assets/actividad/imagen05.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Se registra correctamente cada medio de pago.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Se protegen los comprobantes para conciliación bancaria.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'El cajero entrega menos devolución o cobra un valor mayor al cliente.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Se realiza el arqueo con todos los soportes completos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 16,
          texto:
            'La gestión adecuada de devoluciones permite a la organización:',
          imagen: require('@/assets/actividad/imagen6.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Desconocer las necesidades del cliente después de la compra.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Evitar todo registro de productos retornados.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Desechar siempre todos los productos devueltos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Comercializar nuevamente lo que esté en buenas condiciones y rescatar partes útiles cuando aplique.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 17,
          texto: 'El empaque en el punto de pago es importante porque:',
          imagen: require('@/assets/actividad/imagen7.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Es la última acción con el cliente y facilita el transporte de sus productos, dejando una impresión positiva.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Sustituye la validación del medio de pago.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Evita que se realice el cierre de caja.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Elimina la necesidad de clasificar productos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 18,
          texto: 'Una técnica correcta de empaque consiste en:',
          imagen: require('@/assets/actividad/imagen8.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Poner artículos húmedos junto a productos secos sin protección.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Distribuir el peso y colocar en el fondo los artículos sólidos y pesados para dar firmeza.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Usar siempre una bolsa pequeña sin importar el tamaño del producto.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Mezclar insecticidas con alimentos para ahorrar espacio.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 19,
          texto:
            'Al empacar frutas y verduras, se debe considerar su clasificación por:',
          imagen: require('@/assets/actividad/imagen9.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Número de factura, nombre del cajero y hora de compra.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Tipo de caja registradora y forma de pago.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Grupo, tamaño, color, olor, maduración, peso y constitución.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Valor del descuento y código del supervisor.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },

        {
          id: 20,
          texto:
            'La diferencia entre envase primario, secundario y terciario es que:',
          imagen: require('@/assets/actividad/imagen10.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Los tres cumplen exactamente la misma función y siempre están en contacto directo con el producto.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El primario solo se usa para distribución, el secundario para consumo y el terciario para venta individual.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'El terciario siempre reemplaza al producto y no requiere protección.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'El primario está en contacto directo con el producto, el secundario agrupa envases primarios y el terciario unifica y protege durante la distribución.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: 'Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: 'Ha superado la actividad. ',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica. ',
    },
  }),
}
</script>
