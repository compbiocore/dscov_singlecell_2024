# dscov_singlecell_2024

## To use this notebook

1.  Go to `ood.ccv.brown.edu` (you will need an Oscar account).
2.  Go to `Clusters` in the blue menu bar at the top and click the drop-down that says '\>\_OSCAR Shell Access'
3.  Go to your home folder (`cd ~`)
4.  Git clone the repo (`git clone https://github.com/compbiocore/dscov_singlecell_2024.git`).
5.  Go back to `ood.ccv.brown.edu` and look under `Interactive Apps` in the blue menu bar and click on `RStudio on Singularity` under `Expert GUIs`.

Fill in the fields as follows:

-   `Account`: leave blank\
-   `Partition`: leave blank\
-   `Number of hours`: 3\
-   `Num Cores`: 8\
-   `Memory`: 90\
-   `Singularity Container Path`: /oscar/data/shared/databases/workshops/dscov/dscov_singlecell_2024/metadata/dscov_singlecell_2024:latest.sif\
-   `Package install Path`: leave blank\
-   `Path for R Executable`: This should be the full path to the repo root folder in step 4.\
-   `R Module`: leave blank\
-   `Additional Data Path`: leave blank

Once your job starts, click the button to connect to session.\
At the top of the screen you'll see a menu bar that starts with 'file', click on 'file' and 'open file'.\
Open the `dscov_singlecell_2024.Rproj` file in the root folder of the repo.\
