# Pinecone w/ LangChain Document Loaders


## 1  ```.docx``` directory loader and splitter

1. Create ```/docxs``` directory then place all .docx files inside 
2. Run app and all ```/docxs``` files within the directory will be loaded into your vector store
3. Use helper function to delet db 
4. Use Chat functions to test
5. Trace using LangServe

### Directory Structure 

```
├── pinecone-langchain-docx-dataloader.ipynb
├── docxs
│   ├── client_file_01.docx
│   ├── client_file_02.docx
│   ├── client_file_03.docx
```
---

## 2  ```.pdf``` directory loader and splitter
1. Create ```/pdfs``` directory then place all .docx files inside 
2. Run app and all ```.pdf``` files within the directory will be loaded into your vector store
3. Use helper function to delet db 
4. Use Chat functions to test
5. Trace using LangServe

### Directory Structure

```
├── pinecone-langchain-pdf-dataloader.ipynb
├── pdfs
│   ├── client_file_01.pdf
│   ├── client_file_02.pdf
│   ├── client_file_03.pdf
```
---

## 3 ```.csv``` directory loader and splitter

1. Create ```/csvs``` directory then place all .docx files inside 
2. Run app and all ```.csv``` files within the directory will be loaded into your vector store
3. Use helper function to delet db 
4. Use Chat functions to test
5. Trace using LangServe

### Directory Structure

```
├── pinecone-langchain-csv-dataloader.ipynb
├── pdfs
│   ├── client_file_01.csv
│   ├── client_file_02.csv
│   ├── client_file_03.csv
```
