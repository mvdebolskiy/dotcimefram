# dotcimefram
.cime folder contents on fram


This repositroy makes it possible to pull the latest changes in [cime](https://github.com/ESMCI/cime) whithout affecting your machine configuration. 

## Usage
Clone, name and place this repository under the folder `$HOME/.cime` to run CTSM out of the box. 

### NB 
When the files from this repository are used on Fram, the following options should be added to create new cases:
```
 --machine fram --driver nuopc --compiler intel --mpilib impi --run-unsupported --project <your-project> `
```
 
