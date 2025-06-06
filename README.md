# MS-Disease-Trajectory-Synthea
A disease trajectory model for Multiple Sclerosis (MS) developed using Synthea’s open-source framework. This model simulates realistic patient journeys based on evidence from literature and anonymized real-world data.

## How to Use

1. Download the `.json` file titled `multiple_sclerosis_disease_trajectory.json`.
2. Go to the [Synthea Module Builder](https://synthetichealth.github.io/module-builder/).
3. Upload the `.json` file to the interface to view or edit the model.

### Attention

Please note that due to floating-point precision, some numeric values in the model (e.g., probabilities) may appear with excessively long decimal places. These are not input errors but the result of how floating-point numbers are handled in the model. This may  cause slight visual inconsistencies when reviewing or editing the `.json` file.

