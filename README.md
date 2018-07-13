# antiquarian_networks
Using OCR data from digitised books to extract personal and institutional names and associations as a basis for social network analysis.

## Why use Open Refine for digitised texts?
For historians who have been using the site https://archive.org/ to access full texts of nineteenth-century antiquarian literature, it is clear that there is a vast repository of texts that could be mined in different ways, isolating different parts of a book for analysis.

One part of the texts that I am interested in is the subscribers list. This sometimes stretched to several pages, and recorded those who had placed subscriptions to support the publication, and receive at least one copy of the final text. Institutions also placed subscriptions, such as libraries or museums, and also special interest societies or associations.

Although subscriber lists are among one of the cleanest parts of a digitised text to examine (often each subscriber has their own line in the raw text file), there are still issues with the quality of the OCR (optical character recognition), which need to be tidied up before the list can be useful.

Moreover, a 'list' is not really that helpful for analysis. Most researchers will want to have several columns of data, which each subscriber forming a row in the table. Each record could then provide details concerning name, title, occupation and location (address or institution). Open Refine is helpful in splitting apart the lines of raw text, and providing a cleaner CSV (comma separated values) file at the end.
