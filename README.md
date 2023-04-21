# Sepsis

Our group set out with a goal of detecting sepsis early in ICU patients through the use of machine learning. In 2019, a competition was held which challenged contestants to accomplish this exact task. Sepsis was such an interesting topic to help fix because of how deadly, costly, and common it is. Initially, our team explored multiple models that were established for large amounts of tabular data. We landed on XGBoost (the technique favored by the top four finishers in the competition) and a new, much less well-known library called CatBoost. We aimed to see which of these models could perform better. With a difficult-to-work-with dataset, we ran into a lot of issues which ultimately required creative solutions. CatBoost emerged as the stronger of the two models for predicting sepsis and for providing tools for reporting feature importance, which is highly valuable in clinical settings.

# How to run the sepsis prediction 
1.  Download data/beth.csv and data/emory.csv file to your local machine
2. Upload these two files to your google drive
3. Download the sepsisPrediction.ipynb file, upload it to google drive and open it in google colab
3. Replace the datapath in the import data section to the path you stored your data files
4. Download the pacakges and dependency: catboost
5. Run all code (This dataset is huge and requires a high ram environment that may not be satified with an unpaid colab account. If you run into issue, ignore the hyper parameter tunning pipline and use the optimal parameters for each model recorded in our report)

