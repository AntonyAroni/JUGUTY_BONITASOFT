
### 3.0 PROCESO DE GESTIÓN SEGUIMIENTO Y MONITEOREO DE BECARIOS
Este proceso describe el flujo de trabajo para la evaluación de informes, involucrando a dos actores principales: el Coordinador de Becas y el Analista de Becas. El proceso abarca tres flujos principales: el registro del informe, la revisión del informe y la evaluación del progreso.
![image](https://github.com/user-attachments/assets/a7f74ccf-982d-4b3c-957b-4cd365b2fee5)

#### ACTORES INVOLUCRADOS
1. Usuario Solicitante
2. Registrador
3. Evaluador
4. Personal de Seguimiento
#### FLUJO DEL PROCESO
1. Presentar Informe
   * Actor: Usuario Solicitante
   * Descripción: Usuario Solicitante es el iniciador del proceso el cual presenta los documentos con los datos mediante un formulario, este pobrá ser recibido o rechazado según su completitud
   * Contrato:
       * Nombres
       * Apellidos
       * Correo
       * Numero Telefonico
       * Rol
         
    * Formulario:
      
      ![image](https://github.com/user-attachments/assets/4618faa7-8ae3-46ea-b9fc-660450c4577d)
      
    * API REST:
      
      ![image](https://github.com/user-attachments/assets/93b8c222-6f84-4f20-a42b-7ce564b3a867)
 

         
2. Registrar Informe
   * Actor: Registrador
   * Descripción: El Coordinador de Becas registra el informe en el sistema si este posee los documentos en orden, más no revisa el contenido de este que es entregado por el actor Solicitante. Si el informe no es conforme, se devuelve para corrección.
   * Contrato:
       * Fecha
       * Usuario
       * Estado
       * Comentarios
       * Documentos Adjuntos
    * Formulario:
      
      ![image](https://github.com/user-attachments/assets/ca4c277c-ab8f-4d19-9f79-069e88e3f82c)

    * API REST:
    
     ![image](https://github.com/user-attachments/assets/67609fba-7fb7-4752-848e-1f8d6a171904)


         
3. Revisión del informe
   * Actor: Evaluador
   * Descripción: El Analista de Becas revisa el informe para verificar su conformidad. Si el informe requiere una evaluación más profunda, se procede a la evaluación del progreso.
   * Contrato:
       * Fecha
       * Estado
       * Nombre del Informe
       * Resultados
       * ComentariosInforme
       * DocumentosAdjuntos
    * Formulario
      
      ![image](https://github.com/user-attachments/assets/ea1fba55-829b-438e-9e96-599f9d53d742)

         
4. Evaluación del progreso
   * Actor: Personal de Seguimiento
   * Descripción: Si se requiere, el Personal de Seguimiento realiza una evaluación del progreso. Dependiendo del resultado, el informe puede ser aprobado o devuelto para mejoras.
   * Contrato:
       * Fecha Incio
       * Usuario
       * Documentos Adjuntos
       * Estado de seguimiento
       * Resgistro de Revisiones previas
       * Comentarios
    * Formulario:
      
      ![image](https://github.com/user-attachments/assets/14ebed6a-0032-4c9d-8fc5-cae4fadd23cc)



