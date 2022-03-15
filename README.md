<h3>Clonar repositorio</h3>

Para clonar el repositorio, primeramente he creado una carpeta en local donde guardarlo, una vez creada mediante la consola he accedido a ella y he usado el comando "git clone https://github.com/MrDamian1723/masteruah". 



![image-20220315185742699](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315185742699.png)



<h3>Creacion de README, commit y push</h3>

Una vez hecho esto he creado el archivo de .md al repositorio mediante el comando "git add README.md", una vez hecho esto he hecho un commit mediante el comando "git commit -m 'Primer commit' ". Una vez hecho esto mediante el comando push lo he subido al repositorio no local, "git push https://github.com/MrDamian1723/masteruah".



![image-20220315190611258](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315190611258.png)



<h3>Creación de archivo de texto 1 y adición al repositorio local</h3>

Para crear el archivo de texto he usado el comando "type nul > 1.txt" y para añadirlo al repositorio he usado el comando "git add 1.txt".



![image-20220315191430341](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315191430341.png)



<h3>Creacion de primer tag y su subida al repositorio</h3>

Para crear el tag he usado el comando "git tag v0.1" -m "Version inicial", y para poder verlo para comprobar que se ha creado correctamente he usado el comando "git show v0.1". Una vez hecho esto para subirle he usado "push origin v0.1". Una vez hecho todo esto he hecho un push para aplicar todos los cambios hasta ahora mencionados.



![image-20220315191452195](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315191452195.png)

![image-20220315191512002](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315191512002.png)

![image-20220315191746209](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315191746209.png)



<h3>Creacion de rama y archivo txt</h3>

Para crear una rama he usado el comando "git branch v0.2", una vez creado para posicionarme en ella he usado el comando "git checkout v0.2" y para comprobar que lo he hecho bien he usado "git branch". Una vez hecho esto he creado el archivo de texto 2.txt usando nuevamente "type nul > 2.txt". Una vez hecho esto he hecho el commit y el push.



![image-20220315192347183](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315192347183.png)



Despues de hacerlo me he dado cuenta de que se me habia olvidado añadir 2.txt asi que he hecho de nuevo el commit y el push despues de hacer el git add 2.txt.



![image-20220315192924357](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315192924357.png)



<h3>Merge</h3>

Para hacer el merge me he cambiado a la main branch con "git checkout main" y he usado el comando "git merge v0.2".



![image-20220315193625364](C:\Users\damik\AppData\Roaming\Typora\typora-user-images\image-20220315193625364.png)





