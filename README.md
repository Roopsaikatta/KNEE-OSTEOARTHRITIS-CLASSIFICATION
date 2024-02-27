# KNEE-OSTEOARTHRITIS-CLASSIFICATION
Knee Osteoarthritis (OA) is a prevalent degenerative joint disorder characterized by the gradual deterioration of articular cartilage, 
leading to pain and impaired mobility. Early detection of the disease is crucial for timely intervention and improved patient outcomes.
Magnetic Resonance Imaging (MRI) is a widely utilized modality for assessing knee joint health, offering detailed anatomical information. However, 
accurate and efficient detection of knee osteoarthritis from MRI scans remains a challenging task. 
This project proposes an approach that employs deep transfer learning techniques to enhance the detection of knee osteoarthritis.
The methodology involves dropping out unwanted classes and further implementation of deep transfer learning methods.
We have successfully implemented a hybrid model, called the Inception-Resnet-V2. The model has procured an accuracy of 94.58%. 
Apart from the hybrid model, we have also implemented EfficientNetB3 and MobileNet architectures which have procured an accuracy of 93% and 54.58% respectively.
Amongst all the models that were implemented, the hybrid model has provided us promising results by achieving maximum accuracy. 
This model is then deployed in a custom web application implemented using Flask and Bootstrap
