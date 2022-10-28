# Creación del Cluster

1.  Primero realizamos gcloud init y elegimos el proyecto.
2.  Establecemos la zona del proyecto.

    ![](media/90f57e796973cae148270310adb6af7a.png)

3.  Creamos el cluster

    ![A computer screen capture Description automatically generated with medium confidence](media/22952a9f40fabaa2626d1ed21e0fce4b.png)

4.  Creamos el servicio

    ![](media/c092214e7e29a99cbdd821f1c3275802.png)

5.  Mostramos el comportamiento del cluster

    ![](media/0024ad064842103e467cdf9310808d8f.png)

6.  Configuramos el HPA

    ![](media/41a969499184c492bb18d4cb071c83ed.png)

7.  Comprobamos el estado

    ![](media/da473b9201c5f746afe93d8479c1f172.png)

8.  Activamos el autoescalado horizontal del cluster

    ![](media/38853c30d899803168e50a6c79afdeb5.png)

9.  Optimaze-utilization

    ![](media/0d5c6d694d05cf6cc87897d936c8e96a.png)

10. Nodos disponibles que podemos usar:

    ![](media/701e511320f1d3aaffb847769060aeed.png)

# Entrega 2

1.  En el directorio donde se encuentra el DockerFile creamos la imagen. Usamos el comando -\> “sudo docker build -t gcr.io/pract6-366611/ab:v0.0.1 .”

    ![Text Description automatically generated](media/f9b7df5ae2d606e61dd581cd0d8f54c9.png)

    DockerFile

    ![Text Description automatically generated](media/abc5a2e1537782fb4c1349c97288c485.png)

2.  Pusheamos a Google la imagen con el comando “gcloud builds submit --tag gcr.io/pract6-366611/ab:v0.0.1 .”
3.  Creamos el job.yaml

    ![Text, application Description automatically generated](media/23bd4b971f7a50bfc0c278eab93ec6a1.png)

4.  Comprobamos que funciona:

    ![](media/1a703f5b8fb1c50e519d3e715acd321d.png)

5.  Cluster creado en Google:
6.  Usando Lens sacamos información relevante sobre el cluster:

    ![A screenshot of a computer Description automatically generated](media/6d06e1fa96d81068968051cd8515bd7d.png)

# Entrega 3

1.  Se crea el cluster igual que en la entrega 2 para un nuevo proyecto
2.  
