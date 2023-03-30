### Entirely Unsupervised Approach for Change detection:

The model is trained to output a similarity score between two images without using any ground truth image masks. We use Siamese Networks for this & this model may prove to be useful in an alert system where if a higher than normal similarity is output from the model given two bi-temporal images of the same location, then it may be worth for the inspectors or the land authorities to take action.

![image](https://user-images.githubusercontent.com/51030860/228423379-c7b1c155-5492-452a-936f-f1ecae808810.png)
![image](https://user-images.githubusercontent.com/51030860/228423407-0058539d-7521-4f8b-a2e2-d14d76712a8d.png)
![image](https://user-images.githubusercontent.com/51030860/228423429-dea6b595-5c7f-4d6c-9f09-2b1815d586e1.png)

Sample output:
![image](https://user-images.githubusercontent.com/51030860/228423478-65fc7596-6bac-402d-b4e4-d7470a01701c.png)
