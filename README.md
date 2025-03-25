
ruso3@Alisson2512 MINGW64 ~
$ cd '/c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen'

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen
$ git clone git@github.com:abarrero1358/Barrero_AndresFelipe_nov24.git
Cloning into 'Barrero_AndresFelipe_nov24'...
Enter passphrase for key '/c/Users/ruso3/.ssh/id_ed25519':
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen
$ ll
total 988
-rw-r--r-- 1 ruso3 197617 319808 Mar 22 01:28 '1 Trimestre - Prueba teórica_ Entornos de Desarrollo - PER 12736 - Septiembre 2024.pdf'
-rw-r--r-- 1 ruso3 197617 660630 Nov 25 16:12  202411_EjercicioPractico_EEDD.pdf
drwxr-xr-x 1 ruso3 197617      0 Mar 25 16:59  Barrero_AndresFelipe_nov24/
-rw-r--r-- 1 ruso3 197617  21823 Mar 24 20:38  Soluciones_GitHub.docx

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen
$ cd Barrero_AndresFelipe_nov24/

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ ll
total 1
-rw-r--r-- 1 ruso3 197617 28 Mar 25 16:59 README.md

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ mkdir src docs assets miConfiguracionPersonal

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ touch src/index.html assets/logo.png

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ touch .gitignore

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ code .gitignore

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git push origin main
Enter passphrase for key '/c/Users/ruso3/.ssh/id_ed25519':
Everything up-to-date

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        assets/
        src/

nothing added to commit but untracked files present (use "git add" to track)

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git push origin main
Enter passphrase for key '/c/Users/ruso3/.ssh/id_ed25519':
Everything up-to-date

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        assets/
        src/

nothing added to commit but untracked files present (use "git add" to track)

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ ll
total 1
-rw-r--r-- 1 ruso3 197617 28 Mar 25 16:59 README.md
drwxr-xr-x 1 ruso3 197617  0 Mar 25 17:03 assets/
drwxr-xr-x 1 ruso3 197617  0 Mar 25 17:03 docs/
drwxr-xr-x 1 ruso3 197617  0 Mar 25 17:02 miConfiguracionPersonal/
drwxr-xr-x 1 ruso3 197617  0 Mar 25 17:03 src/

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        assets/
        src/

nothing added to commit but untracked files present (use "git add" to track)

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git add .

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git commit -m "Agregado .gitignore, assets y src"
[main 0b6756b] Agregado .gitignore, assets y src
 3 files changed, 5 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 assets/logo.png
 create mode 100644 src/index.html

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git push origin main
Enter passphrase for key '/c/Users/ruso3/.ssh/id_ed25519':
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 517 bytes | 172.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:abarrero1358/Barrero_AndresFelipe_nov24.git
   88232dd..0b6756b  main -> main

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (main)
$ git checkout -b AndresBarrero
Switched to a new branch 'AndresBarrero'

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (AndresBarrero)
$ code readme.md

ruso3@Alisson2512 MINGW64 /c/DAM1/UNIR/1.DAM1/4. Entorno de Desarrollo/1_Trimestre/Actividades_y_Examen/2_Examen/Barrero_AndresFelipe_nov24 (AndresBarrero)
$
