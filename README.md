# Microsoft Certification Exams in JSON

> JSON files were automatically generated using [ms-cert-exam-parser].
>
> Check the latest commit for the date and time of the update.

## Why

I track my study progress on a few exams on Trello.
By having the data in JSON, you can transfer it more easily than copy-pasting.
The simplest example is to create a task list in Markdown.
Or you can go bigger and use Trello's API to create a board per each exam using the JSON data.
(or GitHub's API to create issues and lists... use whatever service you'd like)

## JSON Structure

Excerpt output from the [Python exam 98-381].

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

[ms-cert-exam-parser]: https://github.com/FurkanKambay/ms-cert-exam-parser
[Python exam 98-381]: https://www.microsoft.com/en-us/learning/exam-98-381.aspx
