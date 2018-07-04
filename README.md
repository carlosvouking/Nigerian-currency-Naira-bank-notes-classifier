# Nigerian-currency-Naira-bank-notes-classifier
Hands on Image Classification using the FAST.AI  library for Nigerian currency: Naira bank notes.
I attempted to train a model without and with data augmentation in order to distinguish and compare the losses and accuracies in both cases.

I/ - Main interesting points to recall in building this classifier:

     . Make sure that the Cuda framework is always available through : torch.cuda.is_available()
     . The Cudnn pacakage containing some functions for accelerating the training should also be enabled.
     
     .The model was trained using a known pretrained architecture: resnext50
     . distinguishing between lr and lr_da with da :: for data augmentation.
     
     
  
