# Free MCBoot
Free McBoot es un método para ejecutar aplicaciones homebrew directamente desde una Memory Card como un cargador independiente.\
No se requieren discos de arranque, ni modchips una vez instalados. Sin embargo, deberá tener un método para instalar FMCB en la Memory Card.


<details>
  <summary>

  ## Preguntas frecuentes de Quick Free McBoot:
  </summary>
  <p>

  ### ¿Qué es FreeMcBoot (también conocido como FMCB)?

  >Free Mcboot es básicamente una forma de explotar su Memory Card PS2.
  >
  >Una vez que tenga este mod instalado en su Memory Card e inserte la misma en su PS2, puede comenzar a instalar programas caseros y liberar el verdadero potencial de su PS2.
  >
  >Una vez que inserte una Memory Card PS2 con Free MCBoot, la PS2 cargará un menú diferente al que normalmente hace.\
  >Este menú se puede configurar para cargar todo tipo de software diferente, pero básicamente le permite ejecutar homebrew, emuladores, cargadores de respaldo, escaladores de gráficos y otras cosas.

  ### ¿Es permanente?

  > No.\
  >FreeMcBoot se instala en una Memory Card de PS2 estándar. Cuando esta Memory Card está conectada a su PS2, entonces su PS2 arranca en la pantalla de inicio de FMCB y se "modifica" funcionalmente.
  >
  >Tan pronto como retire esta Memory Card y reinicie su PS2, se revierte al 100% por completo. Toda la "magia" sucede en la Memory Card de la PS2, por lo que nada de ella es permanente.
  >
  >Los usuarios avanzados pueden incluso instalar FreeMcBoot en el disco duro interno de una PS2 Fat, pero incluso esto se puede deshacer eliminando o formateando el disco duro. 
  >
  > ¡¡¡ Nada sobre FreeMcBoot es permanente. !!!

  ### ¿Funcionará con mi PS2?

  >Free Mcboot funcionará con casi cualquier PS2.
  >
  >|    Modelo PS2    | Soportado o no soportado |
  >|       :---:      |          :---:           |
  >| SPCH-10000/15000 |        Soportado         |
  >|    SPCH-1800x    |        Soportado         |
  >|    SPCH-3xxxx    |        Soportado         |
  >|    SPCH-5xxxx    |        Soportado         |
  >|    SPCH-7xxxx    |        Soportado         |
  >|    SPCH-9xxxx    | Parcialmente soportado*  |
  >
  > \* El número de serie SCPH-9xxxx tiene algunos modelos que son compatibles y otros que no lo son.
  >
  >|                                  Modelo PS2                                  | Soportado o no soportado |
  >|                                     :---:                                    |           :---:          |
  >|                            SPCH-9xx(7C,7D,8A,8B)                             |   Son todos soportados   |
  >|                          SPCH-9xx(8C) con Bios v220                          |   Son todos soportados   |
  >|                          SPCH-9xx(8C) con Bios v230                          |    NO son soportados     |
  >| SPCH-9xx(0A, 0B, 0C, 0D, 1A, 1B, 1C, 1D, 2A, 2B, 2C, 2D, 8D, 9A, 9B, 9C, 9D) |    NO son compatibles    |

  ### ¿Cómo hago que mi PS2 funcione con FreeMcBoot?

  >(Lea a continuación para obtener más detalles)

  ### ¿Puedo jugar copias de seguridad de mis juegos de PS2?

  >Sí.\
  >FMCB le permite cargar copias de seguridad de sus juegos de muchas maneras. Puede grabar copias de seguridad en DVD, en una computadora Windows o Macintosh, simplemente parcheándolas usando el botón [ESR GUI tool](https://www.ps2-home.com/forum/viewtopic.php?f=10&t=15). Este es un programa de un solo clic, que hace que sus archivos de copia de seguridad funcionen con FreeMcBoot, y está disponible para Windows y Macintosh.
  >
  >¡Qué momento para estar vivo!\
  >Los usuarios avanzados también pueden utilizar un software llamado OPL para cargar archivos .iso de PS2 desde una carpeta directamente en su PC, a través de un cable ethernet. Ver [Guía OPL](https://www.ps2-home.com/forum/viewtopic.php?f=50&t=36).\
  >Los usuarios avanzados con Fat PS2s y discos duros internos pueden incluso ripear sus discos al disco duro utilizando un software llamado HDL, y cargarlos a través de OPL sin siquiera tener el disco en la unidad.

  ### NOTA:

  >La carga de copias de seguridad de PS2 es técnicamente posible a través de fuentes USB como thumbdrives y discos duros externos, pero los puertos USB de la PS2 están limitados al protocolo USB 1.1, lo que significa que la velocidad de carga desde fuentes USB es inferior a la mitad de la velocidad de la propia unidad de DVD.\
  >Esto significa que la mayoría de los juegos tendrán saltos de audio, saltos de secuencias FMV y algunos juegos se bloquearán aleatoriamente, o no se podrán reproducir en absoluto desde USB.\
  >¡¡¡No sugerimos a nadie que planee utilizar la carga por USB como fuente principal para la carga de copias de seguridad.!!!

  ### ¿Puedo jugar copias de seguridad de mis juegos de PS1?

  >Sí... más o menos.
  >
  >Lo fácil que sea hacer esto depende del modelo de PS2 que tengas. Si tienes una PS2 FAT es muy difícil. Si tienes una PS2 Slim, es un poco menos difícil.\
  >Siempre requiere la modificación física de la PS2 y está más allá del alcance de estas preguntas frecuentes.
  >
  >Sin embargo, con todo lo dicho, hay un nuevo software disponible llamado POPStarter que esencialmente le permite cargar un archivo .iso PS1 en una unidad USB, o su HD interno si tiene una PS2 FAT, y jugarlo de esta manera. Ver [Guía POPStarter](https://www.ps2-home.com/forum/viewtopic.php?f=19&t=144).\
  >La compatibilidad con este método no es tan alta como modificar físicamente su consola para leer CD-R de copia de seguridad (con modchips), pero es mucho más fácil arrastrar y soltar un archivo que modificar su consola.
  </p>
</details>

<details>
  <summary>

  ## Versiones:
  </summary>
  <p>
  
  ##
  - `Update 2019/04/13: v0.987 (FMCB v1.966) released.` → [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.987%20(FMCB%20v1.966)%20(2019-04-13))
  - `Update 2019/01/14: v0.986 (FMCB v1.966) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.986%20(FMCB%20v1.966)%20(2019-01-14))
  - `Update 2019/01/11: v0.986 (FMCB v1.966) released.`
  - `Update 2019/01/07: v0.985 (FMCB v1.966) released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.985%20(FMCB%20v1.966)%20(2019-01-07))
  - `Update 2018/12/08: v0.985 (FMCB v1.965) released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.985%20(FMCB%20v1.965)%20(2018-12-08))
  - `Update 2018/11/05: v0.984 (FMCB v1.965) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.984%20(FMCB%20v1.965)%20(2018-11-05))
  - `Update 2018/11/03: v0.984 (FMCB v1.965) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.984%20(FMCB%20v1.965)%20(2018-11-03))
  - `Update 2018/10/27: v0.984 (FMCB v1.965) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.984%20(FMCB%20v1.965)%20(2018-10-27))
  - `Update 2018/10/21: v0.984 (FMCB v1.965) released.`
  - `Update 2018/07/22: v0.983 (FMCB v1.964) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.983%20(FMCB%20v1.964)%20(2018-07-22))
  - `Update 2018/07/21: v0.983 (FMCB v1.964) released.`
  - `Update 2018/07/04: v0.983 (FMCB v1.963) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.983%20(FMCB%20v1.963)%20(2018-07-04))
  - `Update 2018/07/03: v0.983 (FMCB v1.963) released.`
  - `Update 2018/06/28: v0.983 (FMCB v1.962) re-released.`
  - `Update 2018/06/20: v0.983 (FMCB v1.962) released.`
  - `Update 2018/06/19: v0.983 (FMCB v1.961) released.`
  - `Update 2018/06/14: v0.982 (FMCB v1.96) released (actualización menor del instalador).`
  - `Update 2018/06/12: v0.981 (FMCB v1.96) released.`
  - `Update 2016/12/16: v0.973 (FMCB v1.953) re-released.`→ [Decargar](https://github.com/usaurioRAWR/ps2RAWR/tree/main/Free%20MCBoot/v0.973%20(FMCB%20v1.953)%20(2016-12-16))
  - `Update 2016/12/15: v0.973 (FMCB v1.953) released.`
  - `Update 2016/06/18: v0.972 (FMCB v1.952) released.`
  - `Update 2016/06/09: v0.972 (FMCB v1.951) released.`
  - `Update 2016/05/21: v0.971 (FMCB v1.951) released.`
  - `Update 2016/01/04: v0.97 (FMCB v1.95) released.`
  - `Update 2013/10/13: v0.96 (FMCB v1.94) released.`
  - `Update 2013/10/13: v0.95 (FMCB v1.93) released.`
  - `Update 2013/08/22: v0.94H (FMCB v1.92) released.`
  - `Update 2013/08/19: v0.94H (FMCB v1.91) released.`
  - `Update 2013/08/17: Beta v0.94D & H released.`
  - `Update 2013/07/20: Beta v0.94C released, corrección de errores menores y actualización de traducción.`
  - `Update 2013/07/16: Beta v0.94B1 released, corrección de errores menores.`
  - `Update 2013/07/14: Beta v0.94B released, corrección de errores menores.`
  - `Update 2013/07/12: Beta v0.94A released, corrección de errores menores y actualización de características.`
  - `Update 2013/07/11 03:21: Añadida una plantilla de traducción.`
  - `Update 2013/07/10: Beta v0.94 released!`
  - `Update 2012/11/04: Beta v0.93B1 released!`
  - `Update 2012/04/07: Beta v0.93B released!`
  - `Update 2011/11/14: Beta v0.93A released! (Actualización tardía)`
  - `Update 2011/10/03: Beta v0.93 released!`
  - `Update 2011/09/20: Beta v0.92 released!`
  - `Update 2011/09/16: Beta v0.91 released!`
  - `Update 2011/09/14: Beta v0.90 released!`
  </p>
</details>




<details>
  <summary>

  ## Fuentes de Información;
  </summary>
  <p>
  
  ### PS2-HOME:

  - [[TUTORIAL] [FMCB] Free McBoot Installation Guide [Noobie Guide] **by Jay-Jay**](https://www.ps2-home.com/forum/viewtopic.php?p=6433#p6433)

  - [[APP] FMCB / FHDB Installer by SP193 **by Jay-Jay**](https://www.ps2-home.com/forum/viewtopic.php?f=11&t=1890)

  - [[DOWNLOAD] FMCB / FHDB "Newbie Packs" **by Jay-Jay**](https://www.ps2-home.com/forum/viewtopic.php?f=11&t=6566)

  - [[FMCB / FHDB] FMCB / FHDB Install - Troubleshooting FAQs **by Jay-Jay**](https://www.ps2-home.com/forum/viewtopic.php?f=96&t=8096)

  ### Espejos del código fuente de GITHUB FMCB:

  - [TnA-Plastic](https://github.com/TnA-Plastic/FreeMcBoot)

  - [Jay-Jay-OPL](https://github.com/Jay-Jay-OPL/FreeMcBoot)
  </p>
</details>



