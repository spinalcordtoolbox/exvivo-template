# exvivo-template

Data repository associated with [this project](https://github.com/sct-pipeline/exvivo-template).

## Data

The ex-vivo template is available in [this repository](https://github.com/sct-data/exvivo-template), which contains:
- `template.nii.gz`: ex-vivo template.
- `mask_spinalcord.nii.gz`: binary spinalcord mask.
- `map_greymatter.nii.gz`: probabilistic grey matter map.
- `mask_spinalsegments.nii.gz`: mask of spinal segments, the value corresponds to the cervical segment, e.g. voxel value of 5 corresponds to C5 spinal level.
- `mask_motortracts.nii.gz`: mask of spinal motor tracts, the value corresponds to a specific motor tract, see [Labels sub-section](#labels) for details.

### Labels

Motor tracts value in `mask_motortracts.nii.gz`:
- 01 - Anterior corticospinal tract
- 02 - Central canal
- 03 - Epaxial motor column
- 04 - Trapezius and sternomastoid motor neurons of lamina 9
- 05 - Hypaxial motor column
- 06 - Lateral corticospinal tract
- 07 - Lamina 2 of the spinal gray (substantia gelatinosa)
- 08 - Cuneate fasciculus
- 09 - Gracile fasciculus
- 10 - Phrenic motor neurons of lamina 9
- 11 - Biceps motor neurons of lamina 9
- 12 - Supraspinatus and infraspinatus motor neurons of lamina 9
- 13 - Deltoid motor neurons of lamina 9
- 14 - Triceps motor neurons of lamina 9
- 15 - Forearm extensor motor neurons of lamina 9
- 16 - Forearm flexor motor neurons of lamina 9
- 17 - Latissimus dorsi motor neurons of lamina 9
- 18 - Pectoral muscle motor neurons of lamina 9

## How to cite
Gros, C., Asiri, A., De Leener, B., Watson, C., Cowin, G., Ruitenberg, M., Kurniawan, N., Cohen-Adad, J., 2020. Ex vivo MRI template of the human cervical cord at 80μm isotropic resolution, in: Proceedingsof the 28th Annual Meeting of ISMRM. Presented at the ISMRM.


## Contributors
Charley Gros, [Nyoman Kurniawan](https://cai.centre.uq.edu.au/profile/110/nyoman-kurniawan), Benjamin De Leener, Charles Watson and Julien Cohen-Adad.
