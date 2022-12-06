# ChessProject
Recognition of a chessboard from an image using artificial neural networks.

Input: 2D image of online chess game

Output: Matrix with recognized chess pieces (chess pieces are represented by the initial letter of their name) 

The goal of this project was to get familiar with artificial neural networks and basics of NumPy, Pandas, OpenCV, Tensorflow, Matplotlib, Scikit-learn, and Keras libraries. The solution is based on already existing solutions and it confirms that the problem is solvable using some of the listed technologies and that it can be extended in the future.

Technologies used: Python, NumPy, Pandas, OpenCV, Matplotlib, Tensorflow, Keras, Scikit-learn.

Initial dataset was found on Kaggle https://www.kaggle.com/datasets/koryakinp/chess-positions and it was used for creating a new dataset which is used by the model. The new dataset consisted of folders whose names correspond to the names of the chess pieces (blackRook, whiteRook, blackBishop, whiteBishop, ...). All these folders were placed in 3 parent folders (train, test and validation). This way of organization is very common when it comes to datasets with images.

The solution is applicable to 2D images of online chess games and it can be extended to more complex scenarios.
