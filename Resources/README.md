# Week 1: Introduction

# 🗃️ Datasets útiles

| Título | Tarea | Data format | Link |
|---|---|---|---|
| Fruits dataset | Clasificación | ```.csv``` | [Clean](https://drive.google.com/file/d/1M8tiAWDZclABJN1Meq9oEHCLJTNyHdpP/view)
| Malaria cells | Clasificación | ```.png``` | [Raw](https://drive.google.com/file/d/1tCa6MHRUM34pv0wwDBsRkpFqMIZPk6iO/view?usp=drive_link)
| Noisy captchas | Clasificación | ```.png``` | [Raw](https://drive.google.com/file/d/1EyZiqMovGI0lZ_uawxAOoGcKm9CBy0kM/view?usp=drive_link)
| Disease diagnosis | Clasificación | ```.csv``` | [Raw](https://drive.google.com/file/d/1T-n-AoJ_As36oBLjY9Frc6NP_PwXWzTq/view?usp=sharing), [Clean](https://drive.google.com/file/d/1Sp_u1vaTafdrvUsZQHzGRCmcy4VfDf_s/view?usp=sharing)
| Houses in Iowa | Regresión | ```.csv``` | [Clean](https://drive.google.com/file/d/1BnTVOkFwRxT0wTKdfkbKF26R4iEKKshJ/view?usp=sharing)
| Natural images | Regresión | ```.png``` | [Raw](https://drive.google.com/file/d/1hF7a-tBXWm9efkG8yi5T-Yh58V2F5icH/view?usp=drive_link)
| Heart stroke dataset | Regresión | ```.csv``` | [Raw](https://drive.google.com/file/d/1JNtrwHJukzeK6l5ljvUgB8_8yESZ_qDK/view?usp=drive_link)
| Bank Customer segmentation | Clasificación / Clustering  | ```.csv``` | [Raw](https://drive.google.com/file/d/1omMtaPEQRilZzTRYqBM5VXU5oXl2BMG9/view?usp=sharing), [Clean](https://drive.google.com/file/d/14V61wky2xXsYwD62EdOfv0AJvH89MG0F/view?usp=sharing)
| Product recommendation| Clasificación / Clustering  | ```.csv``` | [Raw](https://drive.google.com/file/d/14V61wky2xXsYwD62EdOfv0AJvH89MG0F/view?usp=sharing), [Clean](https://drive.google.com/file/d/14V61wky2xXsYwD62EdOfv0AJvH89MG0F/view?usp=sharing)



# 🗃️ Paquetes y librerías


## Docker environment
A preconfigured environment has been provided to ensure that all code runs with the correct dependencies. This helps maintain reproducibility and avoids issues related to package versions or system configuration. To use this environment, you must first install Docker. You can follow the official installation guide here: 

[https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

Once Docker is installed, download the container image by running the following command:

```docker pull rubenfonnegra/jupyter-ml-docker```

After downloading the image, you can start the container with:

```docker run -p 8888:8888 jupyter-ml-docker```

This command will launch a JupyterLab instance accessible from your browser. From there, you can upload the notebook files and execute the code within the prepared environment. Once the container is running, open the URL shown in the terminal to open your browser and navigate through the files. 

