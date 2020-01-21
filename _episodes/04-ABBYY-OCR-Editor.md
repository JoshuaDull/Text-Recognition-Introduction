---
title: "ABBYY OCR Editor"
teaching: 30
exercises: 5
questions:
- "How do I OCR PDFs with tables?"
- "How do I change the language setting in ABBYY?"
objectives:
- "Understand how to extract tabular data from a PDF and export to Excel"
- "How to add new patterns/characters to "
keypoints:
- "ABBYY can OCR data tables and non-English texts"
- "We can train ABBYY to recognize new, unique characters"
---

### Working with Tables

Many PDFs include data in the form of tables. While recognizing the text and numbers in a table is straightforward, maintaing the table structure is more difficult. 

>## From PDF to Excel
>ABBYY can recognize the structure of data tables. It uses the lines seperating rows & columns to idenitify the data in each cell.
>
>1. In the ABBYY folder, right-click to open 'tables.pdf' in ABBYY FineReader.
>2. Click the 'Recognize Text' drop-down and select 'Open in OCR Editor'.
>3. ABBYY should recognize the tables in this PDF. ABBYY designates tables with blue shading.
>4. We can manually adjust columns and rows to match the table structure.
>5. Click 'Send to Excel', this will open the table in excel. We can edit or save the table from there.
>
{: .checklist}

### Non-Latin Text

ABBYY is not limited to English or Latin text. ABBYY has a robust list of languages that are supported. You can evern choose multiple languages if a document is multi-lingual.

>## Non-English OCR
>
>1. Right-click on PDF named 'Russian.pdf', select Open with ABBYY FineReader 14.
>2. Click the 'Recognize Text' drop-down and select 'Open in OCR Editor'. 
>3. Select Language as 'Russian' if not automatically detected.
>4. Click 'Recgonize' again and see how the results have improved. We can edit this PDF in the same way we would with an English text.
>
{: .checklist}

### Improving Pattern Recognition

ABBYY comes trained on many different alphabets and languages. Of course, ABBYY does not know every font used through history. Also, special characters or ligatures might not be in ABBYY's dictionaries. 

* We can enhance ABBYY's existing patterns through training. 
* You can custom train ABBYY from scratch or you can add to an existing pattern dictioanry.

>## Pattern Training and Gothic Fonts
> Typically, modern English is printed using Roman typeface. Other types like Blackletter Gothic are no longer popular, but were used in historic text. 
> Many historic texts in English use a combination of old and modern types. We can enhance our existing pattern dictionary by training ABBYY on the meanings of older style type.   
>
>1. Right-click on PDF named 'Non-Latin.pdf', select Open with ABBYY FineReader 14.
>2. Click the 'Recognize Text' drop-down and select 'Open in OCR Editor'. 
>
{: .checklist} 

