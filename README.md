# Code and data for  lncRNA subcellular localization paper

# <font color="blue"> Part1 Dataset</font>
1. Building lncRNA and mRNA datasets from GENCODE and lncATLAS<br>
2. Extracting genes from APEX-Seq data. Extracting sequence infor from 1<br>

# <font color="blue"> Part2 Analysis</font>
Notebook 1: Calculating q-mer with k-mismatches counts<br>
Notebook 2: LncRNA CN-RCI distribution per cell lines, cell lines correlation<br>
Notebook 3: Prediction without auto-encoder, using SMOTE to handle data imbalance <br>
Notebook 4: Prediction with auto-encoder, using SMOTE to handle data imbalance. <br>
Notebook 5: Apply class_weight during the model training to handle data imbalance issue.<br>
Notebook 6: Training on one cell line, test other cell lines, test RF, SMOTE without auto-encoder.<br>
Notebook 7: Training on one cell line, test other cell lines, test 1DCNN, SMOTE with auto-encoder.<br>
Notebook 8: Build the matrix for the results from 6 and 7.<br>
Notebook 9: Switching genes.<br>
Notebook 10: Average_of_10_fold_accu_for_mismatch_with_std.<br>
