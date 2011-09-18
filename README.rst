=====================================
 Chile: "Códigos territoriales (Región, Provincia, Comuna)"
=====================================
:Web:         Ver [LACOSOX2010]_ para una descripción más detallada
:Autor:       Gustavo Lacoste <gustavo@lacosox.org>
:Fecha:       $Date: 2011-09-14 14:00:00 $
:Revisión:    $Revision: 01 $
:Lincencia:   GPLV3
:Descripción: Base de datos en diferentes formatos de los códigos territoriales chilenos, útil para implementarlo en proyectos informáticos Chilenos.

Acerca del proyecto
=====================================

Este proyecto contiene la base de datos de los códigos territoriales para Chile 
(actualizados a la fecha 13/09/2011), la base de datos está basada en el último 
documento oficial [MININT2010]_ publicado por el *"Sistema nacional de 
información municipal Chileno"* (SINIM) [SINIM2011]_ el cual a su vez se basa en
el Decreto Exento Nº 817 del Ministerio del Interior, publicado en el Diario 
Oficial el día 26 de Marzo de 2010 . 

Actualmente puedes encontrar aquí la base de datos en diversos formatos 
(todos sincronizados con la única fuente de datos oficial). La base de datos es 
generada por el autor, por lo tanto, este no es un proyecto oficial asociado a 
alguna entidad del estado; es decir, no se da ninguna garantía, pero funciona.




Formatos disponibles
=====================================
La BD la puedes bajar en los formatos se describen en la tabla siguiente:

+-----------------------+----------------------+------+-----------------+
|     **Formato**       |     **Ideal para**   |**IR**| **Codificación**|
+-----------------------+----------------------+------+-----------------+
| MySQL5_InnoDB_utf8    |    ``phpMyAdmin3``   | Sí   |      UTF-8      |
+-----------------------+----------------------+------+-----------------+
| PosgreSQL_InnoDB_utf8 |     ``PosgreSQL``    | Sí   |      UTF-8      |
+-----------------------+----------------------+------+-----------------+
|      YAML_utf8        | ``PHP Doctrine ORM`` | Sí   |      UTF-8      |
+-----------------------+----------------------+------+-----------------+
|      JSON_utf8        |   ``AJAX Response``  | Sí   |      UTF-8      |
+-----------------------+----------------------+------+-----------------+

IR= Integridad referencial

.. [LACOSOX2010] http://www.lacosox.org/?q=codigo_territorial_sql_Regiones_provincias_comunas_de_Chile

.. [MININT2010] http://www.sinim.cl/archivos/centro_descargas/modificacion_instructivo_pres_codigos.pdf

.. [SINIM2011] http://www.sinim.cl/