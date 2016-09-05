# Dashboard-Diez

## Documentación 

..*[Casos de Uso](http://everis.homelinux.com:8090/owncloud/s/SBfqWBIKWDQQ1Lf)
..*[DDR](http://everis.homelinux.com:8090/owncloud/s/UY0TTioRFZhrb1B)
..*[DDS](http://everis.homelinux.com:8090/owncloud/s/Q9fQk2ugGIqoxZe)
---
+ Estándares Base de Datos | ![Base de Datos](http://everis.homelinux.com:8090/owncloud/s/PcesziLdhrvDmUh) |
+ Estándares Creación de Usuarios | ![Creacion usuarios](http://everis.homelinux.com:8090/owncloud/s/XnxtOskeDA370R1) |


## Baseline Sistema Cambios 390

| Herramienta     | Comentario                                                           | Evidencias                          | 
|:---------------:|:---------------------------------------------------------------------|:-----------------------------------:|
| SonarQube 6     | El código del aplicativo fue expuesto a las pruebas de la herramienta SonarQube versión 6, tomando como referencia de satisfactorio un 10% o menos de error, cero bugs nuevos y cero vulnerabilidades (reglas preestablecidas con el cliente). Tras realizar el análisis del código, con base en los resultados que se muestran en la sección de evidencias, el resultado fue “aprobado”. | ![SonarQube 6](https://drive.google.com/uc?export=view&id=0B-qMuzIV-omPQ0pJbFFKeE5aeGs "SonarQube 6")|
| SonarQube 4     | El código del aplicativo fue expuesto a las pruebas de la herramienta SonarQube versión 4. | ![SonarQube 4](https://drive.google.com/uc?export=view&id=0B-qMuzIV-omPaG50djlsR2tnbEE "SonarQube 4")|
| FindBugs        | El código del aplicativo fue expuesto a las pruebas de la herramienta FindBugs en Eclipse Indigo.
Tras realizar el análisis del código, fueron arrojadas 35 advertencias clasificadas por su riesgo, de las cuales 4 son altamente riesgosas, y se muestran a continuación en la sección de evidencias. | ![FindBugs](https://drive.google.com/uc?export=view&id=0B-qMuzIV-omPRFJrT3pyT0dJRkU "FindBugs")|
| Kali Linux      | Se usó la herramienta OWASP ZAP para encontrar las vulnerabilidades del aplicativo a las que se encuentra expuesto. Tras terminar el ataque del aplicativo (el cual se montó en nuestro localhost desde una máquina virtual con el objetivo de poder ser atacado), la herramienta arrojó 5 alertas de nivel de riesgo mediano y bajo, mostradas en la sección de evidencias. | ![Kali Linux](https://drive.google.com/uc?export=view&id=0B-qMuzIV-omPUFAtcnFPTlpnbVU "Kali Linux")|


