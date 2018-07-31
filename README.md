# My Template for Machine Learning Competitions




## Idea & Purpose 
The idea for this template came up for me after couple DS competitions. The main purpose of the template is to organize the development flow. 

## Libraries
This template based on jupyter notebooks, and can be used for with jupyter lab as well. 

## Folders 
 * data  - folder for train and test datasets
 * scripts - folder for jupyter notebook scripts
 * submissions - folder for submission files 

## How to use?
After creating a submission file, scripts creates a file in the 'submissioms' folder. For the comnience purpose I used this trick, 

```javascript
%%javascript
var nb = IPython.notebook;
var kernel = IPython.notebook.kernel;
var command = "NOTEBOOK_FULL_PATH = '"  + nb.notebook_path + "'";
kernel.execute(command);
```

And then in python we have:
```python
print("NOTEBOOK_FULL_PATH:\n", NOTEBOOK_FULL_PATH)
```
which we can use for the file naming.

**Recomendation**: 
Copy a jupyter notebook with a new name e.g. script_1.ipyng -> script_2.ipyng. 


## TODO
- [ ] add templates for the CrossValidation (A new folder?)
- [ ] add templates for the ensemble learning 

