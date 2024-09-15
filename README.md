**Official implementation of SERAU-NET. Paper accepted at SIPAIM 2024 Conference.**

Additional Results of "SERAU-Net: Snapshot Ensemble-aided Region-Aware Attention based U-Net for Skin Lesion Segmentation" :-

1. Workflow of overall SERAU-Net model.
   
    ![SEMRANET_arch](https://github.com/user-attachments/assets/906b39b1-d55c-4bcb-8f94-480c1eb2afa2)

2. Architecture of baseline RA-Net model.
   
    ![RA_arch](https://github.com/user-attachments/assets/e0a8f3b1-e02b-42bc-a3fb-658d340a7488)
   
    3a. Heatmap images displaying some test images, its ground truth mask, the mask generated and the images generated after applying encoder lower, encoder higher, bottleneck and decoder respectively from PH2 dataset.
   
   ![ph2_Heatmap_1](https://github.com/user-attachments/assets/3aa85ab3-f265-48a2-8a74-d30af7f31daa)
   ![ph2_Heatmap_2](https://github.com/user-attachments/assets/bba1a3a8-b363-431d-ac20-92a7f6dd72fa)
   ![ph2_Heatmap_3](https://github.com/user-attachments/assets/c97325d2-9c2d-4b33-a708-8e912835a749)
   ![ph2_Heatmap_4](https://github.com/user-attachments/assets/4de39aea-6497-4f0a-bfdb-f70a5d6370a1)
   ![ph2_Heatmap_5](https://github.com/user-attachments/assets/ae3f70ed-5357-483a-8d9b-a5d7d73c55a9)

    3b. Training curves displaying the history of loss, dice score, IOU, recall, precision and accuracy while training and validating the model's performance on PH2 dataset.
   
    ![ph2_train curves](https://github.com/user-attachments/assets/91c4602d-8889-4efa-a791-2e657f3d0b43)

    3c. Graphical comparison displaying how the performance of baseline model is enhanced after the snapshot ensemble technique is performed on PH2 dataset.
   
    ![ph2_model comparison](https://github.com/user-attachments/assets/4bd01ede-fe6c-48fa-92e3-8773a763a20d)

    4a. Heatmap images displaying some test images, its ground truth mask, the mask generated and the images generated after applying encoder lower, encoder higher, bottleneck and decoder respectively from ISIC 2016 dataset.
   
   ![isic16_Heatmap_1](https://github.com/user-attachments/assets/ffd096e3-ef69-44f8-8851-ad37d784b53f)
   ![isic16_Heatmap_2](https://github.com/user-attachments/assets/a81fc0c7-876b-42aa-b6fa-d74899bf3c71)
   ![isic16_Heatmap_3](https://github.com/user-attachments/assets/94ff5f3a-849d-424d-8251-850e7d46c7a5)
   ![isic16_Heatmap_4](https://github.com/user-attachments/assets/2ace0e70-599b-4c3a-8a75-6ee8ce1f2c5a)
   ![isic16_Heatmap_5](https://github.com/user-attachments/assets/54610014-f84a-4713-b009-4c6d9f65ae44)

    4b. Training curves displaying the history of loss, dice score, IOU, recall, precision and accuracy while training and validating the model's performance on ISIC 2016 dataset.
   
    ![isic16_train curves](https://github.com/user-attachments/assets/f5a2f9ae-423e-4245-8e18-05d15a533171)
   
    4c. Graphical comparison displaying how the performance of baseline model is enhanced after the snapshot ensemble technique is performed on ISIC 2016 dataset.
   
    ![isic16_model comparison](https://github.com/user-attachments/assets/e7bce41d-74f4-4daa-90d9-7367dd614e7a)
