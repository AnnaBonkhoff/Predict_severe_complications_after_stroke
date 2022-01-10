# Step-by-step description

Trained models, as described in our publication (to be added upon acceptance), have been saved via Pickle (https://wiki.python.org/moin/UsingPickle).

In order to reuse our trained models to predict in-hospital mortality or severe complications after acute ischemic strokes, first install jupyter notebook (https://jupyter.org/install). Furthermore, our jupyter notebook files need to be downloaded together with the respective .pkl-files that contain information on the trained models.

When run, the following clinical information need to be entered for each new patient (respective fields in the jupyter notebooks are marked):

#### Required patient information to generate new predictions

Age (in years)

Sex_female (0 male, 1 female)

care_at_home (0 no, 1 yes)

nursing_home (0 no, 1 yes)

Paresis (0 no, 1 yes)

Language_impairment (0 no, 1 yes)

Speech_impairment (0 no, 1 yes)

Swallowing_impairment (0 no, 1 yes)

Consciousness (1 awake, 2 somnolent, 3 comatose)

Ranking_Scale (0-6)

NIHSS (0-42)

Barthel_index_bladder_function (0, 5, 10)

Barthel_index_transition_bed_chair (0, 5, 10, 15)

Barthel_index_mobility (0, 5, 10, 15)

Comorbidity_diabetes_mellitus (0 no, 1 yes)

Comorbidity_hypertension (0 no, 1 yes)

Comorbidity_myocardial_infarct (0 no, 1 yes)

Comorbidity_previous_stroke (0 no, 1 yes)

Comorbidity_hypercholesterinaemia (0 no, 1 yes)

Comorbidity_atrial_fibrillation (0 no, 1 yes)

Comorbidity_atrial_fibrillation_newly_diagnosed (0 no, 1 yes)

Thrombolysis_iv (0 no, 1 yes)

Thrombectomy_thrombolysis_ia (0 no, 1 yes)

January (0 no, 1 yes)

February (0 no, 1 yes)

March (0 no, 1 yes)

April (0 no, 1 yes)

May (0 no, 1 yes)

June (0 no, 1 yes)

July (0 no, 1 yes)

August (0 no, 1 yes)

September (0 no, 1 yes)

October (0 no, 1 yes)

November (0 no, 1 yes)

December (0 no, 1 yes)

atherothrombotic (0 no, 1 yes)

embolic (0 no, 1 yes)

microangiopathic (0 no, 1 yes)

other_cause (0 no, 1 yes)

competing_causes (0 no, 1 yes)

unknown_cause (0 no, 1 yes)

Stenosis (0 no, 1 yes, large vessel occlusion)

Stenosis_not_evaluated (0 no, 1 yes)

Imaging_before_admission (0 no, 1 yes)

Time_onset_admission_below_1h (0 no, 1 yes)

Time_onset_admission_1_2h (0 no, 1 yes)

Time_onset_admission_2_3h (0 no, 1 yes)

Time_onset_admission_3_3h30mins (0 no, 1 yes)

Time_onset_admission_3_30_4h (0 no, 1 yes)

Time_onset_admission_4_6h (0 no, 1 yes)

Time_onset_admission_6_24h (0 no, 1 yes)

Time_onset_admission_24_48h (0 no, 1 yes)

Time_onset_admission_48h (0 no, 1 yes)
