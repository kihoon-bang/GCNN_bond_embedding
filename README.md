# Bond-type embedded crystal graph convolutional neural network (BE-CGCNN)


# Installation

This project required Pytorch and Pymatgen



# Usage

For training and test, you need a dataset consist of structure files (cif format) and related properties data (id_prop.csv) in same directory (data_demo). Then, you can run training by following command:
```
python main.py data_demo
```

Then, you can get model_best.pth.tar which store model with best validation accuracy. You can run prediction by following command:
```
python predict.py data_demo
```



## Features

You can add your own features to atom_init.json file.



## Data Format

You need to write id_prop.csv file for the dataset. It is consist of two columns. The first column is a filename of structure file in dataset. The second column is a value of properties related to the structure. Note that the filename doesn't include '.cif' filename extension.




## License

CGCNN is released under the MIT License.

