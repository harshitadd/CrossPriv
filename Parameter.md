Number of training samples = 429 {smaller batch}
Number of training samples =     {larger batch}
Number of silos = 2 
Test Batch Size = 4 ( Reduced largely due to computational restrictions ) 
Train Batch Size = 4 

```
Note : DICOM images in the linked dataset are of the following dimension - [1024,1024]. In the provided code they were read as [3,128,128] (They are transformed into RGB images in accordance to the motivation provided at \cite{}). Please note that the main aim of the paper is not to provide a state of the art model to detect pneumonia using Chest-X Rays but rather demonstrate the efficacy of the cross-silo FL setup with the given use case. 
```
