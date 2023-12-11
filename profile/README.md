# 🌾 BloomMate
**House Gardening with AI Chat using Tiium and SmartCottage**
> This software is part of a project for **a software engineering class at Hanyang University Information Systems Dept**.

> The class is in collaboration with **LG Electronics**.

> Download Link (Android) : https://drive.google.com/drive/folders/1misbKdk9KiIgrsmARhBsaBBLhtyIzM-k?usp=drive_link

![앱 배너](https://github.com/BloomMate/.github/assets/60422588/6c12efc2-af3a-4f83-b109-f2be6de1bd81)




## 💡 Abstract
BloomMate is an application designed to assist people in cultivating plants using Tiiun in LG's SmartCottage. The COVID-19 pandemic has led to a significant increase in home gardening, resulting in a growing market. To address this trend, BloomMate was created as a solution to the lack of applications that provide professional plant growth assistance. Many people face difficulties such as plant diseases or deaths due to the complexity of plant cultivation.

BloomMate offers key features in four categories:

1. Plant log management: Users can manage logs throughout the entire planting and harvesting process.
2. Easy plant cultivation: Detailed plant information, expert articles, Q&A, and AI plant diagnosis are provided to help users grow plants easily.
3. Enjoyable plant cultivation: Users can engage in chat functionality with an AI trained on the plants they are growing.
4. Guide appropriate user actions: AI provides customized information and encourages specific actions, such as one-click purchases.

These features aim to alleviate the difficulties users encounter when cultivating plants.

BloomMate consists of four modules: Frontend, Backend, Machine Learning, and Static Data Storage. All modules, except for Static Data Storage, were developed by team members and can be found on Github. The overall architecture follows the MVC pattern, and the Machine Learning module uses the resnet-50 model, which has been converted into a TensorFlow Lite model.

Currently, BloomMate can be downloaded as an APK file for Android via Google Drive. We are confident that BloomMate will enhance the gardening experience with Tiiun in LG's SmartCottage.

## 💡 Target Users
The target users of BloomMate are individuals who use SmartCottage's outdoor garden Tiiun. These users face the following issues:

1. Lack of information and knowledge about plants, resulting in difficulties in maintaining healthy plants.
2. Lack of interest in growing plants due to finding the process boring.
3. Desire to establish a connection with plants through chatting.

BloomMate offers suitable solutions for each of these pain points, including features such as plant chatting, plant diagnosis, Q&A, expert articles, and more.

## 💡 Main Functions
The core key features of BloomMate can be divided into four categories.

👆 **Plant Log Management**

- Add plants
- Use AI to diagnose plants and view diagnosis logs
- Delete diseased plants
- Harvest plants and view the harvested plant list
- View conversation history with AI

👆 **Easy Plant Care**

- Get growing tips for specific plants from plant details
- Access high-quality information through expert articles
- Ask questions through Q&A
- Check for diseases using AI plant diagnosis

👆 **Enjoyable Plant Care**

- Receive daily reports created by generative AI as the plant you are growing
- Engage in free chat with generative AI as the plant you are growing

👆 **Guidance on Appropriate User Actions**

- Provide personalized information using generative AI
- Easily prompt specific actions using generative AI
    - Order new seeds when a plant is diseased
    - Order new fertilizer when there are soil issues

## 💡 Architecture Design

<img width="1200" alt="image" src="https://github.com/BloomMate/.github/assets/60422588/9212da3a-733e-4923-a704-b2cf382dd208">



## 🔗 Links

|Name(Link)|Tool|
|----------|----|
|[UI-UX Design](https://www.figma.com/file/pAob8LLoxAzJst4vmosErD/SE-Plant?type=design&node-id=321-349amode=design&t=SiQVXpMyvYqygplQ-0)|Figma|
|[Demo Video](https://youtu.be/hUYt6bMIOu4)|Youtube|
|[BloomMate Blog](https://bloommate.notion.site/About-BloomMate-4a8d8dfca7ed4ef9937b4f1641e0a53d?pvs=4)|Notion|
|[Project Blog](https://medium.com/@akainoo/bloommate-project-blog-f7e30e2f57ff)|Medium|
|[ERDiagram](https://dbdocs.io/ash1823/BloomMate)|dbdcos|
|[API Design](https://documenter.getpostman.com/view/29752660/2s9YR9ZDKr)|Postman|

## Contributers
|**`Name`**|**`Dept`**|**`E-mail`**|**`Role`**|
|----------|----------|------------|----------|
|Kim Donghyun|Dept. of Information systems|akainoo@hanyang.ac.kr|AI Developer<br />Frontend Developer|
|An Soonho|Dept. of Information systems|ash1823@hanyang.ac.kr|Backend Developer|
|Shin Hyunah|Dept. of Information systems|hyunah0923@hanyang.ac.kr|Frontend Developer<br />Product Designer|
|Yoon Yongsung|Dept. of Information systems|mirr001003@hanyang.ac.kr|Frontend Developer  <br />UI-UX Designer| 
