# Gesture-Recognition-for-Sign-Language-Translation
This program will use gesture detection to help identify common ASL gestures as well as alphabets, translating them into sentences. These will be converted to speach using Google's TTS library. This application will be converted into a Android application for greater usability.


<br>

## Steps to run

1. Install all the required node modules by using `npm install` in the root working directory of the project.
2. Run the express server using the command `nodemon app.js`.
3. The default port is 3000 so open up `localhost:3000` on Google Chrome
4. Let the model load up before predicting the gestures


<br>

## File Descriptions

- `ML/`: Contains all files realted to data colelction, preprocessing and model training
  - `Model Training.ipynb`: Notebook containing various models and feature engineering techniques to comapre performance.
  - `data/`: Contains the compiled results as well as camera aspect ratio data
  - `model_saves/`: Contains the tensorflow checkpoints for the models trained in `Model Training.ipynb`

- `public/`: Files related to the webpage including the HTML/CSS files for page design aand JS scripts
  - `models/`: TensorflowJS models for the alphabet and gesture models 
 
- `index.js`: Nodejs base file to run the webpage


<br> 

## Video Demo


https://user-images.githubusercontent.com/46743379/155891806-f778c457-dad2-483e-9b3c-fdd23c3ea747.mp4



https://github.com/user-attachments/assets/f6803ae7-c3b8-4423-8d03-8da95c708164

![1](https://github.com/user-attachments/assets/02fe026d-b65b-4f71-9c80-3ec8aac3a112)
![2](https://github.com/user-attachments/assets/24de96a9-229b-44fe-9989-f93cde0294c2)
![5](https://github.com/user-attachments/assets/f0b66614-f146-45fd-a520-02dc0b5ed11b)
![4](https://github.com/user-attachments/assets/77e886e2-da1d-47f0-9657-578ff5e13a18)
![3](https://github.com/user-attachments/assets/32a25941-f44e-4763-9816-080b52cd5d23)
