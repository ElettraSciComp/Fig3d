<div align="left">  
  
<p align="center">
  <img src=https://github.com/ElettraSciComp/Fig3d/blob/main/images/logo_small.png alt="logo"/>
</p>

# Fig3d : Interactive 3D figures

Certain scientific manuscripts have figures that show 3D objects as a limited number of 3D views, like:

<p align="center">
  <img src=https://github.com/ElettraSciComp/Fig3d/blob/main/images/basic_figure.png alt="basic_figure"/>
</p>

<b>Figure 1:</b> (panel A) example of a simplified 3D model based on the logo of Elettra Sincrotrone Trieste. (panel B) Fig3d allows for multiple panels, just like manuscript figures!<br></br>

Fig3d allows for an interactive Figure of 3D objects arranged in panels and accompanied captions. Its rendering is simple and is based on the excellent [Stl Viewer Javascript Plugin](https://www.viewstl.com/plugin/). The previous figure (as appears in PDF, online, etc) can be viewed within the browser window, as shown below: 
<img src=https://github.com/ElettraSciComp/Fig3d/blob/main/images/basic_figure_screenshot.png alt="basic_figure_screenshot"/>

For example, [here](https://download2.grid.elettra.trieste.it/prox_8t4H3EybKLeTZAhSTDXZPUYylfwnxidd/Elettra3D_logo/Elettra3D_logo_v3/rawdata/fig3D_elettra/) you can find the interactive Fig3d of the Elettra logo!

The main advantage of Fig3D is a specialised web based Wizard that given a caption and a 3D Object (ie. .stl) generates the corresponding standalone interactive 3D figure that requires no special servers or software to run (just a web browser). It is also encouraged that it is included as a hyperlink, ideally with its own DOI to the manuscript's figure. The file may be hosted on standard scientific data repos.
<img src=https://github.com/ElettraSciComp/Fig3d/blob/main/images/fig3d_wizard.png alt="fig3d_wizard"/>

## Fig3d : Example use case for 3D brain segmentation for Magnetic Resonance Imaging (MRI) in neuro-oncology

A recent implementation example of Fig3d can be found at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7640630.svg)](https://doi.org/10.5281/zenodo.7640630) 

In this use case, advanced methods of automated MRI assessment are employed in order to reconstruct 3D brain segmentations. These 3D reconstructions in can then be converted to the .stl format and displayed through Fig3d and subsequently even 3D printed for further studies.

</div>
