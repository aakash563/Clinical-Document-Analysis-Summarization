# Clinical-Document-Analysis-Summarization
"Clinical Document Analysis and Summarization with SpaCy NER and BART Transformer"
Approach to the Solution:
Entity Extraction:

Used SpaCy's pre-trained NER (Named Entity Recognition) model (en_core_web_sm) to extract medical entities from the clinical document.
User Query:

Prompted the user to input a query to search within the document.
Section Retrieval:

Checked each sentence in the document and identified relevant sections that contain the user's query.
Summarization:

Utilized the BART (Facebook's Seq2Seq model) for text summarization.
Prepared the input for the summarization model using the AutoTokenizer.
Generated a summary with a maximum length of 256 tokens.
Print Results:

Printed the extracted medical entities, relevant sections based on the user's query, and the generated summary.
Screenshot of Results:


The screenshot should capture the output of the code execution, showing the extracted entities, relevant sections, and the generated summary based on the provided clinical document. Ensure that the screenshot includes the relevant sections of the output.
