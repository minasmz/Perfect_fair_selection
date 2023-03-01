# Perfect_fair_selection


## Adult income dataset using White and Black as sensitive attributes

The debiased model trained with the following parameters:

num_epochs = 5 

adversary_loss_weight = 1 

batch_size = 5 
### Acuraccy as a function of $\epsilon$ when we have perfect fairness
![](fz_adult.PNG)

### Accuracy as a function of $\epsilon$
![](adult_wb_accuracy_in_all_single_selection_3.png)

### Fairness as a function of $\epsilon$
![](adult_wb_equal_opportunity_single_selection_3.png) 

## FICO credit score dataset using White and Black as sensitive attributes

The debiased model trained with the following parameters:

num_epochs = 3 

adversary_loss_weight = 1 

batch_size = 250

### Acuraccy as a function of $\epsilon$ when we have perfect fairness
![](fz_wb.PNG)
![](fz_wb_all_legend.PNG)

### Accuracy as a function of $\epsilon$
![](wb_accuracy_in_all_iterations_all_in_one_adversarial_March.png)

### Fairness as a function of $\epsilon$
![](wb_equal_opportunity_all_in_one_adversarial_March.png) 


## FICO credit score dataset using White+Hispanic and Asian as sensitive attributes

The debiased model trained with the following parameters:

num_epochs = 5 

adversary_loss_weight = 1 

batch_size = 200

### Acuraccy as a function of $\epsilon$ when we have perfect fairness
![](fz_wha_new.PNG)

### Accuracy as a function of $\epsilon$
![](wha_accuracy_in_all_iterations_all_in_one_plus_debiased_March.png)

### Fairness as a function of $\epsilon$
![](wha_equal_opportunity_all_in_one_plus_debiased_March.png) 

## LSAT dataset using White and Black as sensitive attributes

The debiased model trained with the following parameters:

num_epochs = 7

adversary_loss_weight = 3 

batch_size = 50

### Acuraccy as a function of $\epsilon$ when we have perfect fairness
![](fz_lsat.PNG)

### Accuracy as a function of $\epsilon$
![](lsat_wb_accuracy_in_all_single_selection_3.png)


### Fairness as a function of $\epsilon$
![](lsat_wb_equal_opportunity_single_selection_3.png) 
