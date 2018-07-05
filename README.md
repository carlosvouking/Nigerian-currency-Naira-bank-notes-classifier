# Nigerian-currency-Naira-bank-notes-classifier
Hands on Image Classification using the FAST.AI  library for Nigerian currency: Naira bank notes.
I attempted to train a model without and with data augmentation in order to distinguish and compare the losses and accuracies in both cases.

* Main interesting points to recall in building this classifier:

     . Make sure that the Cuda framework is always available through : torch.cuda.is_available()
     
     . The Cudnn pacakage containing some functions for accelerating the training should also be enabled.
     
     .The model was trained using a known pretrained architecture: resnext50
     
     . distinguishing between lr and lr_da with 'da' standing for data augmentation. same for dlr and dlr_da for differential learning rates.
     
     . Training a model on small sized datasets: it's advisable to shrink the batch size(bs). Explicitely setting the bs according to the number of iterations or epochs set to train the classifier.
     
     . This model is practically the first one that I build using the practice tailored fast.ai library.
     
     . The model was trained with 32 images of each type of currency and validated with 15 images of each corresponding type of currency.
     
     . The classifier ended up being able to predict new images input with an accuracy of 99.17 %.
     
    
Challenge: further analysis on different currencies's type will be done to corroborate these results.  
    
     
     
     
     
  
