This repository contains the data used in [Machine learning of dissection photographs and surface scanning for quantitative 3D neuropathology](https://elifesciences.org/reviewed-preprints/91398).

The data consists of dissection photographs of patients with neuropathological disease collected from two sites-.
1. Massachusetts Alzheimer's Disease Research Center (MADRC), and
2. The University of Washington Alzheimer's Disease Research Center (UWADRC).

There are a total of 28 subjects from UWADRC and 33 subjects (15, left, 10 right, 8 whole) from MADRC in the data.

Each subject has two folders, one called 'photos' and one called 'connected_components'. The photos folder contains images of the dissection photographs (JPG) and the connected_components folder contains npy files of the connected components suggesting the order of the slices in the dissection photograph.

### Download instructions
```
pip install datalad
datalad clone git@github.com:MGH-LEMoN/elife-data.git
cd elife-data
datalad get .
```
NOTE: This download process can take a while. So, please be patient.

For more information, please open an issue here or send an e-mail to the senior author at [JIGLESIASGONZALEZ@mgh.harvard.edu](mailto:JIGLESIASGONZALEZ@mgh.harvard.edu?subject=Question%20about%20elife-data)