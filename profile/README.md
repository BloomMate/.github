# 🌾 BloomMate
**House Gardening with AI Chat using Tiium and SmartCottage**
> This software is part of a project for **a software engineering class at Hanyang University Information Systems Dept**.

> The class is in collaboration with **LG Electronics**.

![앱 배너](https://github.com/BloomMate/.github/assets/60422588/83d8609b-5722-4aee-b3d6-3e3c8ca6d9f8)



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
The target user of BloomMate is the individual using the virtual outdoor flower bed Tiiun in SmartCottage. As they are using a fictional electronic device, the target user is also fictional. This target user faces the following problems:

1. Lack of information and know-how about plants - for people with a "brown thumb"
2. Boredom when it comes to growing plants
3. Desire to experience the connection of growing plants through a community

To address each pain point, BloomMate offers appropriate solutions such as chat with plants, plant diagnostics, Q&A, and expert articles.

## 💡 Main Functions
The key features of BloomMate can be divided into four categories:

👆 **Plant Log Management**

- Add plants
- Use AI to diagnose plants and check diagnosis logs
- Remove sick plants
- Harvest plants and view the harvested plant list
- Review conversation history with AI

👆 **Easy Plant Care**

- Get growing tips for specific plants from plant details
- Access high-quality information through expert articles
- Ask questions through Q&A
- Check for plant diseases using AI plant diagnosis

👆 **Enjoyable Plant Care**

- Receive daily reports from an AI with a plant's perspective
- Engage in free conversation with an AI that embodies a plant's perspective

👆 **Guidance on Appropriate User Actions**

- Provide personalized information using AI
- Prompt specific actions easily with AI, without inconvenience
    - Order new seeds when a plant is sick
    - Order new fertilizers when there are soil issues

## 🔗 Links

|Name(Link)|Tool|
|----------|----|
|[UI-UX Design](https://www.figma.com/file/pAob8LLoxAzJst4vmosErD/SE-Plant?type=design&node-id=321-349amode=design&t=SiQVXpMyvYqygplQ-0)|Figma|
|[Demo Video](https://www.youtube.com/watch?v=PZsC4clDS2c)|Youtube|
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
