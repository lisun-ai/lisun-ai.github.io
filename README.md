## Li Sun

Greetings! My name is Li Sun, coming from Hubei, China. I got my undergraduate degree in Bioinformatics from Southern University of Science and Technology. Before I came to Pitt, I was an intern at Microsoft Research Asia. My research interests include machine learning, computer vision and medical image analysis.

### Blogs

```markdown
Talk summary: Deep Learning over Heterogeneous Data: a challenge, a solution, and an application to Poly(A) signal prediction

This is a summary of talk given by Haohan Wang, who is a PhD candidate at Carnegie Mellon University. In this talk, the speaker first gave a brief introduction about convolutional neural network (CNN) and it's application in computer vision. Inspired by the biological structure of visual cortex, CNNs are artificial neural networks with multiple hidden convolutional layers between the input and output layers. They have been used extensively in many computer vision tasks. They have non-linear property and are capable of modeling complex functions.

Next, the speaker points out a shortcoming of CNN: It tend to focus on high frequency component of images. A simple experiment is performed to illustrated this. They randomly selected a few testing samples from MNIST dataset, which is a famous hand-writing digits dataset. Then Fourier transform is used to decompose the images into high frequency component and low frequency component. By feeding these components into trained CNN model, they found that CNN performs well on low frequency component of images, but the accuracy for high frequency component of images is very low. This suggest an insight: CNN can view the data at a much higher granularity than the human can, since the high frequency component is often overlooked by human. But the high frequency focusing behavior of CNN can also lead to problem: It can reduce the robustness of CNN model, especially for adversarial attack.
Moreover, the speaker introduced a method that can be used to strength the robustness of CNN. They use gray-level cooccurrence matrix (GLCM) to extract superficial patterns, then they project the model’s representation onto the subspace orthogonal to GLCM representation’s to introduce independence. The experiments reveal that this method can improve model's robustness and generalizability.

Finally, the speaker introduced an application of proposed method: Using CNN for Poly(A) signal prediction. Poly(A) signal is a biological DNA sequence that plays an important role in RNA splicing. The experiment show that their proposed method achieves better accuracy and have better generalizability than baseline methods.

This is a very interesting talk because the speaker reveals an insight about CNN and it's application. The talk is also concise and engaging.
```
