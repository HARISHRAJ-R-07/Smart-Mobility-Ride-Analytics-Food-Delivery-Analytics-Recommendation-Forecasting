Place the project dataset in this folder.

Expected dataset filename:
food_delivery_analytics_3000.xlsx

The uploaded project notebook currently loads the file using:
pd.read_excel('food_delivery_analytics_3000.xlsx')

If you keep the dataset inside this data/ folder, update that line to:
pd.read_excel('data/food_delivery_analytics_3000.xlsx')
