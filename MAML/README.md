# cmpe297_hw4

Model-Agnostic Meta-Learning (MAML) is approch to make the AI learn/update its hyper-parameters automatically, so that we can reduce gradient descent computation steps. </br>
![image](https://user-images.githubusercontent.com/32551600/198854725-5a84dd5a-8207-444f-9a67-4130ce9b587a.png) </br>
The figure shows how MAML works: before move to next step (from gradient descent), it will take a batch of tasks, and compute all the tasks' gradient descent(in a inner loop). After all tasks done, we then would take a optimal step (based on all small steps). In this exercise, I praticed using MAML on Omniglot dataset.</br>
</br>
Colab Link: https://colab.research.google.com/drive/1JPZSp6_nOUTupmJHWYyHWTm_uGtWoVl0
</br>
</br>
Ref: https://keras.io/examples/vision/reptile/ 
