La base de datos de la red neuronal se encuentra en el siguiente camino de github:
https://github.com/gstinoco/Skin-Diffusion-GFD.git
Se encuentra en Datasets y es la carpeta que dice "skin224_nu" contiene 900 clases con 100 imágenes cada una. 
Al descargar ambos archivos, la red neuronal funcionará si crea la carpeta skin_split que contiene 70% train, 20% test y 10% validation. 
Finalmente se compila la red y se entrena. De momento la en lugar de Flatten() se utiliza AgerageGlobalPooling() y 500 clases.  

