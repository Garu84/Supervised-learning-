# Supervised-learning
# Synthetic Dataset - Student Dropout

I created this dataset for Data Mining Activity I at the Universidad de la Costa.

**Size:** 500 students

## Included Variables
- **Demographic:** age, gender, place_of_origin
- **Academic:** high_school_avg, admission_test_score, first_semester_grades
- **Financial:** socioeconomic_level, has_scholarship, has_loan
- **Target variable:** dropout (Yes = dropped out / No = did not drop out)

## How I created the data
- I used simple random numbers with `numpy.random`
- I added **null values** to some columns (approx. 70 nulls in total)
- I manually added **outliers** (unusual ages, impossible grades, socioeconomic level 0, etc.)
- The “dropout” column depends somewhat on first-semester grades (higher probability of dropping out if the grade is low)

This dataset simulates real student data and meets all the requirements of the activity.
