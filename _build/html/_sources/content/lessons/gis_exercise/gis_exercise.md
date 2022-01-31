# Exercise - where did he go?


Kim decided to go on three scooter trips throughout January, recording his whereabouts with his phone.
The recorded gps tracks (so-called *gpx* files) have been uploaded to the Teams folder: Documents > General > Modules > ArcGIS Pro

```{admonition} Task
:class: tip

Plot these tracks in ArcGIS Pro and find out where he went (including the island, land areas – e.g., Albert I land -, and location/valley names). 

`````


### Does Svalbox have digital datasets in the area visited by Kim?

The Svalbox database lives both in a petrel project as well as on the web -see [svalbox](www.svalbox.no/map) -.
Let’s use the available map data to see whether Svalbox has acquired digital models and / or photos in the places visited by Kim.

```{admonition} Task
:class: tip

What is the outcrop model that Kim got closest too?

`````

````{margin}
```{admonition} Zenodo
:class: note

Zenodo is a general-purpose open-access repository. It allows researchers to deposit research papers, data sets, research software...
All the DTM in svalbox.no are uploaded there to assure free access to the data.
```
````

```{admonition} Task
:class: tip

Download the digital terrain model of the outcrop from the [Zenodo.org](https://zenodo.org/) database and plot it in your GIS project.
`````

### Which geological units did Kim cross?

As per the above, we can also check which geological units Kim crossed on his trips. 

Other than just importing the entire G_Geologi_Svalbard_S250_S750 layers into your map, it is probably a better idea to import only the “Geological units / Geologiske enheter” from the Geologi 1:250000 layer group.
Then you can click on the map and get information about the layer.

````{margin}
```{note}
You can access to this information from the “pop-up”.
```
````

```{admonition} Task
:class: tip

Make a list of all formations that Kim passed during his trips and include the Groups and lithologies.
```