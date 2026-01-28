# legal-case-finder

## Project Overview

Legal Case Finder for Lawyers is an AI-based system designed to help lawyers and legal professionals efficiently retrieve relevant legal cases based on user queries. The system aims to reduce manual legal research time by using semantic search and AI-based techniques.

## Problem Statement

Traditional keyword-based legal search systems fail to capture the contextual meaning of legal queries, making it difficult for lawyers to find the most relevant past cases. This project addresses this problem by building a semantic legal case retrieval system.

## Dataset

- **Source**: Indian Supreme Court Judgments (Kaggle)
- **File name**: cases.csv
- **Description**: This dataset contains metadata of Indian Supreme Court cases, including case numbers, parties involved, advocates, bench details, and judgment information. It is used for building a legal case retrieval system.
- **Number of records**: 47,400
- **Number of columns**: 12
- **Columns**:
  - diary_no
  - Judgement_type
  - case_no
  - pet (Petitioner)
  - res (Respondent)
  - pet_adv (Petitioner Advocate)
  - res_adv (Respondent Advocate)
  - bench
  - judgement_by
  - judgment_dates
  - temp_link
  - language

> Note: This dataset primarily contains case metadata. Full judgment texts will be incorporated in later stages for semantic search and RAG implementation.

## Current Progress 

- Project repository and folder structure created
- Legal dataset collected and documented
- Initial understanding of data completed

## Future Work

- Text preprocessing and data cleaning
- Semantic search using sentence embeddings
- Vector database integration
- LLM-based Retrieval-Augmented Generation (RAG)
- User interface development
