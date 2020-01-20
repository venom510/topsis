# Topsis
Topsis (Technique for Order of Preference by Similarity to Ideal Solution) is a technique used for choosing best out of available choices when the best choice is dependent on more than one parameter. So, basically it is a technique for multi-criteria decision making (MCDM).
So, this is a package which helps you to apply this technique to a dataset. The dataset should have all columns having numerical values. You have to pass the weights and impacts of each column in different strings while running the command. Impacts should contain either '+' sign or '-' sign where '+' denotes that the more the value for that column, more ideal it will be, and '-' denotes that the less the value for that column, more ideal it will be. And weights and impacts should be comma separated.

## How to make it work : 
Command for running the package will look like :</br>
python topsismnvu.py <dataset_name> \<weights> \<impacts>
</br>e.g. python topsismnvu.py dataset.csv "0.25,0.25,0.25,0.25" "+,-,+,+"
