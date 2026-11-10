To repeat the data from this article, follow these steps:

1. Install Apptainer:
```
https://apptainer.org/docs/admin/main/installation.html
```
2. Download Apptainer container via browser:
```
https://disk.360.yandex.ru/d/SCiW43bUI_XhaA
```
3. Run Apptainer container:
```
apptainer run r-niknit_V7.sif
```
4. Download code and data from Github:
```
wget https://github.com/niknit96/Aleynova_et.al.2026/archive/master.zip
unzip master.zip
cd ./Aleynova_et.al.2026-main
```
5. Run R scripts:
```
Rscript -e 'rmarkdown::render("./16S/16S_analysis.Rmd", output_file="../16S_NGS_report.html")'
Rscript -e 'rmarkdown::render("./ITS/ITS_analysis.Rmd", output_file="../ITS_NGS_report.html")'
```
6. Results in ./Aleynova_et.al.2026-main.
