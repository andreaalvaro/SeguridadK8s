# SeguridadK8s
Bienvenidos a mi repositorio de Trabajo de Fin de Grado sobre seguridad de Kubernetes. 
El objetivo principal de este TFG es concienciar sobre la necesidad de implementar medidas de seguridad en Kubernetes y mostrar las diferentes herramientas disponibles para lograrlo. Además, se proporciona una visión detallada sobre las diferentes partes de Kubernetes que son necesarias proteger.  Este proyecto se hace en colaboracion con NTTDATA

Se centrara principalmente en la protecion de runtime (Falco, Sysdig Secure, Red Hat StackRox)

En este repositorio, encontrarás los detalles del proyecto, como la metodología empleada, las herramientas de seguridad evaluadas, ejemplos prácticos y comparadas y los resultados obtenidos. 

## Estrutura del proyecto
En el .docx se encontrara la memoria del TFG donde aparecera detalladamente las tablas comparativas de las herramientas asi la organización del proyecto. 
La guia de instalación de las herrameintas principales se encuentra en un documento .pdf 
Ademas se divide cada una de las herramientas en carpetas donde se encuentra el codigo de los ejemplos utilizados durante el proyecto para realizar las comaprativas. 

## Herramientas selecionadas

### Cluster Layer 
A nivel de cluster detectamos diferentes aspectos a tener en cuenta para asegurar la seguridad de los clusters:

 *Network Policies*
  - Network Policies Kubernetes
  - Istio
  
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
A nivel de contenedor detectamos diferentes aspectos a tener en cuenta para asegurar la seguridad de los clusters:

*Image Registry* 
- Harbor

*Image Scanning*

- Trivy
- Clair

*Image Signing*

- NOTARY

*Runtime protection*

- Enforcement
  - Sysdig Secure
- Auditing
  - Falco
 
### Code Layer 
Durante este proyecto no se abordara este nivel de seguridad.
*Infraestructure as Code*
- Terraform 
- Snyk 

## Implementación 
 - Con las herramientas selecionadas

## Guía de Instalación para macOS
Se presenta una guia de instalación para instalar las herramientas mencionadas en la memoria del PFG. Esta guia de instalacion permite tener todas las herramientas minimas en un documento permitiendo asi mayor rapidez a la hora de instalar.
