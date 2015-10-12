# IntegracionMediosDiagnosticos
Pagina de ejemplo

Lo he añadido por la linea de comandos:
Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos
$ git init
Initialized empty Git repository in D:/Proyectos/git/IntegracionMediosDiagnosticos/.git/

Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos (master)
$ git add .

Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos (master)
$ git commit -m "Subida inicial"
[master (root-commit) 9e8eadb] Subida inicial
 1 file changed, 14 insertions(+)
 create mode 100644 Scripts/IMD_ARQ_CONTINGENCIA.sql

Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos (master)
$ git remote add origin https://github.com/javabuk/IntegracionMediosDiagnosticos

Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos (master)
$ git remote -v
origin  https://github.com/javabuk/IntegracionMediosDiagnosticos (fetch)
origin  https://github.com/javabuk/IntegracionMediosDiagnosticos (push)

Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos (master)
$ git push origin master
remote: Repository not found.
fatal: repository 'https://github.com/javabuk/IntegracionMediosDiagnosticos/' not found

Jorge@AnaRosa MINGW64 /d/Proyectos/git/IntegracionMediosDiagnosticos (master)
$ git push origin master
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 491 bytes | 0 bytes/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/javabuk/IntegracionMediosDiagnosticos
 * [new branch]      master -> master


