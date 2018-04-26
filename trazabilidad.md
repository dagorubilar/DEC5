# Matríz Trazabilidad Funcionalidades DEC5


| ID  	  	| Servicios  		 | 
|:-------------: |:---------------:|
| 1      | Modelo DEC5		 |       
| 2     | autentia-ident2.cgi|          
| 3 | autentia-audit.cgi| 
| 4      | wsValidaRut/index.php?wsdl|       
| 5      | autentia-admusr4.cgi|          
| 6 | autentia-atributo.cgi|
| 7      | dec4_wsdl/wsCallTran.php|       
| 8      | autentia-persona.cgi|          
| 9 | autentia-instit.cgi| 
| 10      | autentia-docs4.cgi|       
| 11      | autentia-patron3.cgi|          
| 12 | autentia-perfil.cgi|
| 13      | Elastic		 |       
| 14      | aws-sign|          
| 15 | Signer | 
| 16      | pdf-stamper|       
| 17     | pdf-signer|          
| 18 | image-info|
| 19      | generator |       
| 20     | x509v3 |          
| 21 | Append | 
| 22      | external-pdf-signature/step-1|       
| 23      | external-pdf-signature/step-2|          
| 24 | xml-signature/external/step-1|   
| 25 | xml-signature/external/step-2|
| 26      | api/v1/verify/session |       
| 27      | firma-web_dev/rest/session/data |          
| 28 | firma-web_dev/rest/certificado/instalar | 
| 29      | firma-web_dev/rest/session/firma|       
| 30      | firma-web_dev/rest/session/certificado|          
| 31 | firma-web_dev/rest/firmar/verificarAcceso|       



| Módulo| Funcionalidad | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 |15 | 
|:---:|:---:|:---:	|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|**login**|***ingreso clave*** |-|X|-|-|X|-|-|X|-|-|-|-|-|-|-|
| |***Ingreso Huella***|-|-|X|-|X|-|-|X|-|-|-|-|-|-|-|
| |***Olvidé mi Clave*** |-|X|-|-|X|-|-|-|-|-|-|-|-|-|-|
|**Crear Cuenta**| ***Presionar crear cuenta***|-|-|-|X|X|-|-|-|-|-|-|-|-|-|-|
|**Editar Cuenta**|***Editar Datos personales*** |-|-|-|-|-|X|-|-|-|-|-|-|-|-|-|
| |***Registro Certificado HSM*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Mi portal**|***Shortcuts (Contadores)*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Mensahes*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Mis Documentos**|***Al presionar Mis Documentos***|X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda General*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Búsqueda por Carpetas*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Filtros Avanzados*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Estados*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Fecha*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Tipo Documento*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Vincular*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar a*** |X|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| | ***Etiquetar*** |X|-|-|-|-|-|-|-|-|-|-|-|X|-|-|
| |***Cartola*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Descargar*** |-|-|-|-|-|-|-|-|-|X|-|-|-|-|-|
| |***Compartir*** |X|-|-|-|X|-|-|-|-|-|-|-|-|-|-|
| |***Ocultar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Mostrar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Selección de Instituciones*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Acciones de Firma**|***Firmar Pin y Huella*** |-|-|X|-|-|-|-|-|-|X|X|-|-|-|X|
| | ***Firmar HSM PDF*** |-|-|X|-|-|-|-|-|-|X|X|-|-|X|-|
| | ***Firmar HSM XML*** |-|-|X|-|-|-|-|-|-|X|X|-|-|X|-|
| |***Firmar Token PDF*** |-|-|X|-|-|-|-|-|-|X|X|-|-|X|-|
| |***Firmar Token XML*** |-|-|X|-|-|-|-|-|-|X|X|-|-|X|-|
| |***Rechazar*** |-|-|X|-|-|-|-|-|-|X|X|-|-|-|X|
| |***Visar*** |-|-|X|-|-|-|-|-|-|X|X|-|-|-|X|
|**Aplicaciones**| ***Papelera*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Reportería*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| | ***Firma Masiva con PIN Y Huella*** |X|-|X|-|-|-|-|-|-|X|X|-|-|-|X|
| |***Firma con etoken***  |X|-|X|-|-|-|-|-|-|X|X|-|-|X|-|
| |***Firma con hsm*** |X|-|X|-|-|-|-|-|-|X|X|-|-|X|-|
|**Mantenedor de Usuarios**|***Crear Rol*** |X|-|-|-|X|-|-|-|-|-|-|-|-|-|-|
| |***Asignar Usuarios a un rol*** |X|-|-|-|X|-|-|-|-|-|-|-|-|-|-|
| |***Deshabilitar Usuarios de un Rol*** |X|-|-|-|X|-|-|-|-|-|-|-|-|-|-|
| |***Exportar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Mostrar Inhabilitados*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Nombre o Rut*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Roles*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Estados*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Eliminar Roles (solo superadmin)*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Tipos de Documentos**|***Crear*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Importar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Exportar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Ocultar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Clonar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Crear Plantillas DEC*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar Plantillas DEC*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Crear Plantillas PDF*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar Plantillas PDF*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación rol creador*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación Firmantes acción Firmar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación Firmantes acción Visar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación Firmantes acción Compartir*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Permitir agregar más firmantes*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar etiquetas*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Configurar Niveles de Seguridad*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar Descripción del tipo de Documento*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Documentos**| ***Crear desde archivo*** |X|-|-|-|-|-|-|-|-|X|-|-|X|-|-|
| |***Crear desde Plantilla DEC*** |X|-|-|-|-|-|-|-|-|X|-|-|X|-|-|
| |***Crear desde Plantilla PDF*** |X|-|-|-|-|-|-|-|-|X|-|-|X|-|-|
| |***Agregar Firmantes*** |X|-|-|-|-|-|-|-|-|X|-|-|X|-|-|
| |***Agregar Comentarios*** |X|-|-|-|-|-|-|-|-|X|-|-|X|-|-|
| |***Buscar Tipo de Documentos*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Plantilla de Correos**| ***Crear*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Clonar*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Enrolar Usuarios**| ***Enrolar Usuarios*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Instituciones**| ***Crear*** |X|-|-|-|-|-|-|X|-|-|-|-|-|-|-|
| |***Editar*** |X|-|-|-|-|-|-|X|-|-|-|-|-|-|-|
| |***Deshabilitar institución*** |X|-|-|-|-|-|-|X|-|-|-|-|-|-|-|
| |***Habilitar Institución*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Incluir Instituciones deshabilitadas*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|

| Módulo| Funcionalidad | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 |30 | 31| 
|:---:|:---:|:---:	|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:--:|
|**login**|***ingreso clave*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Ingreso Huella***|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Olvidé mi Clave*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Crear Cuenta**| ***Presionar crear cuenta***|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Editar Cuenta**|***Editar Datos personales*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Registro Certificado HSM*** |-|-|-|-|-|-|-|-|-|-|-|-|X|-|-|-|
| **Mi portal**|***Shortcuts (Contadores)*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Mensahes*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Mis Documentos**|***Al presionar Mis Documentos***|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda General*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Carpetas*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Filtros Avanzados*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Estados*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Fecha*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Tipo Documento*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Vincular*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar a*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| | ***Etiquetar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Cartola*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Descargar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Compartir*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Ocultar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Mostrar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Selección de Instituciones*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Acciones de Firma**|***Firmar Pin y Huella*** |X|X|X|X|-|-|-|-|-|-|-|-|-|-|-|-|
| | ***Firmar HSM PDF*** |X|X|X|-|X|X|X|X|-|-|X|X|-|X|X|X|
| | ***Firmar HSM XML*** |X|X|X|-|X|X|-|-|X|X|X|X|-|X|X|X|
| |***Firmar Token PDF*** |X|X|X|-|X|X|X|X|-|-|X|-|-|-|-|-|
| |***Firmar Token XML*** |X|X|X|-|X|X|-|-|X|X|X|-|-|-|-|-|
| |***Rechazar*** |X|X|X|X|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Visar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Aplicaciones**| ***Papelera*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Reportería*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| | ***Firma Masiva con PIN Y Huella*** |X|X|X|X|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Firma con etoken***  |X|X|X|-|X|X|X|X|-|-|X|-|-|-|-|-|
| |***Firma con hsm*** |X|X|X|-|X|X|X|X|-|-|X|X|-|X|X|X|
|**Mantenedor de Usuarios**|***Crear Rol*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignar Usuarios a un rol*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Deshabilitar Usuarios de un Rol*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Exportar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Mostrar Inhabilitados*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Nombre o Rut*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Roles*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Búsqueda por Estados*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Eliminar Roles (solo superadmin)*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Tipos de Documentos**|***Crear*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Importar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Exportar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Ocultar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Clonar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Crear Plantillas DEC*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar Plantillas DEC*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Crear Plantillas PDF*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar Plantillas PDF*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación rol creador*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación Firmantes acción Firmar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación Firmantes acción Visar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Asignación Firmantes acción Compartir*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Permitir agregar más firmantes*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar etiquetas*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Configurar Niveles de Seguridad*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar Descripción del tipo de Documento*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Documentos**| ***Crear desde archivo*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Crear desde Plantilla DEC*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Crear desde Plantilla PDF*** |X|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar Firmantes*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Agregar Comentarios*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Buscar Tipo de Documentos*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Plantilla de Correos**| ***Crear*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Clonar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Enrolar Usuarios**| ***Enrolar Usuarios*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|**Instituciones**| ***Crear*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Editar*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Deshabilitar institución*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Habilitar Institución*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| |***Incluir Instituciones deshabilitadas*** |-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|

