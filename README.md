
00 - Crear Tabla TMP_SBS_ANEXO6_CFZ.sql
00 - Crear Tabla TMP_SBS_ANEXO6.sql
Dos tablas temporales
	- Importar los datos de las cartas fianzas
	- Importar los ajustes del anexo 6

01 - Para Subir a temporal - ANEXO_6_CFZ.xlsx (Plantilla)

02 - Validacion Manual CFZ.sql

/*Debe correr despues de los procesos BDC01 y SBS_ANEXO6
03 - ANEXO_6_ENVIAR_COTY_CON_CFZ.sql
	Un script para extraer la informacion formateada de la tabla SBS_ANEXO6 con TMP_SBS_ANEXO6_CFZ, numeracion continua

04 - Para Subir a temporal - TMP_SBS_ANEXO6_CFZ.xlsx
	Subir el anexo 6 con los ajustes ajustes

05 - ANEXO_6_FINAL_CONCATENADO.sql
	Reporta el concatenado final

05 - ANEXO_6_FINAL_SEPARADO.sql
	Para Validaciones Finales