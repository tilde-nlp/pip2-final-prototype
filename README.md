# **Requirements**

 - [Unreal Engine 4](https://www.unrealengine.com/en-US/)
 - Additional UE4 plugins, for instance, [Runtime Audio Importer](https://www.unrealengine.com/marketplace/en-US/product/runtime-audio-importer), [VA REST](https://www.unrealengine.com/marketplace/en-US/product/varest-plugin), [Json Blueprint](https://www.unrealengine.com/marketplace/en-US/product/json-blueprint)
 - 3D model from [Metahuman Creators](https://metahuman.unrealengine.com/)
 - Your HUD setup for dialog
 - Emotion animations for 3D model
 - Connection variable keys should be bought from Tilde ([TildeAI](https://tilde.com/products-and-services/ai-powered-chatbots) (chatbot@tilde.com), [Machine Translation](https://tilde.com/products-and-services/machine-translation/pricing/Tilde-MT?lang=en) and [Tildes Balss](https://www.tilde.lv/tildes-balss) (balss@tilde.lv))

# **Setup**

![image](https://user-images.githubusercontent.com/49145687/173783150-ab4574ef-9936-4d38-a032-86edbbb510a4.png)

Create a new U4 project with Blueprint support, import 3D model from Metahuman Creator and add the blueprint structure for your 3D avatar as in BP_Laura7.uasset.
 
Import also VA2.uasset for connection structure to TildeAI dialog system. 
All [TildeAI](https://tilde.com/products-and-services/ai-powered-chatbots) (chatbot@tilde.com), [Machine Translation](https://tilde.com/products-and-services/machine-translation/pricing/Tilde-MT?lang=en) and [Tildes Balss](https://www.tilde.lv/tildes-balss) (balss@tilde.lv) connection variables should filled in with appropriate information, these connection links and keys should be bought separately from Tilde. 
Create emotion animations and add those to Frustration recognition step.

 ![image](https://user-images.githubusercontent.com/49145687/173783333-c42c9f11-ea37-442e-bcaf-2b567ad163ac.png)

Create a HUD and define the text input area, also you can add the field for showing the full dialog.

 ![image](https://user-images.githubusercontent.com/49145687/173783358-8e25a6e2-a9eb-4705-bd31-00a53490b1df.png)

# **Acknowledgment**
This research has been supported by the European Regional Development Fund within the joint project of SIA TILDE and University of Latvia “Multilingual Artificial Intelligence Based Human Computer Interaction” No. 1.1.1.1/18/A/148.
