Requirements
------------
- Python: 3.9.18
- Recommended environment: Jupyter Notebook

Used Libraries
--------------
This project uses the following Python libraries:

- pandas
- torch
- torchvision
- matplotlib

Make sure to install them with:

    pip install torch torchvision pandas matplotlib
    pip install scikit-learn

Project Structure
-----------------
The project is organized as follows:

- models/   → contains all trained models (.pt)
- results/  → contains accuracy and loss results per epoch (.pt)
- weights/  → contains manually saved weights for comparison (.pt)

How to Run
----------
Open the corresponding Jupyter Notebooks to run the experiments.  
If trained models are found in the `models/` directory, they will be loaded automatically;  
otherwise, they will be trained from scratch and saved.