## Table name: observation

### Reading from pre_op__risk_index

![](md_files/image12.png)

| Destination Field | Source field | Logic | Comment field |
| --- | --- | --- | --- |
| observation_id | id |  |  |
| person_id | anon_case_no |  |  |
| observation_concept_id | high_risk_op<br>h_o_ihd<br>h_o_chf<br>h_o_cva<br>dm_on_insulin<br>asa_class<br>cri_functional_status<br>cardiac_risk_index<br>cardiac_risk_class<br>hypertension<br>history_of_osa<br>loud_snoring<br>daytime_tiredness<br>apnoea |  |  |
| observation_date | session_startdate |  |  |
| observation_datetime |  |  |  |
| observation_type_concept_id |  |  |  |
| value_as_number | cardiac_risk_index |  |  |
| value_as_string | h_o_ihd<br>h_o_chf<br>h_o_cva<br>dm_on_insulin<br>asa_class<br>cri_functional_status<br>cardiac_risk_class<br>hypertension<br>history_of_osa<br>loud_snoring<br>daytime_tiredness<br>apnoea |  |  |
| value_as_concept_id |  |  |  |
| qualifier_concept_id |  |  |  |
| unit_concept_id |  |  |  |
| provider_id |  |  |  |
| visit_occurrence_id |  |  |  |
| visit_detail_id |  |  |  |
| observation_source_value | high_risk_op<br>h_o_ihd<br>h_o_chf<br>h_o_cva<br>dm_on_insulin<br>asa_class<br>cri_functional_status<br>cardiac_risk_index<br>cardiac_risk_class<br>hypertension<br>history_of_osa<br>loud_snoring<br>daytime_tiredness<br>apnoea |  |  |
| observation_source_concept_id |  |  |  |
| unit_source_value |  |  |  |
| qualifier_source_value |  |  |  |
| value_source_value |  |  |  |
| observation_event_id |  |  |  |
| obs_event_field_concept_id |  |  |  |

### Reading from pre_op__others

![](md_files/image13.png)

| Destination Field | Source field | Logic | Comment field |
| --- | --- | --- | --- |
| observation_id | id |  |  |
| person_id | anon_case_no |  |  |
| observation_concept_id | forget_prescribed_medications<br>no_of_prior_hospital_admissions<br>continence |  |  |
| observation_date | session_startdate |  |  |
| observation_datetime |  |  |  |
| observation_type_concept_id |  |  |  |
| value_as_number | no_of_prior_hospital_admissions |  |  |
| value_as_string | forget_prescribed_medications<br>continence |  |  |
| value_as_concept_id |  |  |  |
| qualifier_concept_id |  |  |  |
| unit_concept_id |  |  |  |
| provider_id |  |  |  |
| visit_occurrence_id |  |  |  |
| visit_detail_id |  |  |  |
| observation_source_value | forget_prescribed_medications<br>no_of_prior_hospital_admissions<br>continence |  |  |
| observation_source_concept_id |  |  |  |
| unit_source_value |  |  |  |
| qualifier_source_value |  |  |  |
| value_source_value | forget_prescribed_medications<br>no_of_prior_hospital_admissions<br>continence |  |  |
| observation_event_id |  |  |  |
| obs_event_field_concept_id |  |  |  |

### Reading from pre_op__char

![](md_files/image14.png)

| Destination Field | Source field | Logic | Comment field |
| --- | --- | --- | --- |
| observation_id | id |  |  |
| person_id | anon_case_no |  |  |
| observation_concept_id | smoking_history<br>alcohol_consumption<br>pregnancy_gender<br>presence_of_malignancy<br>allergy_information |  |  |
| observation_date | visit_date |  |  |
| observation_datetime |  |  |  |
| observation_type_concept_id |  |  |  |
| value_as_number |  |  |  |
| value_as_string | smoking_history<br>pregnancy_gender<br>alcohol_consumption<br>presence_of_malignancy |  |  |
| value_as_concept_id | allergy_information |  |  |
| qualifier_concept_id |  |  |  |
| unit_concept_id |  |  |  |
| provider_id |  |  |  |
| visit_occurrence_id |  |  |  |
| visit_detail_id |  |  |  |
| observation_source_value | smoking_history<br>alcohol_consumption<br>pregnancy_gender<br>presence_of_malignancy<br>allergy_information |  |  |
| observation_source_concept_id |  |  |  |
| unit_source_value |  |  |  |
| qualifier_source_value |  |  |  |
| value_source_value | allergy_information<br>smoking_history<br>alcohol_consumption<br>pregnancy_gender<br>presence_of_malignancy |  |  |
| observation_event_id |  |  |  |
| obs_event_field_concept_id |  |  |  |

