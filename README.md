# AODnet-finetuned-on-IGP-fog
This repository is a part of a larger project made to be able to detect objects in foggy weather conditions of the Indo-Gangetic plains. The project focuses on providing effective solutions for motorcyclists. Conditions like the bike's speed, the model's latency, and reducing power consumption enough to provide good fps on a bike's battery are crucial.
This repository is specifically focused on developing an AOD net model.
It was first trained on the RESIDE outdoors dataset; the dataset was then augmented to simulate how IGP fog behaves into 3 categories: light, mid, and heavy fog. The models were thus trained on nearly 15k images. 
The next step is to include YOLO v8 nano to pair it with the AOD net for object detection.
