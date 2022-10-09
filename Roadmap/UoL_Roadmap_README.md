
# UoL Roadmap CSV Documentation

## Columns
| Column                     | Description                                                                    | Example                                              |
|----------------------------|--------------------------------------------------------------------------------|------------------------------------------------------|
| Course_ID                  | ID of course                                                                   | CM1005                                               |
| Course_Name                | Name of course                                                                 | Fundamentals Of Computer Science                     |
| Course_Acronym             | Acronym commonly used for course                                               | HCW                                                  |
| Level                      | Academic level of course                                                       | 5                                                    |
| Status                     | Completion status of course                                                    | In Progress                                          |
| Status_Key                 | Numeric version of Status (See Keys)                                           | 7                                                    |
| Language                   | Programming language/languages taught in course if applicable                  | Python, Javascript                                   |
| Language_Key               | Numeric version of Language (See Keys)                                         | 1, 2                                                 |
| Specialization             | Specialization/Specializations the course belongs to (Level 6)                 | User Experience, Games Development, Virtual Reality  |
| Specialization_Key         | Numeric version of Specialization (See Keys)                                   | 3, 6, 7                                              |
| Syllabus Link              | Local path to PDF of course syllabus starting at UoL_Resources Directory       | UoL_Resources/Syllabus/CM2035-Syllabus.pdf           |
| Course_Specifications_Link | Local path to PDF of course specifications starting at UoL_Resources Directory | UoL_Resources/Course_Specifications/CM1020-Specs.pdf |
| Team_Assignments           | Number of team assignments in course if applicable                             | 2                                                    |
| Grade_Percentage           | Grade achieved in course as a percentage                                       | 74.5                                                 |
| Credits                    | Number of credit hours for the course                                          | 15                                                   |
## Keys

#### Language_Key

| Language   | Key |
|------------|-----|
| Javascript | 1   |
| C++        | 2   |
| Python     | 3   |

#### Specialization_Key

| Specialization                                | Key |
|-----------------------------------------------|-----|
| Data Science                                  | 1   |
| Machine Learning and Artificial Intelligence  | 2   |
| User Experience                               | 3   |
| Web and Mobile Development                    | 4   |
| Physical Computing and the Internet of Things | 5   |
| Games Development                             | 6   |
| Virtual Reality                               | 7   |

#### Status_Key

| Status          | Key |
|-----------------|-----|
| Not Started     | 1   |
| In Progress     | 2   |
| Completed       | 3   |
| Not Picked      | 4   |
| Not Taking      | 5   |
| RPL In Progress | 6   |
| RPL Complete    | 7   |