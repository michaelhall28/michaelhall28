## Repositories
These contain some of the code produced while working at the Wellcome Sanger Institute and MRC-Cancer Unit.  
They relate to the analysis and simulation of genetic mutations in normal tissues. 

See also:   
> https://github.com/PHJonesGroup - further code from myself and others in the Jones group at Sanger  

> https://zenodo.org/record/3648706#.Yk7nyC8w3m0 - Netlogo and Java (HAL) models to accompany *Colom, Bartomeu, et al. "Spatial competition shapes the dynamic mutational landscape of normal esophageal epithelium." Nature genetics 52.6 (2020): 604-614.* 

### clone-competition-simulation

<img src="https://github.com/michaelhall28/michaelhall28/blob/main/img/clone_comp_imgs-01.png" alt="Competition plots" width="800"/>


Python code to run various simulations of mutant clonal competition.  
It can run Moran, 2D Moran,  Wright-Fisher, 2D Wright-Fisher and (non-competitive) branching processes.  

The code has been used in:   
> *Fowler, Joanna C., et al. "Selection of oncogenic mutant clones in normal human skin varies with body site." Cancer discovery 11.2 (2021): 340-361.*  

> *Abby, Emilie, et al. "Notch1 mutation drives clonal expansion in normal esophageal epithelium but impairs tumor growth." bioRxiv (2021).*   

> (old version of this code) *Michael WJ, Philip H. Jones, and Benjamin A. Hall. "Relating evolutionary selection and mutant clonal dynamics in normal epithelia." Journal of the Royal Society Interface 16.156 (2019): 20190230.*  

> (even older version of this code)  *Murai, Kasumi, et al. "Epidermal tissue adapts to restrain progenitors carrying clonal p53 mutations." Cell stem cell 23.5 (2018): 687-699.*   

### darwinian_shift
Python code for statistically analysing patterns of somatic evolutionary selection in genes or proteins.  
A preprint is available:  
*Hall, Michael WJ, et al. "Investigating structure function relationships in the NOTCH family through large-scale somatic DNA sequencing studies." bioRxiv (2020).*  

It has also been used in *Fowler, Joanna C., et al. "Selection of oncogenic mutant clones in normal human skin varies with body site." Cancer discovery 11.2 (2021): 340-361.*  

### Colom_lesions
Code modelling the elimination of micro-tumours by highly fit mutant clones in the surrounding tissue for  
*Colom, B., et al. "Mutant clones in normal epithelium outcompete and eliminate emerging tumours." Nature 598.7881 (2021): 510-514.*

### Fowler_et_al_scripts 
Scripts to accompany *Fowler, Joanna C., et al. "Selection of oncogenic mutant clones in normal human skin varies with body site." Cancer discovery 11.2 (2021): 340-361.*  
These scripts make use of the code from the clone-competition-simulation and darwinian_shift repositories. 

### Hall_et_al_2020
Notebooks to generate the figures for the preprint *Hall, Michael WJ, et al. "Investigating structure function relationships in the NOTCH family through large-scale somatic DNA sequencing studies." bioRxiv (2020).*

### hall_et_al_2019
Code to recreate the figures for *Hall, Michael WJ, Philip H. Jones, and Benjamin A. Hall. "Relating evolutionary selection and mutant clonal dynamics in normal epithelia." Journal of the Royal Society Interface 16.156 (2019): 20190230.*

