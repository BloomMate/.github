# 🌾 BloomMate
**House Gardening with AI Chat using Tiium and SmartCottage**
> This software is part of a project for **a software engineering class at Hanyang University Information Systems Dept**.

> The class is in collaboration with **LG Electronics**.

![배너](https://github.com/BloomMate/.github/assets/60422588/56d63d10-c5be-4ee7-9d95-40b4e203725f)


## 💡 Abstract
BloomMate is an application designed to assist people in growing plants using Tiiun in LG's SmartCottage. In South Korea, there has been a gradual increase in home gardening, particularly in rural homes after retirement, in 2023. However, there is a lack of applications that provide professional assistance in plant cultivation to align with this trend. Additionally, many people face difficulties such as plant diseases or plant death due to the high level of complexity involved in plant cultivation. BloomMate was created to address these issues.

The key features of BloomMate can be categorized into four areas:

1. Plant Log Management: Users can manage logs throughout the process of planting and harvesting plants.
2. Easy Plant Care: Users are provided with detailed plant information, expert articles, Q&A, and AI plant diagnosis to help them easily grow plants.
3. Enjoyable Plant Care: Users can engage in chat conversations with a generative AI that has knowledge about their plants.
4. Guide Appropriate User Actions: Customized information and specific actions, such as one-click purchases, are provided through the use of generative AI.

These features are expected to significantly reduce the difficulties that users encounter when growing plants.

BloomMate consists of four modules: Frontend, Backend, Machine Learning, and Static Data Storage. Except for Static Data Storage, all modules were created by team members and can be found on GitHub. The overall architecture follows the MVC pattern, and the Machine Learning module uses the Resnet-50 model, which has been converted to a TensorFlow Lite model.

Currently, the Android APK file for BloomMate can be downloaded through Google Drive. We are confident that BloomMate will be a valuable tool for enjoying a delightful horticultural life in SmartCottage's Tiiun.

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

## 🔗 Links

|Name(Link)|Tool|
|----------|----|
|[UI-UX Design](https://www.figma.com/file/pAob8LLoxAzJst4vmosErD/SE-Plant?type=design&node-id=321-349amode=design&t=SiQVXpMyvYqygplQ-0)|Figma|
|[Demo Video](https://youtu.be/hUYt6bMIOu4)|Youtube|
|[BloomMate Blog](https://bloommate.notion.site/About-BloomMate-4a8d8dfca7ed4ef9937b4f1641e0a53d?pvs=4)|Notion|
|[Tech Blog](https://medium.com/@akainoo/bloommate-project-blog-f7e30e2f57ff)|Medium|
|[ERDiagram](https://dbdocs.io/ash1823/BloomMate)|dbdcos|
|[API Design](https://documenter.getpostman.com/view/29752660/2s9YR9ZDKr)|Postman|

## Contributers
|**`Name`**|**`Dept`**|**`E-mail`**|**`Role`**|
|----------|----------|------------|----------|
|Kim Donghyun|Dept. of Information systems|akainoo@hanyang.ac.kr|AI Developer<br />Frontend Developer|
|An Soonho|Dept. of Information systems|ash1823@hanyang.ac.kr|Backend Developer|
|Shin Hyunah|Dept. of Information systems|hyunah0923@hanyang.ac.kr|Frontend Developer<br />Product Designer|
|Yoon Yongsung|Dept. of Information systems|mirr001003@hanyang.ac.kr|Frontend Developer  <br />UI-UX Designer| 
