# SeguridadK8s
Bienvenidos a mi repositorio de Trabajo de Fin de Grado sobre seguridad de Kubernetes. 
El objetivo principal de este TFG es concienciar sobre la necesidad de implementar medidas de seguridad en Kubernetes y mostrar las diferentes herramientas disponibles para lograrlo. Además, se proporciona una visión detallada sobre las diferentes partes de Kubernetes que son necesarias proteger. 

En este repositorio, encontrarás los detalles del proyecto, como la metodología empleada, las herramientas de seguridad evaluadas, ejemplos prácticos y comparadas y los resultados obtenidos. 

## Estrutura del proyecto
El codigo esta divido en carpetas donde se encuentran los ejemplos para cada una de las herramientas que se van a evaluar. 
En el .docx se encontrara la memoria del TFG donde aparecera detalladamente las tablas comparativas de las herramientas asi la organización del proyecto. 


## Herramientas selecionadas

### Cluster Layer 
A nivel de cluster detectamos diferentes aspectos a tener en cuenta para asegurar la seguridad de los clusters:

 *Network Policies*
  - 
  
 *Compliance*
 
 - Kube-bench 
 - Kube-hunter
 
 *Secrets Management*
 
 - Vault 
 - Sealed Secrets 
 
 *Policy Management*
 - Kyverno
 - GateKeeper OPA
 
### Container runtime layer 

A nivel de contenedor detectamos diferentes aspectos a tener en cuenta para asegurar la seguridad de los clusters:

*Image Registry*
- Harbor
- ..
-... 

*Image Scanning*

- Trivy
- Clair
- Anchore ¿? O selecionar otro?DUDA

*Image Signing*

- NOTARY
- ...

*Runtime protection*

- Enforcement
  - ...
- Auditing
  - Falco
  - ...
  


### Code Layer 

*Infraestructure as Code*
- Terraform 
- Snyk 

---- NECESARIO MAS HERRAMIENTAS - Sonarqube si da tiempo


## DUDAS

- Donde introducir ISTIO ? 
- HArbor ? Buscar otros para comparar
- Manual de estrucción unificado de todas las herramientas
