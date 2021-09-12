# GAN_Klimt
GAN Gustave Klimt: Klimt Artwork Generator

Goal: Gustave Klimt Artwork generator, Style Transfer, learn form Klimt Golden phase.

In Paris, where I live, there is a beautiful place called “ L’Atelier des Lumières “ in english, The workshop of Light. I was very excited when they re-opened because they were holding an exposition of my favorite artist: Gustave Klimt.

It is a kind of an experimental museum where artwork are projected on the wall on the giant warehouse using powerful projectors. They exploit the unique topology of the inside of the warehouse to create dream like scenaries. Here is a picture to give you an idea:

![image](https://github.com/KelGomez/GAN_Klimt/blob/main/image/atelier_lumiere.jpg?raw=true)

It was an amazing experience. I decided to use GAN's, inspired by GANGogh recent achivements among many others, to create a GAN Gustave Klimt. It will learn from Klimt Symbolist style in order to create new paintings, inspired from Klimt art:

<p float="left">
  <img src="https://github.com/KelGomez/GAN_Klimt/blob/main/image/gangogh_chart.jpg" width="300" />
  <img src="https://github.com/KelGomez/GAN_Klimt/blob/main/image/garden_farm.jpg" width="300" /> 
  <img src="https://github.com/KelGomez/GAN_Klimt/blob/main/image/Pallas-Athena.jpg" width="300" />
</p>

## Toward GAN Klimt 

I decided to use the GANGogh code, an amazing project from @rodrigobdz (https://github.com/rkjones4/GANGogh). It runs on 


### Step 1: Collect artwork for a Klimt Art Dataset

There are no specific Klimt artwork dataset available for Deep Learning, but the Klimt Foundation is planning to publish one in late 2021 for research purposes. In the meantime I used the Klimt Galery Complete Collection Archive  https://www.klimtgallery.org/ and Wikimedia Commans Klimt catalogue of artworks https://commons.wikimedia.org/wiki/Gustav_Klimt_catalog_raisonn%C3%A9,_1978

90% of the dataset will be the training set and 10% the validation dataset.

### Step 2:  Use the repository GanGogh

This awesome repository from 
https://github.com/rkjones4/GANGogh
