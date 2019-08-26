Last login: Mon Aug 26 11:56:18 on ttys000
patricks-air:~ patrickthumeyer$ cd ./Documents/DCI/
patricks-air:~ patrickthumeyer$ 
patricks-air:~ patrickthumeyer$ 
patricks-air:~ patrickthumeyer$ clear



















patricks-air:~ patrickthumeyer$ cd ./Documents/DCI/Develop/asignments/command-line-01/
patricks-air:command-line-01 patrickthumeyer$ touch README.md
patricks-air:command-line-01 patrickthumeyer$ mkdir styles.css
patricks-air:command-line-01 patrickthumeyer$ mkdir scripts.js
patricks-air:command-line-01 patrickthumeyer$ mkdir images
patricks-air:command-line-01 patrickthumeyer$ mkdir content
patricks-air:command-line-01 patrickthumeyer$ mkdir fonts
patricks-air:command-line-01 patrickthumeyer$ cd ./images/
patricks-air:images patrickthumeyer$ mkdir icons
patricks-air:images patrickthumeyer$ cd ./Documents/DCI/Develop/asignments/command-line-01/command-line-01-patrickthumeyer
-bash: cd: ./Documents/DCI/Develop/asignments/command-line-01/command-line-01-patrickthumeyer: No such file or directory
patricks-air:images patrickthumeyer$ cd ./Documents/DCI/Develop/asignments/command-line-01/
-bash: cd: ./Documents/DCI/Develop/asignments/command-line-01/: No such file or directory
patricks-air:images patrickthumeyer$ cd ./Documents/DCI/Develop/asignments/command-line-01/
-bash: cd: ./Documents/DCI/Develop/asignments/command-line-01/: No such file or directory
patricks-air:images patrickthumeyer$ ..
-bash: ..: command not found
patricks-air:images patrickthumeyer$ cd ..
patricks-air:command-line-01 patrickthumeyer$ ls
README.md			images
command-line-01-patrickthumeyer	scripts.js
content				styles.css
fonts
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/
.git/
FoReSt-GReeN-hd-wallpaper-129105.jpg
INDEX.JS
InDeX.CSS
POST-__21.07.2019.md.md
POST-__22.07.2019.md
_POST-__26.07.2019_.md
_Post-__25.07.2019.md.md
casey-horner-wVjoNpcTHxM-unsplash.jpeg
chang-qing-2YQoKbyGvDc-unsplash.jpg
computer__iconfinder_Streamline-05_185024.svg
database__iconfinder_Streamline-77_185097.svg
forest-light-nature-   70365.jpg
index.html.html
joey-kyber-sFLVTqNzG2I-unsplash.jpg
john-fowler-aaIN3y2zcMQ-unsplash.jpg
john-fowler-bgGr1eKlYNw-unsplash.jpg
milada-vigerova-pQMM63GE7fo-unsplash.jpeg
network__iconfinder_Streamline-08_185027.svg
patrick-langwallner-Nv-rPPW_LBc-unsplash.jpg
post about the latest tech news -__24.07.2019.md
post-__23.07.2019.md
post-__27.07.2019.md
post-__29.07.2019.md
raychan-eJSN4mBkhVY-unsplash.jpg
sarah-dorweiler-9Z1KRIfpBTM-unsplash.jpg
server__iconfinder_storage_1370034.svg
vincent-guth-uhoILl3HUZM-unsplash.jpeg
webfontkit-20190825-182014/
wil-stewart-pHANr-CpbYM-unsplash.jpg
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.md content
patricks-air:command-line-01 patrickthumeyer$ ls
README.md			images
command-line-01-patrickthumeyer	scripts.js
content				styles.css
fonts
patricks-air:command-line-01 patrickthumeyer$ ls content
POST-__21.07.2019.md.md
POST-__22.07.2019.md
_POST-__26.07.2019_.md
_Post-__25.07.2019.md.md
post about the latest tech news -__24.07.2019.md
post-__23.07.2019.md
post-__27.07.2019.md
post-__29.07.2019.md
patricks-air:command-line-01 patrickthumeyer$ .
-bash: .: filename argument required
.: usage: . filename [arguments]
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.css styles
mv: rename command-line-01-patrickthumeyer/*.css to styles: No such file or directory
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.css styles.css
mv: rename command-line-01-patrickthumeyer/*.css to styles.css/*.css: No such file or directory
patricks-air:command-line-01 patrickthumeyer$ rn 'styles.css' styles
-bash: rn: command not found
patricks-air:command-line-01 patrickthumeyer$ mv 'styles.css' styles
patricks-air:command-line-01 patrickthumeyer$ mv 'scripts.js' scripts
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.css
usage: mv [-f | -i | -n] [-v] source target
       mv [-f | -i | -n] [-v] source ... directory
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.js
usage: mv [-f | -i | -n] [-v] source target
       mv [-f | -i | -n] [-v] source ... directory
patricks-air:command-line-01 patrickthumeyer$ ls styles
patricks-air:command-line-01 patrickthumeyer$ ls -a styles
.	..
patricks-air:command-line-01 patrickthumeyer$ ls scripts
patricks-air:command-line-01 patrickthumeyer$ ls
README.md			images
command-line-01-patrickthumeyer	scripts
content				styles
fonts
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.js scripts
mv: rename command-line-01-patrickthumeyer/*.js to scripts/*.js: No such file or directory
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.JS scripts 
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.CSS styles
patricks-air:command-line-01 patrickthumeyer$ ls -a styles
.		..		InDeX.CSS
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.svg images/icons/
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.jpg images/
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.png images/
mv: rename command-line-01-patrickthumeyer/*.png to images/*.png: No such file or directory
patricks-air:command-line-01 patrickthumeyer$ ls -a command-line-01-patrickthumeyer/
.
..
.git
casey-horner-wVjoNpcTHxM-unsplash.jpeg
index.html.html
milada-vigerova-pQMM63GE7fo-unsplash.jpeg
vincent-guth-uhoILl3HUZM-unsplash.jpeg
webfontkit-20190825-182014
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.jpeg images/
patricks-air:command-line-01 patrickthumeyer$ ls -a images/
.
..
FoReSt-GReeN-hd-wallpaper-129105.jpg
casey-horner-wVjoNpcTHxM-unsplash.jpeg
chang-qing-2YQoKbyGvDc-unsplash.jpg
forest-light-nature-   70365.jpg
icons
joey-kyber-sFLVTqNzG2I-unsplash.jpg
john-fowler-aaIN3y2zcMQ-unsplash.jpg
john-fowler-bgGr1eKlYNw-unsplash.jpg
milada-vigerova-pQMM63GE7fo-unsplash.jpeg
patrick-langwallner-Nv-rPPW_LBc-unsplash.jpg
raychan-eJSN4mBkhVY-unsplash.jpg
sarah-dorweiler-9Z1KRIfpBTM-unsplash.jpg
vincent-guth-uhoILl3HUZM-unsplash.jpeg
wil-stewart-pHANr-CpbYM-unsplash.jpg
patricks-air:command-line-01 patrickthumeyer$ ll command-line-01-patrickthumeyer/
-bash: ll: command not found
patricks-air:command-line-01 patrickthumeyer$ ls -a command-line-01-patrickthumeyer/
.				index.html.html
..				webfontkit-20190825-182014
.git
patricks-air:command-line-01 patrickthumeyer$ mv command-line-01-patrickthumeyer/*.html command-line-01/
mv: rename command-line-01-patrickthumeyer/index.html.html to command-line-01/: No such file or directory
patricks-air:command-line-01 patrickthumeyer$ .
-bash: .: filename argument required
.: usage: . filename [arguments]
patricks-air:command-line-01 patrickthumeyer$ ./
-bash: ./: is a directory
patricks-air:command-line-01 patrickthumeyer$ .
-bash: .: filename argument required
.: usage: . filename [arguments]
patricks-air:command-line-01 patrickthumeyer$ ../
-bash: ../: is a directory
patricks-air:command-line-01 patrickthumeyer$ .
-bash: .: filename argument required
.: usage: . filename [arguments]
patricks-air:command-line-01 patrickthumeyer$ cd ../
patricks-air:asignments patrickthumeyer$ .
-bash: .: filename argument required
.: usage: . filename [arguments]
patricks-air:asignments patrickthumeyer$ ./
-bash: ./: is a directory
patricks-air:asignments patrickthumeyer$ cd command-line-01/
patricks-air:command-line-01 patrickthumeyer$ ls command-line-01-patrickthumeyer/
index.html.html			webfontkit-20190825-182014
patricks-air:command-line-01 patrickthumeyer$ md ../
-bash: md: command not found
patricks-air:command-line-01 patrickthumeyer$ cd ../
patricks-air:asignments patrickthumeyer$ mv command-line-01/command-line-01-patrickthumeyer/*.html command-line-01/
patricks-air:asignments patrickthumeyer$ mv command-line-01/command-line-01-patrickthumeyer/
.DS_Store                   .git/                       webfontkit-20190825-182014/
patricks-air:asignments patrickthumeyer$ mv command-line-01/command-line-01-patrickthumeyer/
.DS_Store                   .git/                       webfontkit-20190825-182014/
patricks-air:asignments patrickthumeyer$ mv command-line-01/command-line-01-patrickthumeyer/webfontkit-20190825-182014/ command-line-01/fonts/
patricks-air:asignments patrickthumeyer$ ls fonts
ls: fonts: No such file or directory
patricks-air:asignments patrickthumeyer$ ls command-line-01/fonts/
webfontkit-20190825-182014
patricks-air:asignments patrickthumeyer$ nano README.md
patricks-air:asignments patrickthumeyer$ nano README.md 
patricks-air:asignments patrickthumeyer$ pwd
/Users/patrickthumeyer/Documents/DCI/Develop/asignments
patricks-air:asignments patrickthumeyer$ md command-line-01/
-bash: md: command not found
patricks-air:asignments patrickthumeyer$ cd command-line-01/
patricks-air:command-line-01 patrickthumeyer$ nano README.md 

