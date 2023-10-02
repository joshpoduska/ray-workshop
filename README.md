# Ray Tutorial Project

## Contents

* Tutorial Notebooks:
  * 1-Beginner-Ray-Core.ipynb
  * 2-Intermediate-Ray-Core-And-Large-Data.ipynb
  * 3-Intermediate-XGBoost-Ray-Tune.ipynb
* Other Notebooks:
  * admin-notebooks/2-Intermediate-data-gen.ipynb (generates files needed for notebook 2)
  * troubleshooting/check_packages.ipynb (useful during compute environment setup)
  * troubleshooting/* (other miscellaneous troubleshooting notebooks)
* README

## Project and Workspace Setup

1. Fork or Copy this project, or otherwise get these files into a Domino project.
2. Mount the Datasets (not needed for Beginner notebook)
   * Navigate to Data in the project sidebar
   * Click on the "Domino Datasets" tab
   * Click "Mount Shared Dataset" and choose
       * `Points-For-Pi-Approximation` for use with `2-Intermediate-Ray-Core-And-Large-Data.ipynb`
       * `CA-Housing` for use with `3-Intermediate-XGBoost-Ray-Tune.ipynb`
       * Ask your admin if these are not available, or see the Prerequisites section of this readme
2. Start a new workspace
    * In Step 1
        * Ensure a suitable Ray Workspace environment (ask your admin, or see the Prerequisites section of this readme)
        * Jupyterlab is recommended for the IDE
        * The smallest available Hardware Tier is recommended
    * No changes in Step 2 are required
    * In Step 3
        * Choose Ray for the cluster
        * Ensure a suitable Ray Cluster environment (ask your admin, or see the Prerequisites section of this readme)
        * Choose 2 workers (no autoscaling needed)
        * The smallest available Hardware tier is recommended for both head and worker nodes.
        * No local storage needed
