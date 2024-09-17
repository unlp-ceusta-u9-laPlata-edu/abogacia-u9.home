# README - Landing Page de las redes sociales de la carrera de Abogacía

## [Visita la pagina](https://unlp-ceusta-u9-laplata-edu.github.io/abogacia-u9.home/landing-social/index.html)

## Introducción

<p style="font-size: 18px;">Bienvenido al repositorio oficial de la Landing Page de las redes sociales para la <span style="font-weight: bold; font-style: italic;">Carrera de Abogacía</span> del <span style="font-size: 19px; font-weight: bold; font-style: italic;">Centro Universitario Santo Tomás de Aquino</span>. Este proyecto está diseñado para centralizar y proporcionar acceso a los medios sociales y grupos de interés relacionados con nuestra carrera. Aquí podrás encontrar enlaces para unirte a nuestros grupos de discusión, redes sociales y otras plataformas que facilitan la interacción y colaboración entre estudiantes, profesores y egresados.</p>

## Contenido del Proyecto

### La página principal está orientada a ofrecer

    Enlaces a Medios Sociales: Conexiones a nuestros perfiles en redes sociales como Facebook, Whatsapp, Instagram, entre otros.
    Grupos de Estudio y Networking: Información sobre cómo unirse a grupos de estudio, discord y redes profesionales vinculadas a la Carrera de Abogacía.
    Actualizaciones y Anuncios: Información relevante sobre eventos, noticias y oportunidades en el campo del derecho (Próximamente).

## Cómo Clonar el Repositorio

<p style="font-size: 16px;">Para trabajar con este repositorio en tu entorno local, sigue estos pasos: </p>

    Clona el Repositorio: Abre Git Bash y navega al directorio donde deseas clonar el repositorio. Luego, ejecuta el siguiente comando:

``` git clone https://github.com/unlp-ceusta-u9-laPlata-edu/abogacia-u9.home.git ```

### Navega al Directorio del Proyecto:

``` cd tu-repositorio ```

### Cómo Trabajar con Git Bash
Realizar Cambios

    Crea una Rama Nueva: Antes de hacer cambios, es recomendable crear una nueva rama para mantener el trabajo organizado.

  ``` git checkout -b nombre-de-tu-rama ```

### Realiza los Cambios Necesarios: Edita los archivos en el directorio del proyecto usando tu editor de texto o IDE preferido.

Añade los Cambios: Una vez que hayas realizado los cambios, añade los archivos modificados al área de preparación (staging area).

``` git add . ```

### Confirma los Cambios: Realiza un commit con un mensaje descriptivo sobre los cambios que has realizado.

Para una mejor organización y entendimiento de los cambios, la sugerencia de los commits es la siguiente:

- "nombre de carrera"/
	Tienes que especificar el nombre de la carrera porque en los commits a simple vista no se verán hacia dónde fueron reflejados los cambios hasta que no sean revisados.

- frontend/
	Especifica que has trabajado en la rama del Frontend. Aún así deberás crear una rama propia y trabajar sobre la rama front-develop para realizar una pull request que será revisada y testeada.

- backend/ Especifica que has trabajado en la rama del Backend. Aún así deberás crear una rama propia y trabajar sobre la rama back-develop para realizar una pull request que será revisada y testeada.

- feature/
	Esto va seguido de la rama donde has trabajado.

- crud/
	Esto especifica que has creado, actualizado o eliminado algo. Ayuda a la comprensión de tu trabajo.

- event/
	Esto es específico para la creación de eventos institucionales. Da a entender que se creó, actualizó o eliminó un evento.

- fixbug/
	Especifica que se ha corregido algún error

### Ejemplos: 

``` frontend/front-develop/feature/crud/[EVENT-create,update,deleted-nombre del evento] o fixbug/[nombre del o los errores corregidos] ```

``` frontend/front-develop/feature/crud/[CREATE-add,update,delete-new(si corresponde)-feature-nombre de la característica] ```

``` frontend/front-develop/fixbug/[BUG-B001-nombre del error corregido] (Utilice la ID del bug registrado, si no la sabe puede consultarlo vía mail de contacto. Se encuentra al final de éste README. Porfavor, también indique si corresponde a una feature, event o según corresponda) ```

``` backend/back-develop/feature/crud/[CREATE-add,update,delete-new(si corresponde)-feature-nombre de la característica] ```

``` backend/back-develop/fixbug/[BUG-B001-nombre del error corregido] (Utilice la ID del bug registrado, si no la sabe puede consultarlo vía mail de contacto. Se encuentra al final de éste README. Porfavor, también indique si corresponde a una feature, event o según corresponda) ```

<p style="font-size: 18px;"> Estos ejemplos le dará una mejor idea de cómo colaborar y trabajar en las ramas correspondientes y hacer los commits ideales que permitan una mejor comprensión del trabajo realizado y de una manera organizada. Porfavor, utilice lenguaje inglés, en el caso de que no sepa inglés puede utilizar un traductor como <a href="https://translate.google.com.ar/?sl=auto&tl=es&op=translate">Google Translate</a> o mejor aún <a href="https://www.deepl.com/es/translator">DeepL</a>.

Un ejemplo mucho más claro y realista:</p>
``` git commit -m "frontend/front-develop/fixbug/[BUG-B001-Corregido el botón que no tenía acción alguna]" ```

### Enviar Cambios al Repositorio Remoto

    Actualiza la Rama Remota: Envía los cambios confirmados a la rama correspondiente en el repositorio remoto.

``` git push origin nombre-de-la-rama-trabajada(Puede ser: crud/fixbug/feature/event) ```

###     Crea una Solicitud de Extracción (Pull Request): Ve a la interfaz de GitHub y crea una Pull Request para solicitar la integración de tus cambios a la rama principal. JAMAS envíe sus cambios a la rama ```main``` ni a las ramas principales como ```frontend``` o ```backend```, éstas ramas son para mantenimiento del código fuente que ya es testeado y aprobado para integrarlo a la rama main. Si USTED realiza envíos a éstas ramas, sus cambios serán rechazados junto con su pull request y cerrado hasta que usted haga los pasos correctamente.

### Mantenimiento de la Página

Para garantizar que la página se mantenga actualizada y funcional:

    Revisa Regularmente: Verifica los enlaces y la información para asegurarte de que están actualizados y correctos.

    Actualiza Contenidos: Realiza actualizaciones según sea necesario para reflejar cambios en los medios sociales o en la estructura de los grupos.

    Monitorea la Interacción: Asegúrate de que los enlaces a los grupos y redes sociales funcionen correctamente y realiza ajustes si es necesario.

    Gestiona Issues y Pull Requests: Revisa y gestiona issues reportados por otros colaboradores y revisa las Pull Requests para integrarlas al repositorio principal.

### Contribuciones

Si deseas contribuir al proyecto sin ser colaborador, sigue estos pasos:

    Haz un Fork del Repositorio: Crea una copia del repositorio bajo tu cuenta de GitHub.

    Realiza Cambios en tu Fork: Trabaja en tu fork y sigue los pasos mencionados anteriormente para realizar cambios y enviar Pull Requests.

    Envía una Pull Request: Una vez que tus cambios estén listos, envía una Pull Request para revisar y fusionar tus contribuciones con el repositorio principal.

    Si lo deseas, también puedes pedir ser colaborador activo de los proyectos. El requisito es contar con la experiencia necesaria y demostrable para el proyecto en cuestión que solicites ser colaborador. Una vez hecha la solicitud, contactanos por el email que está más abajo y fijaremos una entrevista para conocerte.

### Contacto
<p style="font-size: 18px;">
Para más información o asistencia, puedes ponerte en contacto con el equipo de desarrollo a través de los siguientes medios <br>
    Email: ceusta.u9.laplata@gmail.com <br>
    Grupo de Soporte: https://www.instagram.com/marianomaldonado.dev/ </p>

# ¡Toda colaboración es bienvenida!
