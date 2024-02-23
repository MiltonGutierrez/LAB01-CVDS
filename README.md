# LABORATORIO 1- INTRODUCCIÓN GIT
### ESCUELA COLOMBIANA DE INGENIERÍA
#### CICLOS DE VIDA DE DESARROLLO DE SOFTWARE

## Miembros:
* Milton Andres Gutierrez Lopez
* Jhon Sebastian Sosa Muñoz
## PARTE I. - CREANDO REPOSITORIOS
Trabajo en pareja (2 integrantes):
1. Cada integrante,crear una cuenta en GitHub.
En una de las doscuentas,cree un nuevo repositorio llamado:cvds-lab1-[].
Invite al usuario del otro integrante como colaborador de dicho proyecto.

Creación del repo:


![Image][1]



2. (Integrante 1) Cree una directorio(carpeta)con los siguientes archivos:
libro.txt
Se realiza la creación del repositorio local y posteriormente se añade la rama remota.
![Image2][2]
Se crea el archivo libros.txt con los nombres de los dos integrantes
![Image3][3]
4. (Integrante 1)Haga ‘push’ del proyecto recién clonado al nuevo repositorio.
git push URL_REPOSITORIO master.


**Se realizo este paso conjunto al siguiente**

4. (Integrante 1) Agregue al libro,como autores, losintegrantes de la pareja (sólo el primer nombre). Agregue loscambios para elsiguiente commit,
haga commit, y haga ‘push’ de dichoscommits:
![Image4][4]
![Image5][5]
5. (Integrantes 1 y 2) Revisen a través delcliente Web de GitHub, que el documento haya sido actualizado.
![Image5][6]
6. (Integrante 2) Clone el proyecto actualizado:

git clone URL_REPOSITORIO
![Image16][16]

7. (Integrante 2) Agregue los autores de su Pareja al libro (sólo el primer nombre). Agregue loscambios para elsiguiente commit, haga commit, y haga
‘push’ de dichoscommits:
Se obvian los detalles de add y commit.
![Image7][7]
9. (Integrante 1) Obtenga los‘commits’ realizados por la pareja anterior, y revise que los mismos hayan sido aplicados al documento.
git pull URL_REPOSITORIO master
![Image8][8]
Se añadieron dos lineas:
![Image9][9]
10. Utilice en comando gitk para verificar el historial de cambiossobre el repositorio.
![Image10][10]
11. (Integrantes 1 y 2 al tiempo)
El integrante 1 removio la ultima linea, mientras que el integrante 2 añadio dos lineas.
**Resultado de Milton:**


![Image11][11]


**Resultado de Jhon**


![Image12][12]


**Pasos utilizados para arreglar los problemas:**


![Image13][13]
![Image14][14]
![Image15][15]



[1]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/1.png
[2]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/2.png
[3]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/3.png
[4]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/4.png
[5]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/5.png
[6]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/6.png
[7]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/7.png
[8]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/8.png
[9]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/9.png
[10]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/10.png
[11]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/11.png
[12]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/12.png
[13]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/13.png
[14]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/14.png
[15]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/15.png
[16]: https://github.com/MiltonGutierrez/LAB01-CVDS/blob/master/images/16.png
