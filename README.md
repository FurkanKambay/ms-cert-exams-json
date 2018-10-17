# Microsoft Certification Exams in JSON

> JSON files were automatically generated using [FurkanKambay/ms-cert-exam-parser](https://github.com/FurkanKambay/ms-cert-exam-parser) on October 17, 2018.

## Why

I track my study progress on a few exams on Trello.
By having the data in JSON, you can transfer it easily.
The simplest example is to create a task list in Markdown.
Or you can go big and use Trello's API to create a board per exam.
(or GitHub's API to create issues and lists... use whatever service you'd like)

## JSON Structure

Sample is from the [Python exam 98-381](https://www.microsoft.com/en-us/learning/exam-98-381.aspx).

``` jsonc
[
    {
        "label": "Perform Operations using Data Types and Operators (20-25%)",
        "skills": [
            {
                "label": "Perform data and data type operations",
                "items": [
                    "Convert from one data type to another type",
                    "Construct data structures",
                    "Perform indexing and slicing operations"
                ]
            },
            // other skills
        ]
    },
    // other syllabuses
]
```
