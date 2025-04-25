## Model Files

The `.h5` files in this directory are trained deep autoencoder models for angiogenesis receptor inhibition prediction, using the hyperparameters reported in our Article.

### Files:
- `VEGFR2_model.h5` – Model trained for VEGFR2 inhibition
- `FGFR2_model.h5` – Model trained for FGFR2 inhibition
- `EGFR_model.h5` – Model trained for EGFR inhibition

These models are compatible with the `Prediction.ipynb` notebook and accept compound descriptors as input.

**Input format**: tabular molecular descriptors (CSV)  
**Output**: probability prediction (probability potential inhibitor class, probability none-inhibitor class)
