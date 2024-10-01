## Table name: death

### Reading from post_op__info

![](md_files/image34.png)

| Destination Field | Source field | Logic | Comment field |
| --- | --- | --- | --- |
| person_id | anon_case_no | Joined with PERSON.PERSON_SOURCE_VALUE for PERSON.PERSON_ID |  |
| death_date | death_date | SELECT * FROM post_op__info WHERE death_date IS NOT NULL; |  |
| death_datetime |  |  |  |
| death_type_concept_id |  |  | 32879	Registry |
| cause_concept_id |  |  |  |
| cause_source_value |  |  |  |
| cause_source_concept_id |  |  |  |

