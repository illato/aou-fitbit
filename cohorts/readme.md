Specifications provided to the All of Us Cohorts Builder:

---

|Cohort Name|Dataset|
| --- | ---:|
|Fitbit+Anxiety Disorder|All of Us Registered Tier Dataset v7|

|Cohort Definition|
| --- |
| Fitbit - Has Any Fitbit Data|
| AND|
| Conditions - Parent Anxiety disorder|

---

|Cohort Name|Dataset|
| --- | ---:|
|Fitbit+Depression/Anxiety|All of Us Registered Tier Dataset v7|

|Cohort Definition|
| --- |
| Fitbit - Has Any Fitbit Data|
| AND|
| Conditions - Parent Depressive disorder, Parent Anxiety disorder|

---

|Cohort Name|Dataset|
| --- | ---:|
|Fitbit-Depression/Anxiety|All of Us Registered Tier Dataset v7|

|Cohort Definition|
| --- |
| Fitbit - Has Any Fitbit Data|
| EXCLUDING|
| Conditions - Parent Depressive disorder, Parent Anxiety disorder|

---

|Cohort Name|Dataset|
| --- | ---:|
|Fitbit+Depression Disorder|All of Us Registered Tier Dataset v7|

|Cohort Definition|
| --- |
| Fitbit - Has Any Fitbit Data|
| AND|
| Conditions - Parent Depressive disorder|

---

The All of Us Datasets can be produced by running the queries defined in [`__1__get-combine-save_data___cleared_output.ipynb`](https://github.com/illato/aou-fitbit/blob/main/__1__get-combine-save_data___cleared_output.ipynb)
