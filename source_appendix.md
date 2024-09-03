# Appendix: source tables

### Table: pre_op__char

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0001603518 |  |
| id | INT64 | 203862 |  |
| anon_case_no_clindoc | STRING | CN_0001603518 |  |
| session_id | INT64 | 1083948 |  |
| operation_id | INT64 | 2195518 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2016-08-02 |  |
| session_enddate | DATE | 2016-08-02 |  |
| operation_startdate | DATE | 2016-08-02 |  |
| operation_enddate | DATE | 2016-08-02 |  |
| operation_starttime | TIME | 11:00:00.000 |  |
| operation_endtime | TIME | 10:50:00.000 |  |
| admit_visit_patient_class_description | STRING | Class C |  |
| visit_date | DATE | 2016-08-02 |  |
| age_time_of_surgery | FLOAT64 | 29.0 |  |
| gender | STRING | FEMALE |  |
| race | STRING | Chinese |  |
| resident_indicator | BOOL | 0 |  |
| allergy | BOOL | 1 |  |
| allergy_information | STRING | NULL |  |
| preop_diagnosis | STRING | NULL |  |
| proposed_operation | STRING | NULL |  |
| admission_type | STRING | Inpatient |  |
| smoking_history | STRING | No |  |
| any_steroids_past_6_months | STRING | No |  |
| current_herbal_treatment | BOOL | 1 |  |
| rapid_assessment | STRING | NULL |  |
| any_aspirin_warfarin_anti_platelet_past_2_weeks | STRING | No |  |
| alcohol_consumption | STRING | No |  |
| pregnancy_gender | STRING | Female |  |
| curr_tcm_herbal_treatment | BOOL | 1 |  |
| curr_tcm_herbal_treatment_notes | STRING | NULL |  |
| presence_of_malignancy | STRING | NULL |  |
| height | STRING | NULL |  |
| weight | STRING | NULL |  |
| bmi | STRING | NULL |  |
| systolic_bp | STRING | NULL |  |
| diastolic_bp | STRING | NULL |  |
| heart_rate | STRING | NULL |  |
| o2_saturation | STRING | NULL |  |
| o2_supplementaries | STRING | NULL |  |
| temperature | STRING | NULL |  |
| pain_score | STRING | NULL |  |
| physical_general | STRING | NULL |  |
| physical_cardio | STRING | NULL |  |
| physical_respiratory | STRING | NULL |  |

### Table: pre_op__lab

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0000bb5210 |  |
| id | INT64 | 2860996 |  |
| anon_case_no_clindoc | STRING | CN_0000bb5210 |  |
| session_id | INT64 | 1781764 |  |
| operation_id | INT64 | 2693281 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2016-10-27 |  |
| session_enddate | DATE | 2016-10-27 |  |
| operation_startdate | DATE | 2016-10-27 |  |
| operation_enddate | DATE | 2016-10-27 |  |
| operation_starttime | TIME | 09:20:00.000 |  |
| operation_endtime | TIME | 09:50:00.000 |  |
| preop_lab_test_description | STRING | SODIUM |  |
| preop_lab_result_value | FLOAT64 | 135.0 |  |
| preop_lab_collection_datetime | TIMESTAMP | 2016-08-04 02:30:00.000000 |  |
| operation_startdate_min | STRING | 2016-10-27 |  |

### Table: pre_op__others

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_00282e77f0 |  |
| id | INT64 | 200373 |  |
| anon_case_no_clindoc | STRING | CN_00282e77f0 |  |
| session_id | INT64 | 1685504 |  |
| operation_id | INT64 | 2921449 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2018-11-13 |  |
| session_enddate | DATE | 2018-11-13 |  |
| operation_startdate | DATE | 2018-11-13 |  |
| operation_enddate | DATE | 2018-11-13 |  |
| operation_starttime | TIME | 14:25:00.000 |  |
| operation_endtime | TIME | 16:30:00.000 |  |
| asa_score_aims | STRING | 2.0 |  |
| asa_score_eaf | STRING | NULL |  |
| social_support | STRING | Always |  |
| can_efs_be_done | STRING | NULL |  |
| cognition_test | STRING | No errors |  |
| mood | BOOL | 0 |  |
| forget_prescribed_medications | BOOL | 0 |  |
| health_description | STRING | 'Excellent' , 'Very good' , 'Good' |  |
| no_of_prior_hospital_admissions | STRING | 0 |  |
| continence | BOOL | 0 |  |
| medication_use | BOOL | 0 |  |
| functional_independence | STRING | 0 - 1 |  |
| efs_total_score | FLOAT64 | 2.0 |  |
| functional_performance | STRING | 0 - 10 s |  |
| nutrition | BOOL | 0 |  |
| ftsa | STRING | NULL |  |
| inhalation_burns | STRING | NULL |  |
| tbsa | STRING | NULL |  |

### Table: pre_op__radiology

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0006ccdd59 |  |
| id | INT64 | 689361 |  |
| anon_case_no_clindoc | STRING | CN_0006ccdd59 |  |
| session_id | INT64 | 1956238 |  |
| operation_id | INT64 | 2030027 |  |
| anon_accession_number | STRING | AN_222e5cc78c |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2019-09-23 |  |
| session_enddate | DATE | 2019-09-23 |  |
| operation_startdate | DATE | 2019-09-23 |  |
| operation_enddate | DATE | 2019-09-23 |  |
| operation_starttime | TIME | 10:05:00.000 |  |
| operation_endtime | TIME | 16:00:00.000 |  |
| category_two | STRING | CT |  |
| line_number | STRING | 1.0 |  |
| order_date | STRING | 2019-10-03 |  |
| order_time | STRING | 07:55:27 |  |
| procedure_name | STRING | CT Chest, Abdomen and Pelvis |  |
| result_item_code | STRING | CTCHEABDP |  |
| text | STRING | NULL |  |

### Table: pre_op__risk_index

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0001603518 |  |
| id | INT64 | 131068 |  |
| anon_case_no_clindoc | STRING | CN_0001603518 |  |
| session_id | INT64 | 1083948 |  |
| operation_id | INT64 | 2195518 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2016-08-02 |  |
| session_enddate | DATE | 2016-08-02 |  |
| operation_startdate | DATE | 2016-08-02 |  |
| operation_enddate | DATE | 2016-08-02 |  |
| operation_starttime | TIME | 11:00:00.000 |  |
| operation_endtime | TIME | 10:50:00.000 |  |
| high_risk_op | BOOL | 0 |  |
| h_o_ihd | BOOL | 0 |  |
| h_o_chf | BOOL | 0 |  |
| h_o_cva | BOOL | 0 |  |
| dm_on_insulin | BOOL | 0 |  |
| creatinine_2mg_dl | BOOL | 0 |  |
| last_creatinine | STRING | NULL |  |
| asa_class | STRING | II |  |
| cri_functional_status | STRING | Totally Independent |  |
| cardiac_risk_index | FLOAT64 | 0.0 |  |
| cardiac_risk_class | STRING | I |  |
| hypertension | STRING | No |  |
| history_of_osa | STRING | No |  |
| loud_snoring | STRING | No |  |
| daytime_tiredness | STRING | No |  |
| apnoea | STRING | No |  |
| bmi_35 | STRING | No |  |
| age_50 | STRING | No |  |
| neck_circumference_40cm | STRING | No |  |
| male_gender | STRING | No |  |
| serum_hco3_28_mmol_l | STRING | No |  |
| osa_risk_index | STRING | 0/Low Risk |  |
| osa_advisory | STRING | Patient has low risk for having moderate-to-severe OSA |  |
| ahi | STRING | NULL |  |
| cpap_use | STRING | NULL |  |
| cpap_settings | STRING | NULL |  |
| history_of_hypertension | STRING | No |  |
| act_risk | STRING | No |  |
| active_meds | STRING | NULL |  |
| unlisted_meds | STRING | NULL |  |
| gender | STRING | Female |  |
| history_of_motion_sickness | STRING | No |  |
| postop_nausea_smoking_history | BOOL | 0 |  |
| planned_treatment | STRING | No |  |
| postop_nausea_score | STRING | 39.0 |  |

### Table: intra_op__aims_vitals

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002b9155f |  |
| id | INT64 | 1072561684 |  |
| anon_pat_id | STRING | ID_e31b0d88a7 |  |
| session_id | INT64 | 1209893 |  |
| operation_id | INT64 | 2606572 |  |
| anon_account_no | STRING | CN_0002b9155f |  |
| sess_start_date | TIMESTAMP | 2017-07-26 07:05:00.000000 |  |
| sess_end_date | TIMESTAMP | 2017-07-26 11:45:00.000000 |  |
| opr_start_date | TIMESTAMP | 2017-07-26 07:05:00.000000 |  |
| opr_end_date | TIMESTAMP | 2017-01-13 11:20:00.000000 |  |
| vitalcode | STRING | PULSE_RATE |  |
| vital_num_value | STRING | 0.0 |  |
| vitaldt | TIMESTAMP | 2016-08-02 07:17:37.000000 |  |
| vital_date | DATE | 2017-07-26 |  |
| vital_time | TIME | 11:52:05.000 |  |

### Table: intra_op__drug_blocks

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_000cf699bf |  |
| id | INT64 | 233582 |  |
| anon_case_no_clindoc | STRING | CN_000cf699bf |  |
| session_id | INT64 | 1562959 |  |
| operation_id | INT64 | 2366103 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2021-11-25 |  |
| session_enddate | DATE | 2021-11-25 |  |
| operation_startdate | DATE | 2021-11-25 |  |
| operation_enddate | DATE | 2021-11-25 |  |
| operation_starttime | TIME | 11:35:00.000 |  |
| operation_endtime | TIME | 12:45:00.000 |  |
| med_1_id | STRING | FENTANYL (UG) |  |
| med_2_id | STRING | NULL |  |
| med_3_id | STRING | EXPUNKNOWN |  |

### Table: intra_op__drug_drug

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002b9155f |  |
| id | INT64 | 27800 |  |
| anon_case_no_clindoc | STRING | CN_0002b9155f |  |
| session_id | INT64 | 1209893 |  |
| operation_id | INT64 | 2606572 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2017-07-26 |  |
| session_enddate | DATE | 2017-07-26 |  |
| operation_startdate | DATE | 2017-07-26 |  |
| operation_enddate | DATE | 2017-07-26 |  |
| operation_starttime | TIME | 11:05:00.000 |  |
| operation_endtime | TIME | 16:20:00.000 |  |
| drug_name | STRING | EXPUNKNOWN |  |
| drug_class_name | STRING | EXPUNKNOWN |  |
| dose | FLOAT64 | 0.0 |  |
| volume | FLOAT64 | 0.0 |  |
| concentration | FLOAT64 | 0.0 |  |
| infusion_startdatetime | STRING | 2017-07-26 15:58:35 |  |

### Table: intra_op__drug_fluids

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_000222c560 |  |
| id | INT64 | 263186 |  |
| anon_case_no_clindoc | STRING | CN_000222c560 |  |
| session_id | INT64 | 1173463 |  |
| operation_id | INT64 | 2606572 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2017-01-13 |  |
| session_enddate | DATE | 2017-01-13 |  |
| operation_startdate | DATE | 2017-01-13 |  |
| operation_enddate | DATE | 2017-01-13 |  |
| operation_starttime | TIME | 11:00:00.000 |  |
| operation_endtime | TIME | 16:20:00.000 |  |
| fluid_name | STRING | BLOOD LOSS (ML) |  |
| fluid_volume_actual | FLOAT64 | 0.0 |  |
| fluid_volume_individual | FLOAT64 | 500.0 |  |
| fluid_type | INT64 | 3 |  |
| drug_name | STRING | EXPUNKNOWN |  |
| drug_class_name | STRING | EXPUNKNOWN |  |
| fluid_startdate | DATE | 2017-01-13 |  |
| fluid_starttime | TIME | 11:17:37.000 |  |
| fluid_enddate | STRING | NULL |  |
| fluid_endtime | TIME | 00:00:00.000 |  |

### Table: intra_op__drug_med

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002b9155f |  |
| id | INT64 | 864380 |  |
| anon_case_no_clindoc | STRING | CN_0002b9155f |  |
| session_id | INT64 | 1209893 |  |
| operation_id | INT64 | 2972441 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2017-07-26 |  |
| session_enddate | DATE | 2017-07-26 |  |
| operation_startdate | DATE | 2017-07-26 |  |
| operation_enddate | DATE | 2017-07-26 |  |
| operation_starttime | TIME | 11:05:00.000 |  |
| operation_endtime | TIME | 12:05:00.000 |  |
| medication_name | STRING | FENTANYL (UG) |  |
| dosage_individual | FLOAT64 | 5.0 |  |
| drug_name | STRING | FENTANYL |  |
| drug_class_name | STRING | ANALGESIC;OPIOID |  |
| medication_startdate | DATE | 2017-07-26 |  |
| medication_startdatetime | TIMESTAMP | 2016-08-02 07:20:26.000000 |  |

### Table: intra_op__nur_vitals

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_000222c560 |  |
| id | INT64 | 3689931 |  |
| anon_pat_id | STRING | ID_17057c979e |  |
| anon_case_no_clindoc | STRING | CN_000222c560 |  |
| document_name | STRING | NUR ICU SGH |  |
| document_item_name | STRING | SHS_NUR_VITALSIGNS_HEARTRATEBPM_NUM |  |
| document_item_desc | STRING | HEART RATE BPM FOR NURSE CHARTING VITAL SIGNS |  |
| document_item_left_label | STRING | NULL |  |
| document_item_right_label | STRING | SCORE |  |
| authored_datetime | TIMESTAMP | 2017-09-19 10:44:00.000000 |  |
| created_datetime | TIMESTAMP | 2017-01-13 13:44:39.000000 |  |
| updated_datetime | TIMESTAMP | 2017-01-15 02:57:31.000000 |  |
| value_text | STRING | 0 |  |

### Table: intra_op__operation

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0001603518 |  |
| id | INT64 | 302932 |  |
| anon_case_no_clindoc | STRING | CN_0001603518 |  |
| session_id | INT64 | 1083948 |  |
| operation_id | INT64 | 2195518 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2016-08-02 |  |
| session_enddate | DATE | 2016-08-02 |  |
| operation_startdate | DATE | 2016-08-02 |  |
| operation_enddate | DATE | 2016-08-02 |  |
| operation_starttime | TIME | 09:20:00.000 |  |
| operation_endtime | TIME | 10:50:00.000 |  |
| procedure_code | STRING | SI725U |  |
| procedure_description | STRING | UTERUS/CERVIX, HYSTEROSCOPY, DIAGNOSTIC, D&C |  |
| surgical_specialty | STRING | Gynaecology |  |
| session_duration | FLOAT64 | 40.0 |  |
| urgency | STRING | Elective |  |
| anon_surgeon_name | STRING | ID_ab042d9dad |  |
| surgeon_grade | STRING | CON |  |
| anon_plan_anaesthetist_1_name | STRING | ID_6f9bef3cf6 |  |
| plan_anaesthetist_1_type | STRING | ST_ANAES |  |
| anon_plan_anaesthetist_2_name | STRING | ID_2017b6371c |  |
| plan_anaesthetist_2_type | STRING | ST_ANAES |  |
| induction_airway_method | STRING | NULL |  |
| induction_airway_type | STRING | NULL |  |
| induction_regional_block | STRING | NULL |  |
| block_type | STRING | NULL |  |
| fluid_volume_sum | FLOAT64 | 85.17 |  |
| vital_code | STRING | ECG_RATE |  |
| vital_signs_result | FLOAT64 | 67.0 |  |
| vital_signs_taken_datetime | TIMESTAMP | 2016-08-02 07:19:04.000000 |  |
| vital_signs_taken_date | DATE | 2016-08-02 |  |
| vital_signs_taken_time | TIME | 11:19:04.000 |  |
| ot_code | STRING | R8 |  |
| ot_description | STRING | Ambulatory Surgery Centre OT 3 (GA) |  |
| ot_location_code | STRING | MOT |  |

### Table: post_op__blood_product

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002fc66a7 |  |
| id | INT64 | 63580 |  |
| anon_case_no_clindoc | STRING | CN_0002fc66a7 |  |
| session_id | INT64 | 1799059 |  |
| operation_id | INT64 | 2170888 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-09-24 |  |
| session_enddate | DATE | 2020-09-24 |  |
| operation_startdate | DATE | 2020-09-24 |  |
| operation_enddate | DATE | 2020-09-24 |  |
| operation_starttime | TIME | 08:50:00.000 |  |
| operation_endtime | TIME | 18:15:00.000 |  |
| human_albumin_soln_20 | STRING | NULL |  |
| human_albumin_soln_5 | STRING | NULL |  |
| cell_separator_platelets | STRING | NULL |  |
| fresh_frozen_plasma | STRING | NULL |  |
| rbc | STRING | NULL |  |
| autologous_blood | STRING | NULL |  |
| cryoprecipitate | STRING | NULL |  |
| pooled_platelets | STRING | NULL |  |
| blood_products_authored_date | DATE | 2020-09-25 |  |
| blood_products_authored_time | TIME | 06:00:00.000 |  |
| clinical_doc_name | STRING | NUR Intake and Output SGH |  |

### Table: post_op__clin_doc

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002fc66a7 |  |
| id | INT64 | 2509124 |  |
| anon_case_no_clindoc | STRING | CN_0002fc66a7 |  |
| session_id | INT64 | 1799059 |  |
| operation_id | INT64 | 2170888 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-09-24 |  |
| session_enddate | DATE | 2020-09-24 |  |
| operation_startdate | DATE | 2020-09-24 |  |
| operation_enddate | DATE | 2020-09-24 |  |
| operation_starttime | TIME | 08:50:00.000 |  |
| operation_endtime | TIME | 16:00:00.000 |  |
| postop_clindoc_authored_date | DATE | 2020-09-25 |  |
| anon_postop_clindoc_case_number | STRING | CN_0002fc66a7 |  |
| postop_clindoc_clinical_doc_name | STRING | ANA Acute Pain Service and Postoperative Record SGH |  |
| postop_clindoc_created_datetime | TIMESTAMP | 2020-09-25 09:07:00.000000 |  |
| postop_clindoc_entered_date | TIMESTAMP | 2020-09-24 20:00:00.000000 |  |
| postop_clindoc_item_description | STRING | SHS_ANA_PostOp_PainScoreRest_NUM |  |
| postop_clindoc_item_left_label | STRING | NULL |  |
| postop_clindoc_item_name | STRING | SHS_ANA_PostOp_PainScoreRest_NUM |  |
| postop_clindoc_item_right_label | STRING | Treatment Administered |  |
| postop_clindoc_value_text | STRING | NULL |  |
| postop_clindoc_value_text_sequence_num | INT64 | 1 |  |
| anon_postop_clindoc_visit_number | STRING | VN_0002fc66a7 |  |
| min_operation_date | DATE | 2020-09-24 |  |

### Table: post_op__discharge

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| external_hospital_code | STRING | EXPUNKNOWN |  |
| external_hospital_name | STRING | EXPECTED UNKNOWN |  |
| anon_case_no | STRING | CN_0001e645b7 |  |
| id | INT64 | 1823199 |  |
| anon_case_no_clindoc | STRING | CN_0001e645b7 |  |
| session_id | INT64 | 1081255 |  |
| operation_id | INT64 | 2115534 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2015-11-27 |  |
| session_enddate | DATE | 2015-11-27 |  |
| operation_startdate | DATE | 2015-11-27 |  |
| operation_enddate | DATE | 2015-11-27 |  |
| operation_starttime | TIME | 12:50:00.000 |  |
| operation_endtime | TIME | 13:30:00.000 |  |
| discharge_type_code | STRING | 7 |  |
| discharge_type_description | STRING | Follow-up at SOC |  |
| diagnosis_description | STRING | Hyperlipidaemia, unspecified |  |
| diagnosis_code | STRING | I10 |  |
| days_postop | STRING | >30 |  |
| diagnosis_date | TIMESTAMP | 2016-05-05 16:04:52.000000 |  |
| operation_date | TIMESTAMP | 2015-11-27 07:50:00.000000 |  |

### Table: post_op__discharge_diagnosis

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002fc66a7 |  |
| id | INT64 | 122176 |  |
| anon_case_no_clindoc | STRING | CN_0002fc66a7 |  |
| session_id | INT64 | 1799059 |  |
| operation_id | INT64 | 2170888 |  |
| anon_discharge_summaries_case_number | STRING | CN_0002fc66a7 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-09-24 |  |
| session_enddate | DATE | 2020-09-24 |  |
| operation_startdate | DATE | 2020-09-24 |  |
| operation_enddate | DATE | 2020-09-24 |  |
| operation_starttime | TIME | 08:50:00.000 |  |
| operation_endtime | TIME | 18:15:00.000 |  |
| discharge_summaries_authored_date | DATE | 2020-10-01 |  |
| discharge_summaries_entered_date | TIMESTAMP | 2020-09-30 20:00:00.000000 |  |
| discharge_summaries_item_name | STRING | SHS_Inpatient_ProgNote_HI_No1_TXT |  |
| discharge_summaries_value_text | STRING | NULL |  |
| min_operation_date | DATE | 2020-09-24 |  |

### Table: post_op__icu

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| icu_location | STRING | NULL |  |
| anon_case_no | STRING | CN_0002fc66a7 |  |
| id | INT64 | 7821728 |  |
| anon_case_no_clindoc | STRING | CN_0002fc66a7 |  |
| session_id | INT64 | 1799059 |  |
| operation_id | INT64 | 2030027 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-09-24 |  |
| session_enddate | DATE | 2020-09-24 |  |
| operation_startdate | DATE | 2020-09-24 |  |
| operation_enddate | DATE | 2020-09-24 |  |
| operation_starttime | TIME | 10:05:00.000 |  |
| operation_endtime | TIME | 16:00:00.000 |  |
| icu_discharge_date | STRING | NULL |  |
| icu_admission_date | STRING | NULL |  |
| icu_discharge_time | STRING | NULL |  |
| icu_admission_time | STRING | NULL |  |
| endotracheal_tube_size | STRING | NULL |  |
| resuscitation_status | STRING | NULL |  |
| resuscitation_all_data_authored_date | DATE | 2020-09-27 |  |
| resuscitation_all_data_authored_time | TIME | 06:00:00.000 |  |
| adrenaline_epinephrine_dose_mcg_kg_min | STRING | NULL |  |
| dobutamine_dose_mcg_kg_min | STRING | NULL |  |
| dopamine_dose_mcg_kg_min | STRING | NULL |  |
| morphine_dose_mg_hr | STRING | NULL |  |
| noradrenaline_dose_mcg_kg_min | STRING | NULL |  |
| vasopressin_dose_unit_hr | STRING | NULL |  |
| icu_inotropes_all_data_authored_date | DATE | 2020-09-27 |  |
| icu_inotropes_all_data_authored_time | TIME | 06:00:00.000 |  |
| endotracheal_tube_insertion_date | STRING | NULL |  |
| endotracheal_tube_removal_date | STRING | NULL |  |
| tracheostomy_tube_insertion_date | STRING | NULL |  |
| tracheostomy_tube_removal_date | STRING | NULL |  |

### Table: post_op__icu_clin_doc

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_d7e0e92767 |  |
| id | INT64 | 537772 |  |
| anon_case_no_clindoc | STRING | CN_d7e0e92767 |  |
| anon_case_no_2 | STRING | CN_d7e0e92767 |  |
| session_id | INT64 | 1733839 |  |
| operation_id | INT64 | 2747056 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-11-16 |  |
| session_enddate | DATE | 2020-11-16 |  |
| operation_startdate | DATE | 2020-11-16 |  |
| operation_enddate | DATE | 2020-11-16 |  |
| operation_starttime | TIME | 15:15:00.000 |  |
| operation_endtime | TIME | 15:40:00.000 |  |
| icu_clinical_doc_created_datetime | TIMESTAMP | 2020-10-12 01:07:13.000000 |  |
| icu_clinical_doc_entered_date | TIMESTAMP | 2019-02-05 19:00:00.000000 |  |
| icu_clinical_doc_item_description | STRING | NULL |  |
| icu_clinical_doc_value_text | STRING | NULL |  |
| icu_clinical_doc_value_text_sequence_num | INT64 | 1 |  |
| min_operation_date | DATE | 2020-10-15 |  |
| first_apache_score | STRING | NULL |  |
| last_apache_score | STRING | NULL |  |
| maximum_apache_score | STRING | NULL |  |

### Table: post_op__info

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_000222c560 |  |
| id | INT64 | 1474084 |  |
| anon_case_no_clindoc | STRING | CN_000222c560 |  |
| session_id | INT64 | 1173463 |  |
| operation_id | INT64 | 2606572 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2017-01-13 |  |
| session_enddate | DATE | 2017-01-13 |  |
| operation_startdate | DATE | 2017-01-13 |  |
| operation_enddate | DATE | 2017-01-13 |  |
| operation_starttime | TIME | 11:00:00.000 |  |
| operation_endtime | TIME | 16:20:00.000 |  |
| dose | STRING | NULL |  |
| dose_uom | STRING | MG |  |
| order_name | STRING | PARACETAMOL   TABLET |  |
| task_performed_from_datetime | STRING | 2017-12-01 08:32:00 |  |
| total_stay_in_days | FLOAT64 | 28.0 |  |
| hd_ica_stay | FLOAT64 | 40.2830555 |  |
| hospital_readmission | STRING | NULL |  |
| icu_stay_in_hours | FLOAT64 | 220.464166 |  |
| icu_readmission | BOOL | 0 |  |
| death_date | STRING | 2020-03-01 |  |
| postop_pain_score_movement | STRING | NULL |  |
| postop_pain_score_rest | STRING | NULL |  |
| postop_patient_satisfaction | STRING | NULL |  |
| satisfaction_at_analgesia_removal | STRING | NULL |  |
| post_ponv | STRING | NULL |  |

### Table: post_op__intake_output

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002fc66a7 |  |
| id | INT64 | 5604870 |  |
| anon_case_no_clindoc | STRING | CN_0002fc66a7 |  |
| session_id | INT64 | 1799059 |  |
| operation_id | INT64 | 2170888 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-09-24 |  |
| session_enddate | DATE | 2020-09-24 |  |
| operation_startdate | DATE | 2020-09-24 |  |
| operation_enddate | DATE | 2020-09-24 |  |
| operation_starttime | TIME | 08:50:00.000 |  |
| operation_endtime | TIME | 18:15:00.000 |  |
| urine_vol_ml | STRING | NULL |  |
| intake | INT64 | 0 |  |
| output | INT64 | 0 |  |
| net | INT64 | 100 |  |
| perioperative_details_authored_date | DATE | 2020-09-25 |  |
| perioperative_details_authored_time | TIME | 06:00:00.000 |  |
| hartmann_solution_infusion | STRING | NULL |  |
| sodium_chloride_0_9_infusion | STRING | NULL |  |
| dextrose_5_sodium_chloride_0_9_infusion | STRING | NULL |  |
| fluid_intake_output_authored_date | DATE | 2020-09-25 |  |
| fluid_intake_output_authored_time | TIME | 06:00:00.000 |  |
| hypocount_frequency | STRING | NULL |  |
| insulin_infusion_unit_hr | STRING | NULL |  |
| performed_datetime | STRING | NULL |  |
| random_blood_sugar_mmol_l | STRING | NULL |  |

### Table: post_op__lab

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_000442201a |  |
| id | INT64 | 722568 |  |
| anon_case_no_clindoc | STRING | CN_000442201a |  |
| session_id | INT64 | 1174646 |  |
| operation_id | INT64 | 2131794 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-08-21 |  |
| session_enddate | DATE | 2020-08-21 |  |
| operation_startdate | DATE | 2020-08-21 |  |
| operation_enddate | DATE | 2020-08-21 |  |
| operation_starttime | TIME | 08:50:00.000 |  |
| operation_endtime | TIME | 10:35:00.000 |  |
| postop_lab_collection_datetime_max | TIMESTAMP | 2015-07-30 01:33:00.000000 |  |
| postop_lab_collection_datetime_min | TIMESTAMP | 2015-07-30 01:33:00.000000 |  |
| postop_lab_test_desc | STRING | LYMPHOCYTE |  |
| postop_result_value_max | FLOAT64 | 103.0 |  |
| postop_result_value_min | FLOAT64 | 137.0 |  |
| operation_startdate_min | DATE | 2020-08-21 |  |

### Table: post_op__lab_micro

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0001e645b7 |  |
| id | INT64 | 799870 |  |
| anon_case_no_clindoc | STRING | CN_0001e645b7 |  |
| session_id | INT64 | 1081255 |  |
| operation_id | INT64 | 2115534 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2015-11-27 |  |
| session_enddate | DATE | 2015-11-27 |  |
| operation_startdate | DATE | 2015-11-27 |  |
| operation_enddate | DATE | 2015-11-27 |  |
| operation_starttime | TIME | 12:50:00.000 |  |
| operation_endtime | TIME | 13:30:00.000 |  |
| antibiotic_name | STRING | Expected Unknown |  |
| general_comments | STRING | NULL |  |
| micro_resulted_procedure_description | STRING | WOUND CULTURE |  |
| min_operation_date | DATE | 2015-11-27 |  |
| organism_description | STRING | METHICILLIN-RESISTANT S.AUREUS |  |
| reported_date | DATE | 2015-12-15 |  |
| reported_time | TIME | 11:13:00.000 |  |
| result_comments | STRING | NULL |  |
| sensitivity | STRING | S |  |
| specimen_collection_date | DATE | 2015-12-11 |  |
| specimen_collection_time | TIME | 13:02:00.000 |  |

### Table: post_op__labs_all

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_00002be09a |  |
| id | INT64 | 2911194 |  |
| anon_case_no_clindoc | STRING | CN_00002be09a |  |
| session_id | INT64 | 1801758 |  |
| operation_id | INT64 | 2195518 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2014-09-27 |  |
| session_enddate | DATE | 2014-09-27 |  |
| operation_startdate | DATE | 2014-09-27 |  |
| operation_enddate | DATE | 2014-09-27 |  |
| operation_starttime | TIME | 13:10:00.000 |  |
| operation_endtime | TIME | 13:50:00.000 |  |
| gen_lab_lab_test_code | STRING | FBC |  |
| gen_lab_lab_test_description | STRING | FBC |  |
| gen_lab_lab_resulted_order_test_code | STRING | MCV |  |
| gen_lab_lab_resulted_order_test_description | STRING | SODIUM |  |
| gen_lab_result_value | STRING | 136 |  |
| gen_lab_specimen_collection_date | DATE | 2017-09-26 |  |
| gen_lab_specimen_collection_time | TIME | 12:10:00.000 |  |
| gen_lab_specimen_received_date | DATE | 2017-09-26 |  |
| gen_lab_specimen_received_time | TIME | 12:33:00.000 |  |
| min_operation_date | DATE | 2014-09-27 |  |

### Table: post_op__pacu

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_0002fc66a7 |  |
| id | INT64 | 4193098 |  |
| anon_case_no_clindoc | STRING | CN_0002fc66a7 |  |
| session_id | INT64 | 1799059 |  |
| operation_id | INT64 | 2530786 |  |
| anon_pacu_case_number | STRING | CN_0002fc66a7 |  |
| anon_pacu_visit_number | STRING | VN_0002fc66a7 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2020-09-24 |  |
| session_enddate | DATE | 2020-09-24 |  |
| operation_startdate | DATE | 2020-09-24 |  |
| operation_enddate | DATE | 2020-09-24 |  |
| operation_starttime | TIME | 08:50:00.000 |  |
| operation_endtime | TIME | 10:50:00.000 |  |
| pacu_authored_date | DATE | 2020-09-24 |  |
| pacu_created_datetime | TIMESTAMP | 2020-09-24 14:43:43.000000 |  |
| pacu_item_description | STRING | Heart Rate BPM for Nurse Charting Vital Signs |  |
| pacu_item_left_label | STRING | Heart Rate (beats/min) |  |
| pacu_item_name | STRING | SHS_NUR_VitalSigns_HeartRateBPM_NUM |  |
| pacu_item_right_label | STRING | NULL |  |
| pacu_clinical_doc_name | STRING | NUR OT PACU FS SGH |  |
| pacu_entered_date | TIMESTAMP | 2020-09-23 20:00:00.000000 |  |
| pacu_value_text_sequence_num | INT64 | 1 |  |
| pacu_value_text | STRING | NULL |  |
| min_operation_date | DATE | 2020-09-24 |  |

### Table: post_op__renal

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_03d3d6a98a |  |
| id | INT64 | 62095 |  |
| anon_case_no_clindoc | STRING | CN_0204cb3158 |  |
| session_id | INT64 | 1750640 |  |
| operation_id | INT64 | 2745906 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2021-06-15 |  |
| session_enddate | DATE | 2021-06-16 |  |
| operation_startdate | DATE | 2021-06-15 |  |
| operation_enddate | DATE | 2021-06-11 |  |
| operation_starttime | TIME | 11:50:00.000 |  |
| operation_endtime | TIME | 16:00:00.000 |  |
| crrt_authored_date | DATE | 2018-09-03 |  |
| crrt_status | STRING | NULL |  |
| crrt_type | STRING | NULL |  |
| delivered_length_of_dialysis | STRING | NULL |  |
| dialysis_modality | STRING | NULL |  |
| dialysis_endtime | STRING | NULL |  |
| dialysis_starttime | STRING | NULL |  |

### Table: post_op__vasoactives

| Field | Type | Most freq. value | Comment |
| --- | --- | --- | --- |
| anon_case_no | STRING | CN_01569e414f |  |
| id | INT64 | 148081 |  |
| anon_case_no_clindoc | STRING | CN_01569e414f |  |
| session_id | INT64 | 1340927 |  |
| operation_id | INT64 | 2236041 |  |
| institution_code | STRING | SGH |  |
| session_startdate | DATE | 2019-07-27 |  |
| session_enddate | DATE | 2019-07-27 |  |
| operation_startdate | DATE | 2019-07-27 |  |
| operation_enddate | DATE | 2019-07-27 |  |
| operation_starttime | TIME | 09:35:00.000 |  |
| operation_endtime | TIME | 19:50:00.000 |  |
| adrenaline_dose_outcome | STRING | NULL |  |
| amiodarone_dose_mg_hr | STRING | NULL |  |
| dobutamine_dose_mcg_kg_min_outcome | STRING | NULL |  |
| dopamine_dose_mcg_kg_min_outcome | STRING | NULL |  |
| glyceryl_trinitrate_dose_mcg_min | STRING | NULL |  |
| vasopressin_dose_unit_hr_outcome | STRING | NULL |  |
| noradrenaline_dose_mcg_kg_min | STRING | NULL |  |

