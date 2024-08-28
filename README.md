# AI4Good-Project--Guido
For our final team project at the summer Machine Learning Program @ AI4Good Lab, we created an app called **Guido**, which **assists the visually impaired with crossing intersections by informing them of relevant details**. My contribution to this project was to fine-tune a **ResNet CNN** model using satellite images of different intersection road types (T, Cross, Offset) and wrap the tuned model with a **RESTful API** to facilitate deployment and integration with our app. This allows the visually impaired to identify the type of intersection they are facing, helping them navigate more safely before crossing.

Demo Day PowerPoint: https://docs.google.com/presentation/d/1PoiKOYTNQ0uf9tb0Zvn92_Rkea1BrCgiBuzAxGdXH-U/edit?usp=sharing

# What I have learned
1. Data Processing:<br>
Be able to implement image preprocessing and data augmentation with **PyTorch's transforms module**, including resizing, rotation, flipping, color jittering, and normalization techniques to enhance model performance.
   
2. ML Model Training:<br>
(1)Be able to use **Google Colab** as a platform for training and developing machine learning models.<br>
(2)Be able to use **PyTorch's DataLoader, models, transforms, torch.nn, nn.functional, and the Adam optimizer** to fine-tune pre-trained CNN models.

3. ML Model Evaluation:<br>
Be able to leverage **PyTorch's torchmetrics module**, including Accuracy and ConfusionMatrix, to evaluate the model's performance.

4. ML Model Deployment:<br>
Be able to use **Python Flask** to create a **RESTful API** that wraps a machine learning model for deployment on mobile devices.

   
