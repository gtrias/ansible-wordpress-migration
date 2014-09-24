1 - Definir parella de source i target. Per cada un d'ells
        - Definir accesos a base de dades. Si no tenim access a base de dades poder definir un arxiu .sql manualment
        - Definir accesos SSH o FTP
        - Definir domini

2 - Enviar arxius de source a target (FTP o SSH)

4 - Canviar camps de la base de dades a l'arxiu wp-config.php (utilitzar plantilla?)

4 - Baixar dump base de dades configurada a target

5 - Fer cercar i reemplacar del dump de source: s/domini_source/domini_target/g

6 - Importar dump modificat a target ( si no es pot fer automaticament deixar l'arxiu modificat accessible per poder fer-ho manualment )
