_1/4/2026_: Un grupo intentó monitorear las frecuencias de la repetidora local en el cerro. Aprendieron a usar el software para sintonizar las frecuencias y lograron recibir y grabar algunos mensajes. Otro grupo se quedó viendo la presentación del profe y otro grupo intentó armar un servidor VPN para conectarse por ssh a la compu, pero como no tenemos una IP pública hubo que usar un servicio externo.

_7/4/2026_: Aprendí a usar el control de rotores de gpredict. Está hecho para interactuar con servidores de hamlib creados por el comando rotctld. Solo requiere que le indiquen en que dirección y puerto está el servidor. rotctld puede conectarse a rotores a través de TCP/IP o de puertos seriales. La cuestión es que el aparato que controla realmente el rotor tiene que implementar alguno de los protocolos de comunicación especificados en la lista de rotctld. Creo que el más fácil sería GS-232, ya encontré algunos ejemplos de código. Habría que probarlo en algún arduino.

_10/4/2026_: Escuchamos frecuencias de aviones usando la antena dipolo.

_15/4/2026_: Utilizamos una antena larga hecha con cable sostenida por el mastil de la bandera para escuchar frecuencias lejanas usando las condiciones de la ionosfera del atardecer. Como no andaba la entrada de menor frecuencia del sdr usamos un circuito que le agregaba 150 kHz para poder convertir la señal a digital y luego sacarle esa frecuencia agregada en la computadora. Salió bastante bien, pudimos escuchar un cubano hablando por la radio y la música de un koto japonés.

_22/4/2026_: Me puse a probar el programa Xnex2c. Dentro de todo anda bien, pero el modelado de las antenas es más artesanal, no tiene una interfaz gráfica para eso sino que usa entradas en un formulario que luego se puede editar. Por otra parte, es muy bueno para la simulación. Te permite hacer un montón de estudios y gráficos, y se puede cambiar todo. También nos pusimos a hacer pruebas con la antena "magnetic loop" para aprender como funciona y como se usa.

_29/4/2026_: Hoy armamos una antena dipolo y nos la pusimos a probar con el NanoVNA. Pudimos captar algunas señales, pero los marcos de las ventanas interferían. Ayer fue mi cumpleños.

_2/5/2026_: Intenté armar un código para que el Arduino pueda recibir y responder a compandos de rotctld. Dentro de todo funcionó bien, usé el protocolo GS-232A. El problema es que gpredict no envió ningún comando de escritura aún cuando le daba la orden de que moviera la antena, solo mandaba comandos de lectura.

_6/4/2026_: Hoy hubo sonda y no hice nada.
