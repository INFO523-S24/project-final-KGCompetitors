# Data
-   **[Dataset]**: Our dataset comes from the Kaggle competition we are competeing in, and it consists of around 22,000 essays submitted by students, all of which were written in response to a single assignment prompt, which required students to apply course concepts to a real-world scenario. We selected this dataset/competition because certain team members possess experience in NLP tasks, and it presents an opportunity to impart new skills to the rest of the team while tackling a tangible problem aligned with Kaggle's objective of detecting personally identifiable information (PII) within these essays. 

To safeguard student privacy, original PII in the dataset has been substituted with surrogate identifiers of similar types using a partially automated procedure. 70% of essays have been set aside for the test set, resulting in our team using other datasets to supplement our work for this project. (Supplemental dataset search is in progress).

The competition data is provided in JSON format, containing various components such as a document identifier, the complete essay text, a token list, details about whitespace, and token annotations. The documents underwent tokenization using the SpaCy English tokenizer.

# Codebook for [chosen] Dataset

## Variable Names and Descriptions:

-   **O**: Not a part of an entity constituting personal information
-   **NAME_STUDENT**: The full or partial name of a student that is not necessarily the author of the essay. This excludes instructors, authors, and other person names.
-   **EMAIL**: A student’s email address.
-   **USERNAME**: A student's username on any platform.
-   **ID_NUM**: A number or sequence of characters that could be used to identify a student, such as a student ID or a social security number.
-   **PHONE_NUM**: A phone number associated with a student.
-   **URL_PERSONAL**: A URL that might be used to identify a student.
-   **STREET_ADDRESS**: A full or partial street address that is associated with the student, such as their home address.

## Data Types:

-   **Column**: data type



