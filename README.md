# avito-kaggle

Competition from kaggle
> Avito is challenging you to predict demand for an online advertisement based on its full description (title, description, images, etc.), its context (geographically where it was posted, similar ads already posted) and historical demand for similar ads in similar contexts. With this information, Avito can inform sellers on how to best optimize their listing and provide some indication of how much interest they should realistically expect to receive


Main training data file. 

```rain.csv``` - Train data.
  - ```item_id``` - Ad id.
  - ```user_id``` - User id.
  - ```region``` - Ad region.
  - ```city``` - Ad city.
  - ```parent_category_name``` - Top level ad category as classified by Avito's ad model.
  - ```category_name``` - Fine grain ad category as classified by Avito's ad model.
  - ```param_1``` - Optional parameter from Avito's ad model.
  - ```param_2``` - Optional parameter from Avito's ad model.
  - ```param_3``` - Optional parameter from Avito's ad model.
  - ```title``` - Ad title.
  - ```description``` - Ad description.
  - ```price``` - Ad price.
  - ```item_seq_number``` - Ad sequential number for user.
  - ```activation_date```- Date ad was placed.
  - ```user_type``` - User type.
  - ```image``` - Id code of image. Ties to a jpg file in train_jpg. Not every ad has an image.
  - ```image_top_1``` - Avito's classification code for the image.
  - ```deal_probability``` - The target variable. This is the likelihood that an ad actually sold something. It's not possible to verify every transaction with certainty, so this column's value can be any float from zero to one.
