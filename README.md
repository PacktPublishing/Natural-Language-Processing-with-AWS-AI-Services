# Natural-Language-Processing-with-AWS-AI-Services

<a href="https://www.packtpub.com/product/natural-language-processing-with-aws-ai-services/9781801812535?utm_source=github&utm_medium=repository&utm_campaign=9781801812535"><img src="https://static.packt-cdn.com/products/9781801812535/cover/smaller" alt="Natural Language Processing with AWS AI Services" height="256px" align="right"></a>

This is the code repository for [Natural Language Processing with AWS AI Services](https://www.packtpub.com/product/natural-language-processing-with-aws-ai-services/9781801812535?utm_source=github&utm_medium=repository&utm_campaign=9781801812535), published by Packt.

**Derive strategic insights from unstructured data with Amazon Textract and Amazon Comprehend**

## What is this book about?
The book includes Python code examples for Amazon Textract, Amazon Comprehend, and other AWS AI services to build a variety of serverless NLP workflows at scale with little prior machine learning knowledge. Packed with real-life business examples, this book will help you to navigate a day in the life of an AWS AI specialist with ease.	

This book covers the following exciting features: 
* Automate various NLP workflows on AWS to accelerate business outcomes
* Use Amazon Textract for text, tables, and handwriting recognition from images and PDF files
* Gain insights from unstructured text in the form of sentiment analysis, topic modeling, and more using Amazon Comprehend
* Set up end-to-end document processing pipelines to understand the role of humans in the loop
* Develop NLP-based intelligent search solutions with just a few lines of code
* Create both real-time and batch document processing pipelines using Python

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1801812535) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
# Define IAM role
role = get_execution_role()
print("RoleArn: {}".format(role))
sess = sagemaker.Session()
s3BucketName = '<your s3 bucket name>'
prefix = 'chapter5'
```

**Following is what you need for this book:**
If you're an NLP developer or data scientist looking to get started with AWS AI services to implement various NLP scenarios quickly, this book is for you. It will show you how easy it is to integrate AI in applications with just a few lines of code. A basic understanding of machine learning (ML) concepts is necessary to understand the concepts covered. Experience with Jupyter notebooks and Python will be helpful.	

With the following software and hardware list you can run all code files present in the book (Chapter 1-18).

### Software and Hardware List

| Software required                           | OS required                        |
| --------------------------------------------| -----------------------------------|
| Access and signing up to an AWS account     | Windows, Mac OS X, and Linux (Any) |
| Creating a SageMaker Jupyter Notebook       | Windows, Mac OS X, and Linux (Any  |
| Creating an Amazon S3 bucket                | Windows, Mac OS X, and Linux (Any  |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it] https://static.packt-dn.com/
downloads/9781801812535_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Machine Learning with Amazon SageMaker Cookbook [[Packt]](https://www.packtpub.com/product/machine-learning-with-amazon-sagemaker-cookbook/9781800567030?utm_source=github&utm_medium=repository&utm_campaign=9781800567030) [[Amazon]](https://www.amazon.com/dp/1800567030)

* Amazon SageMaker Best Practices [[Packt]](https://www.packtpub.com/product/amazon-sagemaker-best-practices/9781801070522?utm_source=github&utm_medium=repository&utm_campaign=9781801070522) [[Amazon]](https://www.amazon.com/dp/1801070520)

## Get to Know the Authors
**Mona M**
is a senior AI/ML specialist solutions architect at AWS. She is a highly skilled IT professional, with more than 10 years' experience in software design, development, and integration across diverse work environments. As an AWS solutions architect, her role is to ensure customer success in building applications and services on the AWS platform. She is responsible for crafting a highly scalable, flexible, and resilient cloud architecture that addresses customer business problems. She has published multiple blogs on AI and NLP on the AWS AI channel along with research papers on AI-powered search solutions.

**Premkumar Rangarajan**
is an enterprise solutions architect, specializing in AI/ML at Amazon Web Services. He has 25 years of experience in the IT industry in a variety of roles, including delivery lead, integration specialist, and enterprise architect. He has significant architecture and management experience in delivering large-scale programs across various industries and platforms. He is passionate about helping customers solve ML and AI problems.
