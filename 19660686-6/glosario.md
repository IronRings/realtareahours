# Glosario

### A) Control de versiones (VC):
Es la gestion de cambios realizados sobre productos, sean documentos, programas, sitios web, etc. [1]
### B) Control de versiones distribuido (DVC)
Es un tipo de control de versiones donde cada revision esta almacenada en un sistema de control de versiones distribuido. [2]
### C) Repositorio remoto y repositorio local:
Un repositorio remoto es aquel que esta alojado en algun servidor, mientras que un repositorio local esta alojado en un equipo fisico. [3]
### D) *Working Copy*
Es el repositorio local donde se hacen los cambios para ser devueltos al repositorio remoto. [4]
### E) *Staging Area*
Es donde se guarda la informacion sobre que cambios se van a hacer en el siguiente *commit*. [5]
### F) *Stage Changes*
Es agregar cambios a la *Staging Area* [5]
### G) *Commit Changes*
Es subir todos los cambios de la *Staging Area* al repositiorio remoto.[5]
### H) *Commit*
Tambien llamado "*revision*", es un set de cambios individuales a un archivo o set de archivos, siendo el equivalente a guardar un archivo, excepto que le guarda un ID unico a cada cambio hecho. Suele llevar un corto mensaje describiendo los cambios hechos. [3]
### I) *clone*
Es una copia del repositorio ubicada en el computador en vez de en algun servidor de algun sitio.[3]
### J) *pull*
Es "traer" los cambios hechos a algun archivo de algun repositiorio a la copia local de uno, para que este actualizada.[3]
### K) *push*
Es enviar los cambios hechos a algun repositiorio remoto.[3]
### L) *fetch*
Es conseguir los cambios mas recientes de algun repositiorio sin tener que juntarlos. Una vez que los conseguiste puedes compararlos con tus branches locales.[3]
### M) *merge*
Es juntar los cambios de alguna branch, y aplicarlos a otra.[3]
### N) *status*
Es un tipo de checkeo del repositorio y su estado.[3]
### O) *log*
Es un registro de cada *commit* hecho [6]
### P) *checkout*
Actualiza los archivos de alguna branch para que estos sean los mismos de la branch especificada.[7]
### Q) Branch
Es una version paralela del repositorio. Se ubica dentro del repositorio, pero no afecta la "*master branch*", permitientote trabajar libremente sin interrumpir la version principal.[3]
### R) Tag
Es poner etiquetas en el historial para denotar puntos especificos en la historia del repositorio como importantes. [8]
---
## Source:
```
[1] https://es.wikipedia.org/wiki/Version_control
[2] https://es.wikipedia.org/wiki/Distributed_version_control
[3] https://help.github.com/en/articles/github-glossary
[4] https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms
[5] https://dev.to/sublimegeek/git-staging-area-explained-like-im-five-1anh
[6] https://git-scm.com/docs/git-log
[7] https://git-scm.com/docs/git-checkout
[8] https://git-scm.com/book/en/v2/Git-Basics-Tagging
```