# TeleQuAD: Telecom Question Answering Dataset 

A benchmark for the task of Question-Answering (QA) in the telecom domain. This dataset was prepared by manually annotating a set of documents from the telecom domain, primarily using [3GPP Specifications](https://www.3gpp.org/specifications), and [sharetechnote](https://sharetechnote.com). 

## Notes

- This folder has the TeleQuAD ([`TeleQuAD-v4-full.json`](./TeleQuAD-v4-full.json)) dataset with 4485 questions.
- The dataset is provided in the `JSON` format given below. 
    - For a document (identified by `docid`, having `title` and `source`), `paragraphs` is a list of paragraphs (with associated question-answers (`qas`) and `context`(s)) extracted from the document. 
    - The `qas` is a list of questions with `id`, question `type` and a list of corresponding `answers`. Each answer comprises of the relevant answer in `text`, followed by start and end index of the text from the `context` (`answer_start` and `answer_end` respectively).

```json
{
    "version": "version",
    "description": "Telecom Question Answering Dataset",
    "date": "release_date",
    "data": [
        {
            "docid": "document_identifier",
            "title": "document_title",
            "source": "document_source",
            "paragraphs": [
                {
                    "qas": [
                        {
                            "id": "question_uuid",
                            "type": "question type - short, long, etc",
                            "answers": [
                                {
                                    "text": "relevant answer in text",
                                    "answer_start": "start index of answer in context",
                                    "answer_end": "end index of answer in context",
                                    "contributor": "contributor_id"
                                }
                            ],
                            "is_impossible": "True/False - whether the question can be answered from the given context",
                            "contributor": "contributor_id"
                        }
                    ],
                    "context": "Context from document"
                }
            ]
        }
    ]
}
```

