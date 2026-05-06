# TRIBE Ad Brain-Pattern Analysis

- Generated: 2026-05-06T10:10:50
- Input root: `/Users/seong-yeob/Downloads/tribeproto`
- Interpretation note: these are TRIBE model-predicted fMRI-like responses, not direct experimental fMRI measurements.

## Input Inventory

- Included ad folders: 51
- Excluded folders: 0

## Manifest ROI Summary

- Parsed 6 manifest files and 710 frame rows.
- Overall most frequent ROIs:
  - R Gyrus orbital: 181 appearances, mean score 2.09, frame fraction 0.255
  - R Gyrus rectus: 167 appearances, mean score 2.14, frame fraction 0.235
  - L Gyrus orbital: 161 appearances, mean score 2.08, frame fraction 0.227
  - R Gyrus temporal inf: 153 appearances, mean score 2.11, frame fraction 0.215
  - L Gyrus rectus: 142 appearances, mean score 2.09, frame fraction 0.200
  - L Sulcus orbital med-olfact: 131 appearances, mean score 2.14, frame fraction 0.185
  - R Sulcus orbital med-olfact: 119 appearances, mean score 2.09, frame fraction 0.168
  - L Gyrus temporal inf: 109 appearances, mean score 2.19, frame fraction 0.154
  - R Gyrus and Sulcus cingul-Ant: 104 appearances, mean score 2.06, frame fraction 0.146
  - R Gyrus oc-temp med-Parahip: 103 appearances, mean score 2.13, frame fraction 0.145
  - R Gyrus front sup: 68 appearances, mean score 2.07, frame fraction 0.096
  - L Sulcus temporal inf: 67 appearances, mean score 2.15, frame fraction 0.094
  - L Gyrus oc-temp med-Parahip: 67 appearances, mean score 2.08, frame fraction 0.094
  - L Gyrus front middle: 67 appearances, mean score 2.04, frame fraction 0.094
  - R Gyrus subcallosal: 66 appearances, mean score 2.04, frame fraction 0.093
  - L Gyrus temporal middle: 61 appearances, mean score 2.09, frame fraction 0.086
  - R Gyrus and Sulcus subcentral: 56 appearances, mean score 2.22, frame fraction 0.079
  - L Sulcus circular insula sup: 54 appearances, mean score 2.41, frame fraction 0.076
  - R Sulcus orbital-H Shaped: 54 appearances, mean score 2.20, frame fraction 0.076
  - L Gyrus and Sulcus subcentral: 54 appearances, mean score 2.11, frame fraction 0.076

## Advertisement-Level Highlights

### Budweiser_Super_Bowl_LX_Commercial_American_Icons
- R Gyrus rectus: 30/121 frames, mean score 2.34
- L Gyrus temporal inf: 24/121 frames, mean score 2.27
- L Sulcus orbital med-olfact: 20/121 frames, mean score 2.43
- L Gyrus and Sulcus cingul-Ant: 20/121 frames, mean score 2.29
- L Sulcus pericallosal: 15/121 frames, mean score 2.78

### Considering_What_Paris_2024_Paralympic_Games
- R Gyrus orbital: 85/281 frames, mean score 2.19
- R Gyrus temporal inf: 83/281 frames, mean score 2.18
- L Gyrus orbital: 82/281 frames, mean score 2.19
- R Gyrus rectus: 59/281 frames, mean score 2.24
- L Gyrus rectus: 59/281 frames, mean score 2.18

### Good_Will_Dunkin
- L Gyrus rectus: 5/5 frames, mean score 2.16
- R Gyrus and Sulcus transv frontopol: 5/5 frames, mean score 2.16
- R Gyrus orbital: 4/5 frames, mean score 2.21
- R Gyrus temporal inf: 4/5 frames, mean score 2.04
- R Gyrus subcallosal: 3/5 frames, mean score 2.40

### Jurassic_Park..._Works_Big_Game_Commercial_2026_Xfinity
- R Gyrus rectus: 38/121 frames, mean score 2.13
- R Gyrus temporal inf: 34/121 frames, mean score 2.04
- R Gyrus front sup: 30/121 frames, mean score 2.07
- L Sulcus orbital med-olfact: 24/121 frames, mean score 2.14
- R Sulcus orbital med-olfact: 24/121 frames, mean score 2.14

### LAY_S_Last_Harvest_Super_Bowl_LX_Commercial
- R Gyrus orbital: 46/121 frames, mean score 1.94
- L Gyrus rectus: 38/121 frames, mean score 1.95
- L Sulcus orbital med-olfact: 36/121 frames, mean score 2.12
- L Gyrus orbital: 34/121 frames, mean score 1.96
- R Gyrus and Sulcus cingul-Ant: 32/121 frames, mean score 2.01

### The_Choice_Pepsi_Super_Bowl
- R Gyrus rectus: 22/61 frames, mean score 1.80
- L Gyrus front middle: 20/61 frames, mean score 1.80
- L Gyrus orbital: 16/61 frames, mean score 1.70
- L Gyrus front inf-Triangul: 14/61 frames, mean score 1.80
- L Gyrus rectus: 14/61 frames, mean score 1.78

## NPZ Pattern Analysis

- Valid NPZ prediction files: 51
- Included ads missing NPZ files: 0
- NPZ files should contain either a `preds` or `predictions` array with shape `n_predictions x n_features`.
- Per-ad brain surface maps are written to `figures/ad_brain_maps/`.
- Per-ad Destrieux ROI bar charts are written to `figures/ad_top_rois/`.

| Ad | NPZ status | Array key | Preds shape | Validation |
| --- | --- | --- | --- | --- |
| 2026년_버드_라이트_슈퍼볼_광고_맥주통_30초 | found_in_raw_data | predictions | 31x20484 | ok |
| America_Needs_Neighbors_Like_You_l_Redfin_x_Rocket_Mortgage | found_in_raw_data | predictions | 61x20484 | ok |
| Backstory_Levi_s_Behind_Every_Original | found_in_raw_data | predictions | 31x20484 | ok |
| Bananas_Instacart_Big_Game_Commercial | found_in_raw_data | predictions | 31x20484 | ok |
| Bet_On_Kendall_30_Fanatics_Sportsbook | found_in_raw_data | predictions | 31x20484 | ok |
| Budweiser_Super_Bowl_LX_Commercial_American_Icons | found_in_raw_data | predictions | 61x20484 | ok |
| Cadillac_Formula_1_Team_2026_Livery_Reveal_The_Mission_Begins | found_in_raw_data | predictions | 61x20484 | ok |
| Can_I_get_a_six_pack_quickly | found_in_raw_data | predictions | 31x20484 | ok |
| Can_t_Live_There_Homes.com | found_in_raw_data | predictions | 31x20484 | ok |
| Considering_What_Paris_2024_Paralympic_Games | found_in_raw_data | predictions | 228x20484 | ok |
| DraftKings_live_superbowl_LX | found_in_raw_data | predictions | 31x20484 | ok |
| Everybody_Coinbase | found_in_raw_data | predictions | 62x20484 | ok |
| Good_Will_Dunkin | found_in_raw_data | predictions | 61x20484 | ok;preds_rows_ne_manifest_predictions:61!=3 |
| Grubhub_Big_Game_2026_The_Feest | found_in_raw_data | predictions | 31x20484 | ok |
| HUNGRY_FOR_THE_TRUTH_Uber_Eats | found_in_raw_data | predictions | 61x20484 | ok |
| Hims_Big_Game_Ad_The_Rich_Live_Longer | found_in_raw_data | predictions | 61x20484 | ok |
| Is_there_more_to_life_than_more | found_in_raw_data | predictions | 61x20484 | ok |
| Jurassic_Park..._Works_Big_Game_Commercial_2026_Xfinity | found_in_raw_data | predictions | 61x20484 | ok |
| LAY_S_Last_Harvest_Super_Bowl_LX_Commercial | found_in_raw_data | predictions | 61x20484 | ok |
| Mike_Tyson_Takes_on_the_Fight_of_His_Life_in_Super_Bowl | found_in_raw_data | predictions | 31x20484 | ok |
| NERDS_Juicy_Gummy_Clusters_Big_Game_Commercial_ft._Andy_Cohen_Official_30_2026 | found_in_raw_data | predictions | 31x20484 | ok |
| NFL_Super_Bowl_LX_You_Are_Special | found_in_raw_data | predictions | 31x20484 | ok |
| New_Home_Google_Gemini_SB_Commercial_2026 | found_in_raw_data | predictions | 61x20484 | ok |
| Oakley_Meta_Athletic_Intelligence_is_Here_-_Part_One | found_in_raw_data | predictions | 31x20484 | ok |
| Oakley_Meta_Athletic_Intelligence_is_Here_-_Part_Two | found_in_raw_data | predictions | 31x20484 | ok |
| OpenAI_Super_Bowl_2026_Codex_You_Can_Just_Build_Things | found_in_raw_data | predictions | 61x20484 | ok |
| Pringles_Pringleleo | found_in_raw_data | predictions | 31x20484 | ok |
| RITZ_Island_Big_Game_2026_Commercial | found_in_raw_data | predictions | 31x20484 | ok |
| Relax_your_tight_end | found_in_raw_data | predictions | 61x20484 | ok |
| Salesforce_Big_Game_Ad_MrBeast_s_Vault | found_in_raw_data | predictions | 33x20484 | ok |
| Search_Party_from_Ring_Be_A_Hero_In_Your_Neighborhood | found_in_raw_data | predictions | 31x20484 | ok |
| Serena_Williams_Super_Bowl_LX_Commercial_Healthier_on_Ro | found_in_raw_data | predictions | 31x20484 | ok |
| Shake_Your_Bots_Off_-_SVEDKA_Big_Game_Commercial_2026 | found_in_raw_data | predictions | 31x20484 | ok |
| Sticky_Note_SB_LX_Commercial | found_in_raw_data | predictions | 31x20484 | ok |
| Super_Bowl_LX_Champion | found_in_raw_data | predictions | 61x20484 | ok |
| Superhero_Belt_Toyota | found_in_raw_data | predictions | 31x20484 | ok |
| Take_A_Look_Liquid_I.V._Game_Day_2026_Commercial | found_in_raw_data | predictions | 31x20484 | ok |
| The_Choice_Pepsi_Super_Bowl | found_in_raw_data | predictions | 31x20484 | ok |
| The_Expert_feat._Adrien_Brody_TurboTax_2026_Super_Bowl_Commercial_Official_TV_Ad_45 | found_in_raw_data | predictions | 46x20484 | ok |
| The_Game_is_Ours | found_in_raw_data | predictions | 31x20484 | ok |
| Unavailable_Big_Game_Commercial_2026_Squarespace | found_in_raw_data | predictions | 38x20484 | ok |
| Universal_Orlando_Resort_-_Lil_Bro | found_in_raw_data | predictions | 61x20484 | ok |
| VW_대대적인_초대_운전자를_모집합니다._빅_게임_스팟 | found_in_raw_data | predictions | 31x20484 | ok |
| Where_Dreams_Began_Toyota_X_NFL | found_in_raw_data | predictions | 31x20484 | ok |
| Wix_Harmony_Big_Game_Commercial_2026_The_New_Way_to_Create | found_in_raw_data | predictions | 31x20484 | ok |
| YES_BUENO_2026 | found_in_raw_data | predictions | 31x20484 | ok |
| boshi | found_in_raw_data | predictions | 31x20484 | ok |
| hellmans | found_in_raw_data | predictions | 31x20484 | ok |
| poppi_Super_Bowl_LX_Commercial_poppi | found_in_raw_data | predictions | 31x20484 | ok |
| 기도에_의존하며_사는_것을_멈춰라_60_스테이트팜_광고 | found_in_raw_data | predictions | 61x20484 | ok |
| 임무_SOS_신호_감지 | found_in_raw_data | predictions | 31x20484 | ok |

## Similarity

- `ad_similarity.csv` contains Pearson correlations between each ad's mean prediction vector.

## NPZ Destrieux ROI Summary

- `npz_roi_summary_by_ad.csv` ranks Destrieux ROIs from each ad's mean prediction vector.
- Common mean-pattern top ROIs:
  - L Sulcus collat transv post: mean response 0.4022, peak 0.4633
  - R Sulcus collat transv post: mean response 0.4015, peak 0.4852
  - R Sulcus oc middle and Lunatus: mean response 0.3493, peak 0.4814
  - L Sulcus oc middle and Lunatus: mean response 0.3380, peak 0.4591
  - R Sulcus oc sup and transversal: mean response 0.3286, peak 0.4807
  - L Sulcus oc sup and transversal: mean response 0.3266, peak 0.4405
  - R Gyrus occipital sup: mean response 0.2851, peak 0.5105
  - L Pole occipital: mean response 0.2848, peak 0.4588
  - R Gyrus occipital middle: mean response 0.2800, peak 0.5063
  - L Gyrus and Sulcus occipital inf: mean response 0.2789, peak 0.4765
  - R Pole occipital: mean response 0.2670, peak 0.4830
  - R Sulcus oc-temp med and Lingual: mean response 0.2617, peak 0.4835
  - R Gyrus oc-temp lat-fusifor: mean response 0.2576, peak 0.4400
  - L Gyrus occipital middle: mean response 0.2488, peak 0.4229
  - L Sulcus occipital ant: mean response 0.2437, peak 0.3473
  - R Sulcus occipital ant: mean response 0.2384, peak 0.3274
  - L Gyrus oc-temp lat-fusifor: mean response 0.2323, peak 0.4909
  - R Gyrus and Sulcus occipital inf: mean response 0.2316, peak 0.3813
  - L Sulcus oc-temp med and Lingual: mean response 0.2127, peak 0.4653
  - R Sulcus temporal transverse: mean response 0.2093, peak 0.2998

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
- `figures/ad_brain_maps/*.png` when NPZ data is available
- `figures/ad_top_rois/*.png` when NPZ ROI data is available
