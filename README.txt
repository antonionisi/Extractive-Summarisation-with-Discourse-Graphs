The code expects a folder hierarchy similar to the one provided.
Edit the variable `dataset_path` in the first cell to contain the path to the dataset_folder

Make sure you have CUDA installed to run the code, as it requires GPU acceleration for efficient processing. The code can be run in a google colab notebook with runtime type `T4 GPU`


dataset_folder/
│
├── training/
│   ├── [training data files]  # Training data files
│   └── ...
│
├── test/
│   ├── [test data files]      # Test data files
│   └── ...
│
└── training_labels.json       # File containing labels for the training data