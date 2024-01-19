# Dish-from-Ingredients
The project aims to suggest dish from the image of available ingredients.<br />
This uses the following libraries and dependencies :<br />
-> Bing Image Downloader for Dataset<br />
-> Basic steps of Data Augmentation using Keras<br />
-> GroundedSAM for auto-annotations if images<br />
-> YoloV8 for Object Detection<br />
## Dataset
For Ingredient Detection : <br />
https://www.kaggle.com/datasets/nishchaygarg/food-ingredients-dataset?rvi=1 <br />
For Recipies from Detected Ingredients : <br /> 
https://www.kaggle.com/datasets/saldenisov/recipenlg/data
## Notebook Directory
- dataaugmentation.ipynb<br />
  - Used for Data Augmention<br />
- grounded-sam.ipynb<br />
  - Used for Auto Annotating Dataset<br />
- yolov8.ipnyb<br />
  - Used for training the Model<br />
- search.ipynb<br />
  - Used for recommending recipies<br />
  
## Final Weights
best.pt contains the final weights <br />
## Results
Following is the link to the final results : <br /> 
https://drive.google.com/file/d/1Piw-cMs7X48Sb6e0Ai_R2QAN8y8Vofsk/view?usp=drivesdk<br />
Due to repeated disconnectivity and long training hours, 12 out of 50 epochs were run.
## Report
Following is the report for summarising the project : <br />
https://docs.google.com/document/d/1PpAUkKeEsCXKjy35Uhju8UfXXaDVLMMWnAzn4FY26Yc/edit#heading=h.yb0qqakihcik <br />
