# EcoSort Waste Management Assistant

Performed by Group 6:
- Frasiah Wanjiku
- Gisairo Mokeira
- Clement Otindo
- Myles Imbayi

Our goal for this challenge was to create a Waste Management Assistant that can:
1) Look at a photo of a waste item and can correctly identify what it is.
2) Can correctly identify an item from a text describing it.
3) Give recycling instructions for the item based on particular policies.

We achieved this by building:
1) A Convolutional Neural Network (CNN) model that analyzes and identifies waste from pictures.
2) A Text Classification model through the use of Traditional Machine Learning Models that help analyze and identify waste from text descriptions.
3) A Retrieval Augmented Generation (RAG) Model which looks up the right recycling rules and generates instructions based on the rule.
4) An all round Integrated Assistant system that combines all the three models into one, can classify any waste category either by the use of Images or Text, and will generate appropriate instructions and policies depending on the waste category.

Dataset Used:
1) Waste Descriptions (CSV File)
2) Waste Policy Documents (JSON File)
3) RealWaste Dataset 
