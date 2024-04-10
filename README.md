# **Hyperspectral imaging dataset**


![Hyperspectral imaging dataset](fig/Dataset.png)

We present a database of hyperspectral images (HSIs) that were used to support our research. The images are of a wide variety of real-world materials and objects. We are making this database available to the research community. Details of the database can be found in our manuscript.


## **Image Capture Information**
| Camera              | FigSpec-23      | GaiaField Pro-N17E-HR |
| ------------------- | --------------- | --------------------- |
| Range of wavelength | 400-1000 nm     | 900-1700 nm           |
| Steps               | 2.5 nm          | 5 nm                  |
| Sampling steps      | 10 nm           | 10 nm                 |
| Number of bands     | 61              | 81                    |
| Spatial resolution  | 960×1230 pixels | 640×660 pixels        |
| Image format        | spe/hdr         | raw/hdr               |


## **Database Organization**
After data processing, 61 bands were selected at 10 nm intervals within the 400-1000 nm range. Similarly, 81 bands were chosen at 10 nm intervals in the 900-1700 nm range. Additionally, we calibrated the collected HSIs to eliminate the quantum efficiency (QE) influence of each camera. We provide the QE data named ‘FS23_acA1920.mat’ and ‘’.

Because the field of view of these two cameras is different, we performed image registration on the acquired hyperspectral images of the two cameras. As a result, we obtained a hyperspectral imaging dataset covering the entire spectral range of 400-1700 nm. the spatial resolution of the dataset is 640 × 666 pixels, with a total of 131 spectral bands at 10 nm intervals.

Our dataset comprises 1000 sets of hyperspectral images captured using the Figspec-23 and GaiaField Pro-N17E-HR hyperspectral cameras. These sets encompass a diverse range of scenes, with 500 outdoor scenes (such as roads, buildings, flowers, vehicles, etc.) and 500 indoor scenes captured under laboratory illuminant (Thorlabs SLS302, 10W output optical power, 1115lux), including food, cloth, toy, model, etc. The outdoor scenes were photographed in Beijing, China from April to June and October to December, encompassing various weather conditions including sunny, cloudy, and overcast.

The collection of image pairs is available at this repository [10.5281/zenodo.10952018](https://zenodo.org/doi/10.5281/zenodo.10952017)
 

## Paper
Under Review.


## Contact Information
If you have any questions, please feel free to contact us (bian@bit.edu.cn).

