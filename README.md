# SeguridadK8s
Bienvenidos a mi repositorio de Trabajo de Fin de Grado sobre seguridad de Kubernetes. 
El objetivo principal de este TFG es concienciar sobre la necesidad de implementar medidas de seguridad en Kubernetes y mostrar las diferentes herramientas disponibles para lograrlo. Además, se proporciona una visión detallada sobre las diferentes partes de Kubernetes que son necesarias proteger. 

En este repositorio, encontrarás los detalles del proyecto, como la metodología empleada, las herramientas de seguridad evaluadas, ejemplos prácticos y comparadas y los resultados obtenidos. 

## Estrutura del proyecto
El codigo esta divido en carpetas donde se encuentran los ejemplos para cada una de las herramientas que se van a evaluar. 
En el .docx se encontrara la memoria del TFG donde aparecera detalladamente las tablas comparativas de las herramientas asi la organización del proyecto. 


## Herramientas selecionadas

### Cluster Layer 
-
A nivel de cluster detectamos diferentes aspectos a tener en cuenta para asegurar la seguridad de los clusters:

 *Network Policies*
  - Network Policies Kubernetes
  - Isti9o
  
 *Compliance*
 
 - Kube-bench 
 - Kube-hunter
 
 *Secrets Management*
 
 - Vault 
 - Sealed Secrets 
 
 *Policy Management*
 - Kyverno
 1 ejemplo por cada tipo de politica
   - Generate 
   - Validate
   - Mutate 
   - Verify Images
 
 - GateKeeper OPA
 
### Container runtime layer 
-
A nivel de contenedor detectamos diferentes aspectos a tener en cuenta para asegurar la seguridad de los clusters:

*Image Registry*

*Image Scanning*

- Trivy
- Clair => Error
- Anchore

*Image Signing*

- NOTARY
- ... ¿??¿ No enc uentro comparativa

*Runtime protection*

- Enforcement
  - Sysdig FecureR
- Auditing
  - Falco
  - ...
 

### Code Layer 
-
*Infraestructure as Code*
- Terraform 
- Snyk 

##Implementación 
 - Con las herramientas selecionadas


## DUDAS
-
- Manual de estrucción unificado de todas las herramientas
