Paper Title:  Knowing what and how: a multi-modal aspect-based framework for complaint detection
    
Conference: European Conference on Information Retrieval (ECIR) 2023

Dataset: Aspect Category, Aspect-level Complaint/Non-Complaint Label annotated dataset for Multimodal Aspect-Based Complaint Dataset (CESAMARD-Aspect)


Description: The CESAMARD-Aspect consists of 3962 multimodal complaint reviews (texts and images) in English. Each record in the dataset consists of review text, review image (user-uploaded) domain, review title, complaint labels (overall) and corresponding annotations for aspect category, aspect-level complaint/non-complaint labels.

There are two classes for the Complaint task, i.e, 0: non-complaints and 1: complaints. 


For the aspect category task following are the classes corresponding to each domain:

Books: Content, Packaging, Price, Quality

Edibles: Taste, Smell, Packaging, Price, Quality

Electronics: Design, Software, Hardware, Packaging, Price, Quality

Fashion: Colour, Style, Fit, Packaging, Price, Quality

Miscellaneous: Packaging, Price, Quality


All domains share three common aspect categories, namely packaging, price, and quality because these aspects are relevant for products purchased online.


In the csv file following are the dependencies:

Packaging = packaging+ service labels in the dataset (for all the domains)     
 
For Fashion domain: Quality= quality+fabric+category+texture; fit= fit+shape





For citation:

@inproceedings{singh2023knowing,
  title={Knowing what and how: a multi-modal aspect-based framework for complaint detection},
  author={Singh, Apoorva and Gangwar, Vivek and Sharma, Shubham and Saha, Sriparna},
  booktitle={European Conference on Information Retrieval},
  pages={125--140},
  year={2023},
  organization={Springer}
}
