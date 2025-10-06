# How to use this package

Speficy the following fields:

- `title`: The title of your thesis
- `subtitle`: Optional subtitle
- `student_name`: Name of the student/author
- `lang`: language of the document "en" or "it"
- `student_gender`: Optional gender of the student used only if `lang = "it"`
- `degree_name`: Name of your degree
- `supervisors`: List of the supervisors (relatori), must always be a list even if there is a single name. For example `("Mario Rossi", )`
- `academic_year`: "20xx/20xx"
- `graduation_session`: Month and year of the graduation session
- `for_print`: Optional, if `true` the left margin of the page will be increased to account for binding
