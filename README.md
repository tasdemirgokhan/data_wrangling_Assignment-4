# Reweighing (Kamiran & Calders, 2012) on German Credit, COMPAS and Adult

Reproduction of the pre-processing fairness method **Reweighing** from
F. Kamiran and T. Calders, "Data preprocessing techniques for classification without discrimination",
*Knowledge and Information Systems* 33(1), 1–33 (2012). doi:10.1007/s10115-011-0463-8

The notebook computes demographic parity difference (DP_Diff), disparate impact ratio (DIR) and consistency
before and after Reweighing, with an unweighted logistic-regression baseline, 10 random splits and a sensitivity check

## How to run

bash

git clone https://github.com/tasdemirgokhan/data_wrangling_Assignment-4.git
cd data_wrangling_Assignment-4
python3.12 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt


Open `Reweighing_Kamiran_Calders_2012.ipynb` from this folder, select the `.venv` kernel and run **Restart Kernel → Run All**. 
The data are included; results go to `results/` and `figures/`.
