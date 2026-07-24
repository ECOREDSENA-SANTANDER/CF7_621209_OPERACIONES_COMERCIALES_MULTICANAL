<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-secundario
      .titulo-principal__numero
        span 3
      h1 Empaque de productos

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12.col-md-12.col-12
        .bloque-texto-g.bgazul.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema3/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            p.mb-4 Es la última acción que realiza el cajero con el cliente en el puesto de pago, facilitándole el transporte de sus productos. Es un proceso de mucha importancia, ya que parte de la buena imagen de la compañía es el empaque, para el cliente esta última impresión debe ser grata y positiva.
            br
            br
            |
    p.mb-4 Para que logre prestar un excelente servicio de empaque debe tener en cuenta las siguientes recomendaciones: 
    
    .row.mb-5
      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.p-4
          .row.justify-content-center.mb-3
            .col-6.col-lg-5.col-4
              figure
                img(src='@/assets/curso/tema3/ico1.png', alt='')
              h3.blanco.text-center.text-white 1
          p.text-center El material debe estar siempre organizado para que evite demoras al momento de seleccionar una bolsa.

      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.p-4
          .row.justify-content-center.mb-3
            .col-5.col-lg-4
              figure
                img(src='@/assets/curso/tema3/ico2.png', alt='')
              .py-2
              h3.blanco.text-center.text-white 2
          p.text-center.mb-3 Las bolsas están identificadas por tamaño y resistencia para evitar el gasto inoficioso y facilitar el empaque.
          br
      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.p-4
          .row.justify-content-center.mb-2
            .col-5.col-lg-4
              figure
                img(src='@/assets/curso/tema3/ico3.png', alt='')
              .py-2
              h3.blanco.text-center.mb-3.text-white 3
          p.text-center Durante el registro debe organizar y clasificar la mercancía de acuerdo con su tamaño, características físicas y composición.
          br
    
    .row.justify-content-start.mb-3(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .d-flex.align-items-center.mt-4
          img.w-card-icon(src="@/assets/curso/tema2/icon.svg")
          .bg55.py-2.w-card-text.fw-bold.text-white La técnica de empaque
      .py-3
      p Al momento de empacar los productos se deben tener en cuenta los siguientes pasos:

    
    .row.justify-content-center.align-items-center.fondo3.p-4
      .py-3
      .col-lg-11
        .tarjeta.tarjeta--gris.p-4.mb-5
          LineaTiempoC.color-acento-contenido(text-small)
            .row(titulo="1").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/1.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 1
                p Observe los productos y proceda a seleccionar la bolsa.
 
            .row(titulo="2").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/2.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 2
                p Para abrir la bolsa introduzca las manos sin sacudirla.          
              
            
            .row(titulo="3").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/3.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 3
                p Debe distribuir el peso en las bolsas para que el cliente pueda llevarlas en forma equilibrada.
            
            .row(titulo="4").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/4.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 4
                p Recuerde que, para artículos pequeños, use bolsas pequeñas; para artículos grandes, use bolsas grandes. Ponga pocos artículos en bolsas pequeñas y muchos artículos en bolsas grandes.
            
            .row(titulo="5").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/5.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 5
                p Se debe utilizar la bolsa sin invertirla, ya que contiene la publicidad y la imagen de la empresa. Si el cliente lo requiere, se debe marcar con lapicero.
            
            .row(titulo="6").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/6.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 6
                p Otorgue a la bolsa una base firme colocando en el fondo los artículos sólidos y pesados.
            
            .row(titulo="7").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/7.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 7
                p Si una bolsa se rasga, saque todos los artículos y empáquelos en otra.
            
            .row(titulo="8").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/8.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 8
                p Apriete bien las tapas de los frascos que contengan líquidos, así evitará que se rieguen durante el transporte.
            
            .row(titulo="9").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/9.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 9
                p Entre los frascos debe colocar otro artículo en caja o bolsa, para evitar que se quiebren. 
            
            .row(titulo="10").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/10.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 10
                p Disminuya el peso al empacar granos de diferentes tamaños, evitando que las bolsas queden demasiado pesadas.
            
            .row(titulo="11").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/11.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 11
                p Cuando el artículo es húmedo o fácil de derramar debe colocarlo primero en una bolsa plástica sin impresión.
            
            .row(titulo="12").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/12.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 12
                p Los productos de aseo deben ir con los de su misma especie, es decir, aseo hogar separado de aseo personal.
                P Los insecticidas y blanqueadores deben empacarse en bolsa separada, puesto que son venenosos.
            
            .row(titulo="13").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/13.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 13
                p Algunos productos como escobas, traperos, papel de regalo, flores, sillas, cartulina que por su forma o tamaño son muy difícil empacarlos en bolsas, se sujetan con una bolsa pequeña y el tiquete.
            
            .row(titulo="14").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/14.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 14
                p Los artículos que vienen empacados en cajas, como ollas, vajillas y televisores, se les adhiere el tiquete de compra.
            
            .row(titulo="15").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/15.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 15
                p Los licores, sobre todo los costosos, cuando son varios puede empacarlos en bolsa doble, evitando que se quiebren.
            
            .row(titulo="16").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/16.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 16
                p Los artículos de loza o cristal deben envolverse con papel antes de ser empacados en cajas de cartón o en bolsas cuando son pocos.
            
            .row(titulo="17").p-4
              .col-md-2.col-8
                figure
                  img(src='@/assets/curso/tema3/17.png', alt='')
              .col-md-10.mb-4.mb-md-0.py-2
                h5 Paso 17
                p Debe tener cuidado con productos como arepas, huevos, productos de panadería, bombillos, frutas y verduras.
    .py-2
    p Para que disminuya el riesgo de reclamos por pérdida de paquetes debe tener en cuenta las siguientes recomendaciones:


    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8
        img(src='@/assets/curso/tema3/img02.png', alt='')
        .py-4
      .col-lg-8  
        .row.justify-content-center
          .col-lg-5.col-md-6.mb-4.py-4
            .overflow-hidden.h-100.bg01.p-4
              .py-3
              img.img-a.img-t(src='@/assets/curso/tema3/num1.png', alt='')
              .py-2
              p.mb-0 Antes de iniciar un nuevo registro verifique que en el puesto de pago no hayan quedado paquetes o mercancía del cliente anterior.
              br
              br
              br
          
          .col-lg-5.col-md-6.mb-4.py-4
            .overflow-hidden.h-100.bg01.p-4 
              .py-3
              img.img-a.img-t(src='@/assets/curso/tema3/num2.png', alt='')
              .py-2
              p.mb-0 Anotar en el tiquete el código del empacador y notificar al cliente el número de paquetes.
              br
              br
              br

    .row.justify-content-start.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .d-flex.align-items-center.mt-4
          img.w-card-icon(src="@/assets/curso/tema2/icon.svg")
          .bg55.py-2.w-card-text.fw-bold.text-white El empaque simultáneo
    
    p.mb-4 Consiste en ir empacando a medida que se registra para agilizar la atención al cliente y descongestionar el puesto de pago. Algunos productos por su peso o contextura se prestan para que realice el empaque simultáneo: los textiles, los productos de panadería, la galletería, los pasabocas y los productos refrigerados.
    
    .row.justify-content-start.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .d-flex.align-items-center.mt-4
          img.w-card-icon(src="@/assets/curso/tema2/icon.svg")
          .bg55.py-2.w-card-text.fw-bold.text-white El empaque de frutas y verduras 

    p.mb-4 Para empacar estos productos debe tener en cuenta algunas clasificaciones:

    .row.justify-content-center.align-items-center.mb-5.fondo4.p-4
      .col-lg-11
        SlyderA.blanco1.p-4
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por grupos
              ul.lista-ul--color
                li
                  i.fas.fa-circle-check
                  |Ramas.
                li
                  i.fas.fa-circle-check
                  |Verduras.
                li
                  i.fas.fa-circle-check
                  |Frutas.
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img03.png', alt='')
          
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por tamaño
              ul.lista-ul--color
                li
                  i.fas.fa-circle-check
                  |Grandes. 
                li
                  i.fas.fa-circle-check
                  |Medianas.  
                li
                  i.fas.fa-circle-check
                  |Pequeñas.
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img04.png', alt='')             
            
          
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por color
              p La combinación de los colores de los productos debe ser agradable a la vista del cliente. Se debe tener en cuenta el contraste de los colores claros y oscuros (cuando se empaca en bolsa transparente).
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img05.png', alt='')     
          
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por olor
              p No se deben empacar productos de olores fuertes al lado de productos con aroma suave (siempre frutas y verduras aparte).
              p Ejemplo: cebollas con banano, naranjas con orégano o tomillo. 
              p Nota. Las hortalizas de hoja, los cítricos y los champiñones son propensos a absorber olores fuertes.
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img06.png', alt='')     
          
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por maduración
              p Según su velocidad de maduración y respiración, no se deben empacar juntos productos que liberen gas etileno.
              p Ejemplo: el plátano maduro con repollo, banano con tomate de aliño o arveja con hortalizas de hoja.
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img07.png', alt='')     
          
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por peso
              ul.lista-ul--color
                li
                  i.fas.fa-circle-check
                  |Pesados. 
                li
                  i.fas.fa-circle-check
                  |Semipesados. 
                li
                  i.fas.fa-circle-check
                  |Livianos.
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img08.png', alt='')     
          
          .row.justify-content-center.align-items-center.mb-5
            .col-md-6.mb-4.mb-md-0
              h5 Por constitución
              ul.lista-ul--color
                li
                  i.fas.fa-circle-check
                  |Resistentes. 
                li
                  i.fas.fa-circle-check
                  |Delicados.
              .py-2
            .col-md-4.col-8
              figure
                img(src='@/assets/curso/tema3/img09.png', alt='')              
    separador
    #t_3_1.titulo-segundo.mb-5
      h2 3.1  Descripción del empaque

    p.mb-3 El empaque es un momento importante del producto, en el diseño se debe tener en cuenta la protección y conservación adecuadas para que no se afecte durante el transporte, almacenamiento y entrega al cliente final, también es muy útil diferenciar y promocionar en la etiqueta del producto la marca y demás información que necesite comunicarse.

    .row.justify-content-start.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .d-flex.align-items-center.mt-4
          img.w-card-icon(src="@/assets/curso/tema2/icon.svg")
          .bg55.py-2.w-card-text.fw-bold.text-white La importancia del empaque
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8
        img(src='@/assets/curso/tema3/img10.png', alt='')
        .py-4
      .col-lg-8  
        .row.justify-content-center
          .col-lg-5.col-md-6.mb-4.py-4
            .overflow-hidden.h-100.bg5.p-4
              .py-3
              img.img-a.img-t(src='@/assets/curso/tema3/num1.png', alt='')
              .py-2
              p.mb-0 Consiste en proteger el producto para que llegue en las mejores condiciones al consumidor o cliente final.
              br
              br
              br
          
          .col-lg-5.col-md-6.mb-4.py-4
            .overflow-hidden.h-100.bg5.p-4 
              .py-3
              img.img-a.img-t(src='@/assets/curso/tema3/num2.png', alt='')
              .py-2
              p.mb-0 Una de las funciones que debe cumplir el empaque es ayudar a vender el producto, logrando que el canal de distribución quiera comercializarlo por considerar que es fácil de transportar y almacenar.
              br
              br
              br
    p.mb-3 También se consideran envases los artículos desechables utilizados para contener, proteger o facilitar el transporte de los productos. Entre ellos se encuentran las bolsas entregadas o adquiridas por el cliente en los establecimientos comerciales, así como las bandejas, los platos, los vasos, los cubiertos y otros recipientes de un solo uso.
    separador
    #t_3_2.titulo-segundo.mb-5
      h2 3.2 Tipos

    .row.justify-content-center.align-items-center.mb-2
      .col-lg-4.col-8
        img.mb-2(src='@/assets/curso/tema3/img11.png', alt='')
      .col-lg-8
        .row.justify-content-center.align-items-center
          .col-lg-11
            p Cada producto tiene su propio envase y embalaje, el envase primario tiene como función contenerlo, envolverlo, protegerlo y conservarlo, es el primer contacto con el producto, el empaque secundario tiene uno o varios embalajes primarios.
          .col-lg-1.col-3
            img.mb-3(src='@/assets/curso/tema3/img12.png', alt='')
        .cajon.color-primario.p-4.mb-4
          p Teniendo en cuenta los diferentes tipos de envases se deben categorizar en primarios, secundarios y terciarios, el envase primario es el que protege y está en contacto directo con el producto, el secundario contiene varios productos y facilita su traslado, el terciario es el que contiene envases grandes con mucha mercancía.

   


    .row.justify-content-start.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .d-flex.align-items-center.mt-4
          img.w-card-icon(src="@/assets/curso/tema2/icon.svg")
          .bg55.py-3.w-card-text.fw-bold.text-white Tipos de envases para los alimentos

    p.mb-3 Los envases para alimentos y bebidas se elaboran con materiales como metal, vidrio, plástico, papel y cartón. Cada material presenta características, ventajas y desventajas según el producto que debe contener y proteger. A continuación, consulte el recurso para conocer los tipos de envases y sus principales características.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12.col-12.col-sm-12
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in-left")
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/01.png' alt='')
            h5.text-center.mt-4 El envase primario
            p.mt-4 Es el que tiene contacto directo con el producto, además de contener el producto permite su consumo. 
            p.mt-4 Un ejemplo de envase primario son las latas que contienen leche, sea líquida o en polvo. La función de este primer envase es cumplir con dos condiciones principales: proteger la mercancía y fomentar las ventas.
          
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/02.png' alt='')
              h5.mt-4.text-center Envase secundario
              p.mt-4 Es el contenedor unitario de uno o varios envases primarios. Su función es protegerlos, identificarlos y proporcionar información sobre las cualidades del producto.
          
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/03.png' alt='')
              h5.mt-4.text-center Envase terciario
              p.mt-4 Es el envase que cumple con la función de distribuir, unificar y proteger el producto a lo largo de la cadena comercial.  Este envase se refiere a la caja de cartón corrugado que contendrá varias latas de leche para su distribución a los almacenes.
          
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/04.png' alt='')
            h5.text-center.mt-4 ¿Qué es el envase y sus características?
            p.mt-4 El envase es todo recipiente o soporte destinado a contener un producto para así poder facilitar su transporte. 
            p.mt-4 Un buen envase se identifica por las siguientes características: posibilidad de contener el producto y resistencia.
          
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/05.png' alt='')
              h5.text-center.mt-4 ¿Cuál es el mejor envase para alimentos?
              p.mt-4 Unos de los envases que más se usa para empacar alimentos es el aluminio y la hojalata, ya que son más confiables que las bolsas de plástico a la hora del transporte, también porque extiende la vida útil del producto, factor importante en la planificación y sostenibilidad de la venta.
          
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/06.png')
            h5.text-center.mt-4 ¿Qué tipo de envases plásticos se pueden utilizar para alimentos?
            p.mt-4 El PET (material sintético denominado tereftalato de polietileno) es muy usado en el envasado de los diferentes tipos de refrescos, bebidas para deportistas, agua, salsas, aderezos para ensaladas, vitaminas, botellas de aceite vegetal y envasado de mantequilla de maní. Pero también existen otros materiales.
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/07.png' alt='')
              h5.text-center.mt-4 ¿Cuál es uno de los materiales más utilizados para fabricar envases de alimentos?
              p.mt-4 El plástico es uno de los materiales más utilizados para fabricar envases de alimentos debido a sus propiedades. Entre los tipos de plástico empleados se encuentra el PET (tereftalato de polietileno), valorado por su inercia química y su facilidad para adoptar diferentes formas.
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/08.png' alt='')
              h5.text-center.mt-4 Envases plásticos aptos para microondas
              p.mt-4 Solo se deben utilizar en el microondas los envases plásticos que indiquen expresamente que son aptos para este uso. Los recipientes no autorizados pueden deformarse, fundirse o liberar sustancias que contaminen los alimentos.

          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-7
                img.mt-2(src='@/assets/curso/tema3/09.png' alt='')
            h5.text-center.mt-4 ¿Qué recipientes no se pueden meter en el microondas?
            p.mt-4 Hay que ser muy cuidadoso con los recipientes que se usan para la preparación de alimentos en el microondas, no se pueden utilizar el papel de aluminio o las tapas metálicas hasta recipientes de acero inoxidable o las vajillas decoradas con pinturas metálicas. 
            p.mt-4 No se deben usar los recipientes herméticamente cerrados e incluso los alimentos con cáscara o piel dura para evitar que revienten.
      


    separador
    #t_3_3.titulo-segundo.mb-5
      h2 3.3  Normativa y clasificación

    p.mb-4 La clasificación de los envases debe cumplir con las normas específicas para cada uno de ellos según su capacidad, su textura y su fin estratégico.

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-lg-12.col-md-12.col-12
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Según su capacidad")
            .row.justify-content-center
              .col-lg-8.mb-4
                ul.lista-ul.ps-2
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envase unitario:] envase que contiene una sola unidad de producto destinada a la venta al consumidor. Generalmente corresponde al envase primario, ya que está en contacto directo con el producto.
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envase múltiple:] recipiente o envoltura que contiene dos o más unidades de un mismo producto o de productos relacionados, destinados a la venta como una sola presentación.
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envase colectivo:] envoltura o recipiente que agrupa dos o más productos previamente envasados para facilitar su almacenamiento, transporte o distribución.
              .col-lg-4.mb-4
                img.img-a.img-t(src="@/assets/curso/tema3/img015.png")

          .row.col-xl-11.m-auto(titulo="Según su textura")
            .row.justify-content-center
              .col-lg-8.mb-4
                ul.lista-ul.ps-2
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envase rígido:] la rigidez de este envase permite ubicar el producto en estibas y soporta mayor peso sin sufrir daños, entre ellos están las latas metálicas y los envases de vidrio.
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b  Envase semirrígido:] la resistencia de este envase es menor al envase rígido, también se puede ubicar en estibas, entre ellos están los envases de plástico.
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envase flexible:] estos envases son fabricados con hojas de aluminio, papel, laminaciones, películas plásticas y otros materiales flexibles, no se deben almacenar en estibas, ya que se pueden deteriorar.
              .col-lg-4.mb-4
                img.img-a.img-t(src="@/assets/curso/tema3/img16.png")

          .row.col-xl-11.m-auto(titulo="Según su fin estratégico")
            .row.justify-content-center
              .col-lg-8.mb-4
                ul.lista-ul.ps-2
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envases de líneas de productos o por familias:] se utiliza en productos de la misma línea, con el objetivo de facilitar la publicidad de la marca.
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envases de uso posterior:] se elabora con el sentido de que sirva para diversos fines, se puede utilizar una vez se ha sacado de su envase o se ha consumido. 
                  li.d-flex.mb-4
                    i.fas.fa-circle-check
                    p.mb-0 #[b Envases promocionales:] este envase cumple con las funciones para las cuales fue elaborado y también sirve como promoción, esta función se hace con el fin de provocar al consumidor para su consumo.
              .col-lg-4.mb-4
                img.img-a.img-t(src="@/assets/curso/tema3/img17.png")



    .row.justify-content-start.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .d-flex.align-items-center.mt-4
          img.w-card-icon(src="@/assets/curso/tema2/icon.svg")
          .bg55.py-3.w-card-text.fw-bold.text-white Las Normas ISO para empaques y embalajes

    p.mb-3 Las certificaciones para las normas estandarizadas que involucran a los empaques y embalajes corresponden a las siguientes:
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8
        img.mb-3(src="@/assets/curso/tema3/img18.png")
      .col-lg-8.col-12
        SlyderF.mb-5(columnas="col-lg-6 col-xl-5")(data-aos="zoom-in-left")
          .tarjeta.color-secundario-cus.p-4
            .row.justify-content-center.mb-3
              .col-sm-3.col-lg-12.my-2.d-none.d-lg-block
                img(src='@/assets/curso/tema3/img19.png')
            .row.justify-content-center.mb-3
              h5.text-center.text-white ISO 3394
              p.text-center.text-white Se refiere a las dimensiones de cajas, plataformas o cargas con #[em pallets]. Las cajas externas o #[em masters], utilizadas para el embalaje deben ajustarse a 60 × 40 cm.
                
          .tarjeta.color-secundario-cus.p-4
            .row.justify-content-center.mb-3
              .col-sm-3.col-lg-12.my-2.d-none.d-lg-block
                img(src='@/assets/curso/tema3/img20.png')
            .row.justify-content-center.mb-3
              h5.text-center.text-white R87
              p.text-center.text-white Es una reglamentación desprendida de la norma anterior y hace referencia al etiquetado de envases para venta individual con descripción de ingredientes.
          
          .tarjeta.color-secundario-cus.p-4
            .row.justify-content-center.mb-3
              .col-sm-3.col-lg-12.my-2.d-none.d-lg-block
                img(src='@/assets/curso/tema3/img21.png')
            .row.justify-content-center.mb-3
              h5.text-center.text-white ISO 780 y 7000
              p.text-center.text-white Ambas cuidan que se agregue señalética para el manejo. Crear etiquetas con simbología que indique si se transporta algo frágil o que corre riesgo, o que pueda causarlos con mala manipulación.

          
          .tarjeta.color-secundario-cus.p-4
            .row.justify-content-center.mb-3
              .col-sm-3.col-lg-12.my-2.d-none.d-lg-block
                img(src='@/assets/curso/tema3/img22.png')
            .row.justify-content-center.mb-3
              h5.text-center.text-white ISO 14001
              p.text-center.text-white Esta certificación indica que la empresa está minimizando el impacto negativo que su actividad pudiera generar al medio ambiente.




    separador
    #t_3_4.titulo-segundo.mb-5
      h2 3.4  Técnicas de empaque

    .row.justify-content-center.align-items-center.mb-5
        .col-lg-12.col-md-12.col-12
          .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/tema3/img23.png')})`}"
            )
            .bloque-texto-g__texto.p-5
              p.mb-4 Uno de los empaques que requiere mayor cuidado es el destinado a frutas y verduras, ya que estos productos son delicados y es necesario proteger su calidad durante el transporte y su exhibición en los estantes del punto de venta. Este tipo de empaque debe seleccionarse de acuerdo con las características del producto y con el método de manipulación más adecuado. Asimismo, debe diseñarse para soportar las diferentes condiciones de la cadena de abastecimiento, como la manipulación durante la carga y descarga, la compresión ocasionada por el peso de otros contenedores (cuando se apilan en doble nivel), el movimiento durante el transporte y la alta humedad que puede presentarse durante el preenfriamiento. 
             
    p.mb-3 El tener un buen conocimiento de todos los aspectos de empaque es clave al momento de seleccionar el más adecuado, de acuerdo con el tipo de producto que se enviará y para tener un mejor manejo del producto durante el tránsito.

    .row.justify-content-center.align-items-center(data-aos="fade-left").mb-4
      .col-lg-12.col-12.col-md-12
        figure(data-aos="fade-right").py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/rYZXkd2sl7M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Empaque, almacenamiento y transporte del plátano



   

    separador
    #t_3_5.titulo-segundo.mb-5
      h2 3.5  Empaque de productos según naturaleza

    p.mb-3 Para elaborar empaques y embalajes se deben considerar las características del producto que se desea proteger y el medio de transporte que se utilizará. Entre los principales factores se encuentran los siguientes:
    
    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Figura 1.
      span Características del producto para seleccionar empaques y embalajes
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        img.mb-3(src="@/assets/curso/tema3/img20.svg", alt='Características para seleccionar empaques y embalajes: fragilidad, durabilidad, resistencia a la abrasión, sensibilidad a la humedad y vida útil.')

      p.mb-3 Los empaques y embalajes deben seleccionarse de acuerdo con las características del producto y las condiciones de manipulación y transporte. Entre los materiales más utilizados se encuentran la madera, el cartón, el plástico, el vidrio y el metal. La elección del material depende de sus propiedades físicas, mecánicas y químicas, así como de la protección que requiera el producto.
      p.mb-3 A continuación, consulte las ventajas y desventajas de los materiales más comunes utilizados en la elaboración de empaques y embalajes.
     
      .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
        .col-lg-12.col-md-12.col-12
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
            .row.col-xl-11.m-auto(titulo="Empaques de papel")
              .row.justify-content-center
                .col-lg-8.mb-4
                  p Son utilizados para envolver por dentro o por fuera otros empaques como bolsas o cajas, se usan también las cajas plegadizas de cartón, ya que estas pueden adoptar diversas formas, dado que se componen de varias capas.
                  h4 Ventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Reciclable.
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Permite la impresión en la superficie y de alta calidad. 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Fácil cortado, trazado, plegado. 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Fácil de pegar con cualquier tipo de adhesivo. 
                  h4 Desventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Son materiales altamente higroscópicos (capacidad de algunas sustancias o materiales). 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 No tiene propiedades de barrera contra líquidos, aceites y gases.
                .col-lg-4.mb-4
                  img.img-a.img-t(src="@/assets/curso/tema3/gr01.png")
            
            .row.col-xl-11.m-auto(titulo="Empaques de cartón corrugado")
              .row.justify-content-center
                .col-lg-8.mb-4
                  p Este tipo de empaque es usado para el transporte y protección de producto, es utilizado para empacar preferiblemente artesanías, maquinaria, electrodomésticos, calzado y alimentos.
                  h4 Ventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Ligereza y flexibilidad. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Versatilidad (forma y dimensiones). 
 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Amplia gama de resistencias mecánicas.
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Fácil de pegar con cualquier tipo de adhesivo. 
                  h4 Desventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Permeabilidad a los gases. 
 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Problemas de termoestabilidad. Empaques metálicos.
                .col-lg-4.mb-4
                  img.img-a.img-t(src="@/assets/curso/tema3/gr02.png")

            
            .row.col-xl-11.m-auto(titulo="Acero y aluminio")
              .row.justify-content-center
                .col-lg-8.mb-4
                  p Los dos principales materiales utilizados para la fabricación de empaques son el acero y el aluminio. 
                  p Los alimentos enlatados se empacan en acero y las bebidas con gas se empacan en aluminio.

                  h4 Ventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Resistencia mecánica. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Ligereza. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Protección de luz y radiación. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Conductividad térmica.
                  h4 Desventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Solo se producen empaques estandarizados y normalizados.
        
                .col-lg-4.mb-4
                  img.img-a.img-t(src="@/assets/curso/tema3/gr03.png")

            
            .row.col-xl-11.m-auto(titulo="Empaques de vidrio")
              .row.justify-content-center
                .col-lg-8.mb-4
                  p El envase de vidrio tiene la característica de ser muy fuerte, el inconveniente con este empaque es que tiene poca resistencia al impacto, una de sus mejores características es que protege de la contaminación, los más usados son los frascos y botellas, su principal uso se da en salsas, compotas, bebidas, cosméticos y medicamentos.

                  h4 Ventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 No altera el olor ni el sabor del contenido.


                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Actúa como barrera frente a gases y vapores, lo que favorece la conservación del producto.

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Puede soportar presión interna y procesos térmicos cuando el envase está diseñado para estas condiciones.

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Es reciclable.
                  h4 Desventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Fragilidad. 
 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Ocupan volumen cuando están vacíos.
                .col-lg-4.mb-4
                  img.img-a.img-t(src="@/assets/curso/tema3/gr04.png")

            
            .row.col-xl-11.m-auto(titulo="Empaques de madera")
              .row.justify-content-center
                .col-lg-8.mb-4
                  p Entre los empaques que existen está la madera, este es un producto natural, entre sus características está que es duro, moldeable y flexible, su mayor uso se da en los embalajes de productos de exportación, ya que requieren de una protección especial principalmente las partes para vehículos y la maquinaria pesada.

                  h4 Ventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Material abundante. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Robustez. 
 
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Su fabricación es fácil y no requiere equipos especiales. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Son reutilizables.
                  h4 Desventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Es más costoso. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Exige mayor trabajo y espacio de almacenamiento.
                .col-lg-4.mb-4
                  img.img-a.img-t(src="@/assets/curso/tema3/gr05.png")

            .row.col-xl-11.m-auto(titulo="Empaques con material textil")
              .row.justify-content-center
                .col-lg-8.mb-4
                  p Los empaques hechos con textiles especialmente se usan para elaborar bolsas y sacos, estos contienen fibras vegetales como el cáñamo, algodón, fique, yute y sisal, se utilizan especialmente para almacenar productos a granel. 

                  h4 Ventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Bajo costo. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Abundancia de materia prima.
              
                  h4 Desventajas
                  ul.lista-ul.ps-2
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Son sometidos a estrictos controles fitosanitarios. 

                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Poca adaptabilidad a equipos de manipulación.
                .col-lg-4.mb-4
                  img.img-a.img-t(src="@/assets/curso/tema3/gr06.png")


      p.mb-3 A continuación, se presentará en la tabla un resumen de la información abordada previamente sobre los materiales de los empaques y embalajes, con algunos ejemplos de estos:



    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-lg-12.col-md-12.col-12
        .titulo-sexto.color-acento-contenido(data-aos='fade-right', atl='La tabla presenta 7 filas y 5 columnas, donde se describen materiales de empaques y embalajes como: metales, madera, cartón, plástico, papel y vidrio; adicionalmente se mencionan algunos tipos, ejemplos, ventajas y desventajas.')
          h5 Tabla 1.
          span Materiales de empaques y embalajes
        .tabla-a.color-acento-contenido
          table
            thead
              tr
                th Materiales
                th Tipo
                th Ejemplo
                th Ventajas
                th Desventajas
            tbody
              tr
                td Metales
                td Láminas de aluminio y acero, recubiertas de estaño.
                td Contenedores, recipientes bajo presión, cajas metálicas.
                td Solidez, fácil estibado, reutilizables.
                td Costo elevado, corrosión, pesado y voluminoso.
              tr
                td Madera
                td Madera en bruto, cepillada y aglomerada.
                td Cajas, #[em pallets] y canastas.
                td Fácil de manipular y estibar.
                td Altos costos, sensible al sol y a la humedad, fácil descomposición, contaminable, sensible a plagas, inflamable y pesado.
              tr
                td Cartón
                td Plano, ondulado o corrugado.
                td Cajas de cartón.
                td Económico, reciclable y de fácil manipulación.
                td Muy frágil, sensible a la humedad y al calor, poco sólido, no reutilizable.
              tr
                td Plástico
                td Polietileno (PE), poliestireno (PS) y policloruro de vinilo (PVC).
                td Bolsas, toneles, bidones, cajas y contenedores.
                td Impermeabilidad, gran diversidad, reutilizable.
                td Inflamable, costoso y difícil eliminación.
              tr
                td Papel
                td Papel kraft, papel encerado y papel parafinado.
                td Bolsas.
                td Bajos costos y fácil eliminación.
                td Muy frágil, sensible a la humedad y al calor.

              tr
                td Vidrio
                td Vidrio sodocálcico y vidrio borosilicato.
                td Botellas, frascos y botellones.
                td Visibilidad del contenido, fácil estibado y reciclable.
                td Frágil a los golpes, pesado y voluminoso.

















</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
