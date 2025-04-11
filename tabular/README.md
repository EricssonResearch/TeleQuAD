# TeleQuAD: Telecom Question Answering Dataset for Tabular Data

A benchmark for the task of Question-Answering (QA) on tabular data in the telecom domain. This dataset was prepared by manually annotating a set of documents from the telecom domain, using, [3GPP Specifications](https://www.3gpp.org/specifications). 

## Dataset Format

The following is the format of the TeleQuAD Tabular dataset.

```json
{
    "version": "TeleQuAD-v1-full-Tabular",
    "description": "dataset_descriptive_text",
    "date": "release_date",
    "data_source": "dataset_source",
    "data": [
        {
            "questions": [
                {
                    "question": "question",
                    "answer": "relevant_answer",
                    "document_name": "document_filename",
                    "doc_name": "document_name",
                    "document_title": "document_title",
                    "start_page": "context_start_page",
                    "end_page": "context_end_page",
                    "section_number": "section_number",
                    "table_name": "table_name",
                    "question_type": "Type of question",
                    "context": "context from document",
                    "id": "question_uuid"
                }
            ]
        }
    ]
}
```

## Notes
- The questions are framed from a subset of tables present in the [3GPP documents, Rel 18](https://www.3gpp.org/specifications-technologies/releases/release-18). 
- The details of the concerning document (name and title), section name, table name, table caption, page numbers along with context are captured for every question. 
- The expected answer is present in `answer` field. 
- The answers can be just limited to a cell within the table, or might require extract information and/or aggregate across rows/columns and/or use logic. These have been captured for each question.