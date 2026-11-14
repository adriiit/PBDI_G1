Las siguientes imágenes has sido procesadas por el modelo adjunto best_model_OD_MA.pt, haciendo uso de la versión 8 nano de yolo, en busca de una versión más optimizada. En las 17 imágenes se ha podido captar el disco óptico, sin embargo en 1 imagen no se pudo captar la mácula.
- El uso del modelo requiere de la instalación de una versión de python posterior a la 3.8 e instalar la librería de ultralytics:
    <h1> pip install ultralytics </h1>
- Además de un comando de prueba similar al siguiente:
    <h1>yolo segment predict model="C:\MI_RUTA\best.pt" source="C:\MI_RUTA\images\test" imgsz=640 conf=0.25 save=True</h1>
