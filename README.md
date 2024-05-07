# MLOps_P3

1. Video 

[![Texto alternativo](https://img.youtube.com/vi/YPbuRMIL1H8/0.jpg)](https://www.youtube.com/watch?v=YPbuRMIL1H8)

3. INgrese a la interfaz grafica de Airflow en la direccion: http://10.43.101.151:8080/home y haga clic en el boton que dispara el DAG, si lo desea puede seguir el desarrollo de la ejecucion haciendo clic en la celda last run que ahora tiene la fecha actual del ultimo run enviado.

   ![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/airflow1.png)
   ![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/airflow2.png)

Una vez esta ejecucion termine con las 3 cajas del grafo en status success el modelo estara disponible en mlflow.

4. ingrese a la interfaz de mlflow a traves de la direccion http://10.43.101.151:8087/#/models en esta ventanaencontrara listados los modelos generados y vera que ya cuentan con el alias de produccion que permite distinguirlos de los otros modelos.

![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflow1.png)

 En caso de no tener modelos registrados, el procedimiento es el siguiente:
 
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr1.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr2.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr3.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr4.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr5.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr6.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr7.png)
![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/mlflowr8.png)

6. ingresar a la url http://10.43.101.151:8082/ , en esta direccion se encuentra alojada la aplicacion streamlit en la cual se encuentra la siguiente interfaz grafica:

   ![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/streamlit2.png)

   En esta interfaz puede modificar los datos de prediccion o dejar los ya existentes, una vez ha revisado / modificado los datos para predecir puede hacer clic en el boton "realizar prediccion". El sistema devolvera una estructura Json donde encontrara el nombre del modelo utilizado y el valor predicho como se observa en la imagen:

   ![alt text](https://github.com/bermud1992/MLOps_P3/blob/main/images/streamlit1.png)
