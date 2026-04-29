# TRIBE Ad Brain-Pattern Analysis

- Generated: 2026-04-29T16:55:10
- Input root: `/Users/seong-yeob/Downloads/tribeproto`
- Interpretation note: these are TRIBE model-predicted fMRI-like responses, not direct experimental fMRI measurements.

## Input Inventory

- Included ad folders: 6
- Excluded folders: 1
- Exclusion details:
  - `Jurassic_Park..._Works_Big_Game_Commercial_2026_Xfinity_threshold90`: threshold_folder_excluded

## Manifest ROI Summary

- Parsed 4 manifest files and 424 frame rows.
- Overall most frequent ROIs:
  - R Gyrus rectus: 106 appearances, mean score 2.09, frame fraction 0.250
  - R Gyrus orbital: 92 appearances, mean score 1.99, frame fraction 0.217
  - L Sulcus orbital med-olfact: 86 appearances, mean score 2.16, frame fraction 0.203
  - L Gyrus rectus: 78 appearances, mean score 2.01, frame fraction 0.184
  - L Gyrus orbital: 78 appearances, mean score 1.96, frame fraction 0.184
  - L Gyrus temporal inf: 66 appearances, mean score 2.08, frame fraction 0.156
  - R Gyrus temporal inf: 66 appearances, mean score 2.03, frame fraction 0.156
  - R Sulcus orbital med-olfact: 65 appearances, mean score 2.09, frame fraction 0.153
  - R Gyrus and Sulcus cingul-Ant: 64 appearances, mean score 2.03, frame fraction 0.151
  - R Gyrus front sup: 60 appearances, mean score 2.07, frame fraction 0.142
  - R Gyrus and Sulcus subcentral: 48 appearances, mean score 2.17, frame fraction 0.113
  - L Sulcus temporal inf: 48 appearances, mean score 2.12, frame fraction 0.113
  - L Sulcus pericallosal: 47 appearances, mean score 2.49, frame fraction 0.111
  - R Gyrus oc-temp med-Parahip: 47 appearances, mean score 2.09, frame fraction 0.111
  - L Gyrus temporal middle: 44 appearances, mean score 2.06, frame fraction 0.104
  - L Gyrus front middle: 42 appearances, mean score 1.98, frame fraction 0.099
  - L Gyrus and Sulcus cingul-Ant: 40 appearances, mean score 2.12, frame fraction 0.094
  - R Sulcus temporal inf: 36 appearances, mean score 2.13, frame fraction 0.085
  - R Sulcus central: 34 appearances, mean score 1.95, frame fraction 0.080
  - L Gyrus front inf-Triangul: 34 appearances, mean score 1.94, frame fraction 0.080

## Advertisement-Level Highlights

### Budweiser_Super_Bowl_LX_Commercial_American_Icons_20260429_061035
- R Gyrus rectus: 30/121 frames, mean score 2.34
- L Gyrus temporal inf: 24/121 frames, mean score 2.27
- L Sulcus orbital med-olfact: 20/121 frames, mean score 2.43
- L Gyrus and Sulcus cingul-Ant: 20/121 frames, mean score 2.29
- L Sulcus pericallosal: 15/121 frames, mean score 2.78

### Jurassic_Park..._Works_Big_Game_Commercial_2026_Xfinity_20260429_064425
- R Gyrus rectus: 38/121 frames, mean score 2.13
- R Gyrus temporal inf: 34/121 frames, mean score 2.04
- R Gyrus front sup: 30/121 frames, mean score 2.07
- L Sulcus orbital med-olfact: 24/121 frames, mean score 2.14
- R Sulcus orbital med-olfact: 24/121 frames, mean score 2.14

### LAY_S_Last_Harvest_Super_Bowl_LX_Commercial_20260429_015322
- R Gyrus orbital: 46/121 frames, mean score 1.94
- L Gyrus rectus: 38/121 frames, mean score 1.95
- L Sulcus orbital med-olfact: 36/121 frames, mean score 2.12
- L Gyrus orbital: 34/121 frames, mean score 1.96
- R Gyrus and Sulcus cingul-Ant: 32/121 frames, mean score 2.01

### The_Choice_Pepsi_Super_Bowl_20260429_022611
- R Gyrus rectus: 22/61 frames, mean score 1.80
- L Gyrus front middle: 20/61 frames, mean score 1.80
- L Gyrus orbital: 16/61 frames, mean score 1.70
- L Gyrus front inf-Triangul: 14/61 frames, mean score 1.80
- L Gyrus rectus: 14/61 frames, mean score 1.78

## NPZ Pattern Analysis

- Valid NPZ prediction files: 6
- Included ads missing NPZ files: 0
- NPZ files should contain either a `preds` or `predictions` array with shape `n_predictions x n_features`.

| Ad | NPZ status | Array key | Preds shape | Validation |
| --- | --- | --- | --- | --- |
| Budweiser_Super_Bowl_LX_Commercial_American_Icons_20260429_061035 | found_in_data | predictions | 61x20484 | ok |
| Good_Will_Dunkin_20260428_133842 | found_in_data | predictions | 61x20484 | ok |
| Jurassic_Park..._Works_Big_Game_Commercial_2026_Xfinity_20260429_064425 | found_in_data | predictions | 61x20484 | ok |
| Jurassic_Park..._Works_Big_Game_Commercial_2026_Xfinity_threshold90 | found_in_data |  |  | skipped:threshold_folder_excluded |
| LAY_S_Last_Harvest_Super_Bowl_LX_Commercial_20260429_015322 | found_in_data | predictions | 61x20484 | ok |
| The_Choice_Pepsi_Super_Bowl_20260429_022611 | found_in_data | predictions | 31x20484 | ok |
| Considering_What_Paris_2024_Paralympic_Games | found_in_data_only | predictions | 228x20484 | ok |

## Similarity

- `ad_similarity.csv` contains Pearson correlations between each ad's mean prediction vector.

## NPZ Destrieux ROI Summary

- `npz_roi_summary_by_ad.csv` ranks Destrieux ROIs from each ad's mean prediction vector.
- Common mean-pattern top ROIs:
  - L Sulcus collat transv post: mean response 0.2953, peak 0.3573
  - R Sulcus collat transv post: mean response 0.2923, peak 0.3531
  - R Sulcus oc middle and Lunatus: mean response 0.2302, peak 0.3379
  - L Sulcus oc middle and Lunatus: mean response 0.2286, peak 0.3291
  - R Sulcus oc sup and transversal: mean response 0.2246, peak 0.3383
  - L Sulcus oc sup and transversal: mean response 0.2183, peak 0.2945
  - L Pole occipital: mean response 0.2146, peak 0.3453
  - R Pole occipital: mean response 0.1997, peak 0.3730
  - L Gyrus and Sulcus occipital inf: mean response 0.1985, peak 0.3637
  - R Gyrus occipital sup: mean response 0.1981, peak 0.3708
  - R Gyrus occipital middle: mean response 0.1912, peak 0.3605
  - R Gyrus oc-temp lat-fusifor: mean response 0.1869, peak 0.3197
  - R Sulcus oc-temp med and Lingual: mean response 0.1847, peak 0.3468
  - L Gyrus oc-temp lat-fusifor: mean response 0.1728, peak 0.3664
  - L Gyrus occipital middle: mean response 0.1687, peak 0.3016
  - R Sulcus precentral-sup-part: mean response 0.1590, peak 0.2551
  - R Gyrus and Sulcus occipital inf: mean response 0.1571, peak 0.2821
  - L Sulcus temporal transverse: mean response 0.1563, peak 0.2339
  - L Sulcus oc-temp med and Lingual: mean response 0.1527, peak 0.3386
  - R Sulcus temporal transverse: mean response 0.1511, peak 0.2078

## Files

- `roi_summary_overall.csv`
- `roi_summary_by_ad.csv`
- `manifest_summary.csv`
- `npz_status.csv`
- `ad_similarity.csv` when NPZ data is available
- `npz_roi_summary_by_ad.csv` when NPZ data is available
- `npz_roi_summary_common.csv` when NPZ data is available
- `figures/overall_top_rois.png`
- `figures/roi_heatmap_by_ad.png`
- `figures/ad_similarity_heatmap.png` when NPZ data is available
- `figures/common_mean_brain_map.png` when NPZ data is available
