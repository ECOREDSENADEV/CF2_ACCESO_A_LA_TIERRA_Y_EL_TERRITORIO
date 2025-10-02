<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Métodos de investigación participativa en comunidades campesinas',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> identificar los conceptos clave sobre investigación cualitativa y cuantitativa, técnicas participativas, herramientas de recolección de información y su aplicación en comunidades campesinas.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO.',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Qué objetivo principal tiene la investigación en comunidades campesinas?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Promover el uso de tecnologías avanzadas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Caracterizar la comunidad y proponer soluciones a sus problemáticas.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Fomentar el comercio internacional de sus productos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reforzar la dependencia de actores externos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Cuál de las siguientes características corresponde a la investigación cuantitativa?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Usa relatos y experiencias.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Se basa en la observación participante.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Utiliza métodos estadísticos y datos numéricos.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Busca comprender significados culturales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Qué distingue a la Investigación Acción Participativa (IAP)?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Es una investigación sin participación de la comunidad.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Solo aplica en contextos urbanos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Involucra a la comunidad en todas las etapas del proceso.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Requiere expertos externos para su ejecución.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Cuál de las siguientes técnicas permite un diálogo horizontal entre diferentes tipos de conocimientos?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Grupo focal.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Diálogo de saberes.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Entrevista estructurada.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Encuesta.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Qué instrumento permite registrar observaciones, emociones y reflexiones durante el trabajo en campo?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Formulario de contacto.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Diario de campo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Cuestionario.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Gráfico estadístico.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué característica define al taller dentro de la investigación participativa?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Se limita a la recolección de datos numéricos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Es exclusivo para expertos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Combina reflexión, diálogo y actividades prácticas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'No permite la participación activa.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Qué representa un mapa de territorio?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La visión comunitaria de su espacio físico, social y cultural.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Las coordenadas exactas de la comunidad.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'El plano técnico diseñado por profesionales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'El esquema legal de tenencia de la tierra.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué permite analizar el método FODA en una comunidad campesina?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Solo aspectos geográficos del territorio.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El potencial turístico de la zona.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Fortalezas, oportunidades, debilidades y amenazas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Las decisiones del gobierno local.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Cuál es una función clave de los dibujos participativos en la investigación?  ',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Medir productividad agrícola.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Expresar ideas y necesidades desde la perspectiva local.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Registrar datos técnicos del suelo.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reemplazar encuestas estructuradas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Qué herramienta tecnológica se usa comúnmente para tabular datos en la investigación participativa?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Microsoft Word.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Paint.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Google Earth.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Microsoft Excel.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'La investigación cualitativa se enfoca en comprender experiencias y significados desde la voz de los participantes.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'El grupo focal es una técnica exclusiva para la recolección de datos numéricos.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto:
            'La cartografía social busca representar el territorio desde la perspectiva técnica de ingenieros.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto:
            'La organización de la información debe hacerse de forma colectiva junto con la comunidad.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            'Un cuestionario debe contener preguntas largas y complejas para obtener información detallada.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
