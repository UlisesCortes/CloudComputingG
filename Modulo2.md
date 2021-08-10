# Modulo 2 Cómo se organiza la nube: desde la infraestructura hasta el software

## 1. Infraestructura como servicio (IaaS)
La infraestructura como servicio IaaS consiste en abstraer la capa hardware de la infraestructura y ofrecerla en modo servicio. Los servicios a ofertar pueden ser capacidades de cómputo, como CPU o memoria, almacenamiento y elementos de redes y comunicaciones.

Conceptos Clave:
- Iaas: Infraestructure as a Services
- Escogemos, la potencia de hardware que vamos a usar. (simulamos los componentes).
- Para poder construir por encima.
- adoptar modelo cloud implica asummir cambios
- la virtualización abstrae a las aplicaciones del hardware
- Virtual machines - Containers - API´s 


## 2. Gestión de un servicio Cloud
Cuanto mejor sea el rendimiento del servicio de Cloud que ofrecemos mayor número de usuarios tendremos, por lo tanto, es importante medir y controlar el rendimiento. Algo que nos puede ayudar a mejorar nuestro rendimiento es llevar a cabo un control del consumo que hacen de nuestro servicio.

Conceptos Clave:
- Control de rendimiento.
- Control de consumo.

## 3. Profundizamos: HDDC vs. SDDC
Es importante entender que no hay una decisión única para todas las necesidades y que para cada necesidad se debe aplicar una solución específica y personalizada. Para esto puede ser útil fijarse en la competencia y ver cómo se adapta a las necesidades de sus usuarios, además de saber qué servicio se quiere dar al cliente con el fin de que sea el mejor y dé un buen rendimiento.

Conceptos Clave:
-  Una solución especifica ha cada problema.

## 4. Plataforma como servicio (PaaS)
Las plataformas como servicio (servicio PaaS) son entornos que permiten desarrollar y desplegar aplicaciones de forma abstracta con respecto a la infraestructura. Este tipo de servicios te permiten independizar la plataforma de la infraestructura y gracias a esto los desarrollos obtienen una mayor portabilidad.

Conceptos Clave:
- tipo de middleware
- Tú pides unos recursos centrados en tu aplicación para construirla y desplegarla y que vaya creciendo.
- otra capa de software
- exhibir unas APIs al desarrollador, al integrador, al usuario, y esa misma plataforma lo que hace es consumir de la infraestructura tirando de la API de infraestructura
- La plataforma adiministra que necesecitas.


## 5. Software como servicio (SaaS)
Los servicios SaaS son la abstracción máxima de los servicios de Cloud. Permiten utilizar las ofertas disponibles de software que se ajustan a las necesidades de los usuarios. Se centran en la capa de software y en las funcionalidades que este ofrece, pero no permiten independizar la plataforma de la infraestructura, esto lo hace un servicio PaaS.
Conceptos Clave:
- Es una aplicación como tal que te administra 

## 6. Profundizamos: Arquitectura IaaS, PaaS
La transformación de la arquitectura del servicio Cloud, debe ir destinada a mejorar la calidad de nuestro servicio, creando una infraestructura como recurso. Incorporar módulos que ofrezcan un nivel de abstracción a la aplicación puede ser útil.

Conceptos Clave:
- IaaS: Abstraer recursos de infraestructura TI (computo, almacenamiento, redes) y ofrecerllos como servicio.
* Autoservicio -Bajo demanda- Elástico, Gestion de servio

- PaaS: Consume IaaS a través de API´s
* Se enfoca en la aplicación, abstrayendola de la infraestructura.
* ¿middleware como servicios?

## 7. El navegador como herramienta principal
Efectivamente, el navegador puede permitirnos el acceso offline a determinadas funcionalidades de las aplicaciones y mantener así la experiencia de usuario.

Conceptos Clave:
- Es muy estable
- El cambio en la forma de desarrollar.
- el navegador no implica siempre online, no significa estar siempre conectado. 

## 8. Cloudbrokers
El incremento de la oferta y la demanda ha generado que se creen modelos de negocio con base a la intermediación entre el proveedor de servicios iCloud y los clientes. Estos ayudan a entender la necesidad, encaminar la solución más adecuada y distribuir la demanda.
Conceptos Clave:
- Son perosnas (intermediario) que saben del tema y te pueden decir que incluyen los servicios de cloud.

Extras:

Las empresas que integran para su uso servicios de Cloud deben saber que tiene distintos componentes o partes. Estos componentes son infraestructura, plataforma y software. IaaS no es una tecnología diferente a virtualización. La virtualización es una capa de abstracción del software sobre la que se puede empezar a construir la infraestructura para ofrecerla como servicio.

Existen varios modelos de servicio Cloud pero si se utiliza como estructura servicio, debemos saber cómo gestionarlo. La gestión del servicio de Cloud no debe hacerse ni manualmente ni mediante la búsqueda de ciertos indicadores, ni tampoco mediante revisiones mensuales, ya que con estas acciones podemos provocar que el servicio Cloud, que se caracteriza por ser sencillo y fluido, no lo sea, por ello, lo mejor es que la gestión de un servicio Cloud esté automatizada.

Existen muchos tipos de servicios Cloud y dependiendo del servicio que queramos dar o queramos recibir, deberá tener unas características determinadas. HDDC y SDDC son centros de datos con características diferentes pero ninguno de los dos es mejor ni peor que el otro, simplemente tendremos que elegir cuál de ellos se adapta más a las necesidades de nuestro servicio Cloud.

Debido a la gran cantidad de datos que se ofrecen a través de servicios Cloud, es indispensable tener una figura que nos guíe. El Cloudbroke es este guía cuyo principal propósito es facilitar el acceso a múltiples proveedores de servicios y tipos de Cloud.
