# I've made a Language Model that generates Shakespeare like Texts/Poems using LSTMs. The code is in Python and uses Keras.
Note: All the files are well documented and commented wherever I felt necessary

## To see the code open Shakespeare Text generation- Language Model.ipynb

Run the file named Shakespeare Text generation- Language Model.ipynb which does the following:
1. Imports all necessary requirements- mentiones explicitly as there are a lot, which is generally the case when using Machine    Learning Frameworks like Keras ;) 
2. Loads the Dataset and builds training set from it using a function from shakespeare_utils.py named build_data(), vectorises    it as well.
3. Now loads the pre-trained model saved in model_shakespeare_kiank_350_epoch.h5
4. Asks the user for the initial sentence and uses the function generate_output() from shakespeare_util.py to generate            subsequent outputs to complete the poem
