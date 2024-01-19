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
dataaugmentation.ipynb<br />
Used for Data Augmention<br />
grounded-sam.ipynb<br />
Used for Auto Annotating Dataset<br />
yolov8.ipnyb<br />
Used for training the Model<br />
search.ipynb<br />
Used for recommending recipies

