# Computer Vision: Sample Questions and Answers

Costa Rica

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[brown9804](https://github.com/brown9804)

Last updated: 2025-07-16

----------

> Describe features of computer vision workloads on Azure

> [!NOTE]
> The questions and answers provided in this study guide are for practice purposes only and are not official practice questions. They are intended to help you prepare for the [AI-900 Microsoft certification exam](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-900). For additional preparation materials and the most up-to-date information, please refer to the [official Microsoft documentation](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-fundamentals/?practice-assessment-type=certification).

<details>
<summary><b>List of References</b> (Click to expand)</summary>

- [Custom Vision documentation - Quickstarts, Tutorials, API Reference](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/)
- [What is Custom Vision? - Azure AI services](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/overview)
- [Azure AI Custom Vision | Microsoft Azure](https://azure.microsoft.com/en-us/products/ai-services/ai-custom-vision)

</details>

<details>
<summary><b>List of questions/answers </b> (Click to expand)</summary>

- [Q1: Identifying AI Services for Sentiment Analysis](#q1-identifying-ai-services-for-sentiment-analysis)
- [Q2: Extracting Key Phrases from Text](#q2-extracting-key-phrases-from-text)
- [Q3: Translating Text Between Languages](#q3-translating-text-between-languages)
- [Q4: Detecting Language of Text](#q4-detecting-language-of-text)
- [Q5: Identifying Objects in Images](#q5-identifying-objects-in-images)
- [Q6: Extracting Text from Images](#q6-extracting-text-from-images)
- [Q7: Analyzing Speech for Keywords](#q7-analyzing-speech-for-keywords)
- [Q8: Detecting Anomalies in Data](#q8-detecting-anomalies-in-data)
- [Q9: Building Conversational Agents](#q9-building-conversational-agents)
- [Q10: Translating Speech in Real-Time](#q10-translating-speech-in-real-time)
- [Q11: Choosing the Right Azure Cognitive Service](#q11-choosing-the-right-azure-cognitive-service)
- [Q12: Identifying AI Services for Document Processing](#q12-identifying-ai-services-for-document-processing)
- [Q13: Extracting Data from Business Cards](#q13-extracting-data-from-business-cards)
- [Q14: Extracting Data from Medical Forms](#q14-extracting-data-from-medical-forms)
- [Q15: Extracting Information from Scanned Documents](#q15-extracting-information-from-scanned-documents)
- [Q16: Analyzing Images for Specific Criteria](#q16-analyzing-images-for-specific-criteria)
- [Q17: Identifying Computer Vision Tasks](#q17-identifying-computer-vision-tasks)

</details>


## Q1: Identifying AI Services for Sentiment Analysis

> Which service should you use to analyze customer reviews and determine whether they are positive, negative, or neutral?

**Options:**
- [x] A. Text Analytics `This is the correct answer because Text Analytics is used for analyzing unstructured text data, such as sentiment analysis.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for sentiment analysis.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for analyzing text data.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for sentiment analysis.`


## Q2: Extracting Key Phrases from Text

> Which service should you use to extract important phrases and keywords from a large collection of documents?

**Options:**
- [x] A. Text Analytics `This is the correct answer because Text Analytics is used for extracting key phrases and keywords from unstructured text data.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for extracting key phrases.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for analyzing text data.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for extracting key phrases.`


## Q3: Translating Text Between Languages

> Which service should you use to translate text from one language to another?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for translating text.`
- [x] B. Translator `This is the correct answer because Translator is used for translating text between different languages.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for translating text.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for translating text.`

## Q4: Detecting Language of Text

> Which service should you use to identify the language of a given text?

**Options:**
- [x] A. Text Analytics `This is the correct answer because Text Analytics includes language detection capabilities.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for detecting the language of text.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for detecting the language of text.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for detecting the language of text.`


## Q5: Identifying Objects in Images

> Which service should you use to identify and label objects in images, such as cars, trees, and buildings?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for identifying objects in images.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for identifying objects in images.`
- [x] C. Custom Vision `This is the correct answer because Custom Vision allows you to train a custom model to identify and label specific objects in images.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for identifying objects in images.`

## Q6: Extracting Text from Images

> Which service should you use to extract text from images, such as scanned documents or photos of signs?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for extracting text from images.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for extracting text from images.`
- [x] C. Optical Character Recognition (OCR) `This is the correct answer because OCR is used for recognizing and extracting text from images.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for extracting text from images.`

## Q7: Analyzing Speech for Keywords

> Which service should you use to analyze spoken language and extract keywords from audio recordings?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for analyzing spoken language.`
- [x] B. Speech to Text `This is the correct answer because Speech to Text is used for converting spoken language into text, which can then be analyzed for keywords.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for analyzing spoken language.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for analyzing spoken language.`

## Q8: Detecting Anomalies in Data

> Which service should you use to detect unusual patterns or anomalies in time-series data?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for detecting anomalies in time-series data.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for detecting anomalies in time-series data.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for detecting anomalies in time-series data.`
- [x] D. Anomaly Detector `This is the correct answer because Anomaly Detector is used for identifying unusual patterns or anomalies in time-series data.`

## Q9: Building Conversational Agents

> Which service should you use to create a chatbot that can understand and respond to user queries in natural language?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for building conversational agents.`
- [x] B. Language Understanding `This is the correct answer because Language Understanding (LUIS) is used for building natural language understanding models that can be integrated into chatbots.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for building conversational agents.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for building conversational agents.`

## Q10: Translating Speech in Real-Time

> Which service should you use to translate spoken language in real-time during a conversation?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, not for translating spoken language.`
- [x] B. Speech Translation `This is the correct answer because Speech Translation is used for translating spoken language in real-time during conversations.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for translating spoken language.`
- [ ] D. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for translating spoken language.`

## Q11: Choosing the Right Azure Cognitive Service

> You are developing a solution to analyze images from grocery stores and identify various fruits and vegetables. The solution will use a custom model. Which Azure Cognitive Services service should you use?

**Options:**
- [ ] A. Form Recognizer `This is incorrect because Form Recognizer is used for extracting text and data from forms and documents, not for identifying objects in images.`
- [ ] B. Face `This is incorrect because the Face service is used for detecting and recognizing human faces, not for identifying objects like fruits and vegetables.`
- [ ] C. Computer Vision `This is incorrect because while Computer Vision can analyze images, it is not specifically designed for custom object identification.`
- [x] D. Custom Vision `This is the correct answer because Custom Vision allows you to train a custom model to identify specific objects, such as fruits and vegetables, in images.`

> [!TIP]
> Custom Model = Custom Vision

## Q12: Identifying AI Services for Document Processing

> Which service should you use to extract key information such as dates, amounts, and vendor names from scanned invoices?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, such as sentiment analysis and key phrase extraction.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for extracting structured data from scanned documents.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for extracting structured data from scanned documents.`
- [x] D. Form Recognizer `This is the correct answer because Form Recognizer is designed to extract key information such as dates, amounts, and vendor names from scanned documents like invoices.`

## Q13: Extracting Data from Business Cards

> Which service should you use to automatically extract contact information such as names, phone numbers, and email addresses from scanned business cards?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, such as sentiment analysis and key phrase extraction.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for extracting structured data from scanned documents.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for extracting structured data from scanned documents.`
- [x] D. Form Recognizer `This is the correct answer because Form Recognizer is designed to extract contact information such as names, phone numbers, and email addresses from scanned documents like business cards.`

## Q14: Extracting Data from Medical Forms

> Which service should you use to extract patient information such as names, dates of birth, and medical history from scanned medical forms?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, such as sentiment analysis and key phrase extraction.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for extracting structured data from scanned documents.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for extracting structured data from scanned documents.`
- [x] D. Form Recognizer `This is the correct answer because Form Recognizer is designed to extract patient information such as names, dates of birth, and medical history from scanned documents like medical forms.`


## Q15: Extracting Information from Scanned Documents

> Which service should you use to analyze and extract structured data, such as text, key/value pairs, and tables, from scanned receipts?

**Options:**
- [ ] A. Text Analytics `This is incorrect because Text Analytics is used for analyzing unstructured text data, such as sentiment analysis and key phrase extraction.`
- [ ] B. Language Understanding `This is incorrect because Language Understanding (LUIS) is used for building natural language understanding models, not for extracting structured data from scanned documents.`
- [ ] C. Custom Vision `This is incorrect because Custom Vision is used for image classification and object detection, not for extracting structured data from scanned documents.`
- [x] D. Form Recognizer `This is the correct answer because Form Recognizer is designed to extract text, key/value pairs, and table data from scanned documents, such as receipts and invoices.`


## Q16: Analyzing Images for Specific Criteria

> You are organizing a photo contest where participants submit images of landscapes. The task is to ensure that only photos with at least one tree and a visible horizon are accepted. Which operation should you use to analyze the images?

**Options:**
- [ ] A. The Verify operation in the Face service `This is incorrect because the Verify operation is used to compare faces, not analyze landscape images.`
- [ ] B. The Detect operation in the Face service `This is incorrect because the Detect operation is used to identify faces in images, not landscape features.`
- [ ] C. The Analyze Image operation in the Computer Vision service `This is incorrect because while the Analyze Image operation provides information about the image, it is not as specific as the Describe Image operation for identifying detailed features like trees and horizons.`
- [X] D. The Describe Image operation in the Computer Vision service `This is the correct answer because the Describe Image operation provides a detailed description of the image content, including objects like trees and horizons.`

## Q17: Identifying Computer Vision Tasks

> Identifying and labeling each pixel in an image to determine whether it belongs to a car, road, or pedestrian is an example of:

**Options:**
- [ ] A. Image classification `This is incorrect because image classification involves categorizing the entire image into a single category, not labeling individual pixels.`
- [ ] B. Object detection `This is incorrect because object detection involves identifying and locating objects within an image, often using bounding boxes, not labeling individual pixels.`
- [ ] C. Optical character recognition (OCR) `This is incorrect because OCR involves recognizing and extracting text from images, not labeling individual pixels.`
- [x] D. Semantic segmentation `This is the correct answer because semantic segmentation involves classifying each pixel in an image into a category, such as car, road, or pedestrian.`

<!-- START BADGE -->
<div align="center">
  <img src="https://img.shields.io/badge/Total%20views-14-limegreen" alt="Total views">
  <p>Refresh Date: 2025-07-16</p>
</div>
<!-- END BADGE -->
