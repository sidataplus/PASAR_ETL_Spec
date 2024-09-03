## Table name: visit_occurrence

### Reading from pre_op__char

![](md_files/image7.png)

| Destination Field | Source field | Logic | Comment field |
| --- | --- | --- | --- |
| visit_occurrence_id |  |  |  |
| person_id | anon_case_no | Joined with PERSON.PERSON_SOURCE_VALUE for PERSON.PERSON_ID |  |
| visit_concept_id | admission_type | TODO: map standard concept ids |  |
| visit_start_date | session_startdate |  |  |
| visit_start_datetime |  |  |  |
| visit_end_date | session_enddate |  |  |
| visit_end_datetime |  |  |  |
| visit_type_concept_id |  |  | 32879	Registry |
| provider_id |  |  |  |
| care_site_id | institution_code |  |  |
| visit_source_value | session_id |  |  |
| visit_source_concept_id |  |  |  |
| admitted_from_concept_id |  |  |  |
| admitted_from_source_value |  |  |  |
| discharged_to_concept_id |  |  |  |
| discharged_to_source_value |  |  |  |
| preceding_visit_occurrence_id |  |  |  |

### Reading from post_op__discharge

![](md_files/image8.png)

| Destination Field | Source field | Logic | Comment field |
| --- | --- | --- | --- |
| visit_occurrence_id |  |  |  |
| person_id | anon_case_no |  |  |
| visit_concept_id |  |  |  |
| visit_start_date |  |  |  |
| visit_start_datetime |  |  |  |
| visit_end_date |  |  |  |
| visit_end_datetime |  |  |  |
| visit_type_concept_id |  |  | 32879	Registry |
| provider_id |  |  |  |
| care_site_id |  |  |  |
| visit_source_value |  |  |  |
| visit_source_concept_id |  |  |  |
| admitted_from_concept_id |  |  |  |
| admitted_from_source_value |  |  |  |
| discharged_to_concept_id |  |  |  |
| discharged_to_source_value | external_hospital_code |  |  |
| preceding_visit_occurrence_id |  |  |  |

