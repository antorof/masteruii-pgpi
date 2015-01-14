Seminario: Seguridad en redes corporativas. Detectando al intruso.
==================================================================

## ¿Qué elementos de seguridad se pueden integrar en la red corporativa (firewalls, etc)?

Hay muchos elementos elementos que ayudan a la seguridad de una red, los cuales pordrían incluso clasificarse en varios tipos.

#### Prevención
+  Seguridad física
+  Criptografía (protocolos seguros [WPA, IPSec...])
+  Control del acceso ([RADIUS](http://en.wikipedia.org/wiki/RADIUS), VPN)
+  Seguridad perimetral (Firewall, NAT)

#### Deteción
+  Intruder Detection System - [IDS](http://es.wikipedia.org/wiki/Sistema_de_detecci%C3%B3n_de_intrusos)
+  Security information and event management - [SIEMs](http://en.wikipedia.org/wiki/Security_information_and_event_management)

#### Respuesta
+  IRSs (Introducen reglas adicionales en el FW)
+  Políticas y procedimientos 
+  Incident Response Teams

## ¿Es realmente necesario disponer de medidas de seguridad en la red de una empresa?

Es muy importante ya que las brechas en la seguridad pueden tener muchas consecuencias en la empresa.

Si hay un robo de información -por ejemplo-, aparte de comprometer los datos de los clientes, se pierde en imagen y 
en credibilidad. Además, todo esto hace que la empresa pierda dinero.

## Es posible que las medidas de seguridad convencionales no cubran todos los posibles escenarios de riesgos actuales. ¿Considerarías incorporar algún esquema experimental a la red? ¿Cuál?

En cuanto a diferentes arquitecturas de red, hay esquemas en los que se construyen una especie de jerarquías u
organizaciones de equipos que permiten aplicar métodos de identificación y prevención de amenazas.

En el ámbito de la investigación existen nuevas tendencias a la hora de identificar problemas de seguridad,
como el análisis multivariante -que procede de distintas fuentes (tráfico, firewalls, logs, IDSs...)- con el 
problema de que, al tener que manejar un conjunto de datos muy grande, se tarda bastante en realizar dicho 
análisis.

Además, una buena visualización de los distintos datos de los que se dispongan puede ayudar a una persona
a identificar más rapidamente los problemas que puede haber.

Sin embargo, antes de incorporar alguno de estos esquemas y métodos seguramente trataría de investigar más a 
fondo acerca de las ventajas e inconvenientes de cada uno.