# **Netflora**

**Read this in other languages**: [Português](README.pt.md), [Español](README.es.md).

<a href="https://colab.research.google.com/drive/16nydPteUlpXo1tcIC0DWrQr05Z3m-npU?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

<p align="justify">The Netflora Project involves the application of geotechnologies in forest automation and carbon stock mapping in native forest areas in Western Amazonia. It is an initiative developed by Embrapa Acre with sponsorship from the JBS Fund for the Amazon.

<p align="justify"> Here we will discuss the "Forest Inventory using drones" component. Drones and artificial intelligence are used to automate stages of the forest inventory in identifying strategic species. More than 40,000 hectares of forest areas have already been mapped with the goal of collecting information to compose the Netflora dataset.

<div style="display: flex;">

 <img src="https://github.com/NetFlora/NetFlora/blob/main/logo/Netflora.png?raw=true" width="200" alt="Netflora Logo">

  <img src="https://github.com/NetFlora/NetFlora/blob/main/logo/Embrapa-Acre.png?raw=true" width="200" alt="Embrapa Acre Logo">
    
   <img src="https://github.com/NetFlora/NetFlora/blob/main/logo/Fundo-JBS.png?raw=true" width="200" alt="JBS Fund Logo">

</div>

## Running the Detection

``!python detect.py --device 0 --weights model_weights.pt --img 1536``

## Visualizing Detection Results 

``!python results.py --graphics --conf 0.25``

## Examples of Detection by Algorithms

<div style="display: flex;">

 <img src="https://github.com/NetFlora/NetFlora/blob/main/inference/images/Acai.jpg?raw=true" width="230" alt="Acai"> 

 <img src="https://github.com/NetFlora/NetFlora/blob/main/inference/images/Palmeiras.jpg?raw=true" width="250" alt="Palm">
 
 <img src="https://github.com/NetFlora/NetFlora/blob/main/inference/images/PFMNs.jpg?raw=true" width="230" alt="PFMNs">
  
 </div>

## Website

https://www.embrapa.br/acre/tecnologias/netflora

## Citation

[![DOI](https://zenodo.org/badge/791648585.svg)](https://zenodo.org/doi/10.5281/zenodo.11063715)   
Karasinski, M. A., Santos, E. K. M. dos, Santos, C. A. N., &#38; Figueiredo, E. O. (2024, April 25). NetFlora/Netflora: 0.1.0. Zenodo. https://zenodo.org/records/11063716

```

@misc{Karasinski2024NetFlora,
	author = {Karasinski, Mauro Alessandro and Santos, Erica Kerolaine Mendon{\c c}a dos and Santos, Caio Alexandre Nascimento and Figueiredo, Evandro Orfan{\' o}},
	year = {2024},
	month = {apr 25},
	title = {NetFlora/{Netflora}: 0.1.0},
	howpublished = {https://zenodo.org/records/11063716},
}


```


## License

Distributed under the GPL 3.0 license. See [`LICENSE`](LICENSE.md) for more information.

## Useful Links

- [EAD Course](https://www.embrapa.br/web/portal/acre/tecnologias/netflora/curso-ead)
- [Frequently Asked Questions (FAQ)](https://www.embrapa.br/web/portal/acre/tecnologias/netflora/perguntas-e-respostas)
- [Embrapa Acre](https://www.embrapa.br/acre/)
- [JBS Fund for the Amazon](https://fundojbsamazonia.org/)

We appreciate your interest for the Netflora project!

## Acknowledgements

<details><summary> <b>Expand</b> </summary>

* [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
* [https://github.com/WongKinYiu/yolov7](https://github.com/WongKinYiu/yolov7)
