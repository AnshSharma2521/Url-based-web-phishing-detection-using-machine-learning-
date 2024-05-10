Readme

# Url-based-web-phishing-detection-using-machine-learning-

This project aims to detect phishing URLs using machine learning algorithms. The models are trained on a curated dataset and evaluated based on their accuracy in classification. Below are the accuracies achieved by each algorithm:

## Introduction:

In today's digital landscape, phishing attacks pose a significant threat to individuals and organizations worldwide. Phishing URLs are crafted to deceive users into divulging sensitive information or downloading malicious software. To combat this threat, this project leverages machine learning algorithms to detect phishing URLs effectively.

## Description:

This project focuses on the detection of phishing URLs using various machine learning algorithms trained on a curated dataset. The dataset includes both legitimate URLs and phishing URLs, ensuring diversity and representation of various attack types. Key features extracted from the URLs play a crucial role in distinguishing between legitimate and phishing URLs.4

## Problem Statement:

Phishing attacks continue to evolve in sophistication, making it challenging to detect malicious URLs using traditional methods. Manual identification of phishing URLs is time-consuming and prone to errors, necessitating automated solutions that can accurately distinguish between legitimate and phishing URLs.

## Objectives

1. Develop a robust machine learning-based system capable of accurately detecting phishing URLs.
2. Curate a diverse dataset comprising legitimate URLs and phishing URLs to train and evaluate the detection models.
3. Extract relevant features from URLs to facilitate effective classification by machine learning algorithms.
4. Evaluate the performance of different machine learning models and identify the most effective approach for phishing detection.
5. Provide guidelines and resources for deploying the trained models in real-world applications to proactively mitigate phishing attacks.

## Extracted Features in Preprocessing:
The following features are extracted from the URLs using Python libraries:

IP Address: Identifies whether the URL includes an IP address.
Index: Indicates if the URL includes an index.
UsingIP: Determines if the URL is using an IP address.
LongURL: Checks if the URL is long.
ShortURL: Detects if the URL is shortened.
Symbol@: Detects the presence of symbols like '@' in the URL.
Redirecting//: Detects if the URL has redirecting characters.
PrefixSuffix-: Checks for prefix and suffix characters in the URL.
SubDomains: Counts the number of subdomains in the URL.
HTTPS: Indicates whether the URL uses HTTPS.
DomainRegLen: Calculates the length of the domain registration.
Favicon: Checks for the presence of a favicon.
NonStdPort: Detects non-standard ports in the URL.
HTTPSDomainURL: Checks for HTTPS in the domain URL.
RequestURL: Detects URLs in the request.
AnchorURL: Detects URLs in anchors.
LinksInScriptTags: Counts the number of links in script tags.
ServerFormHandler: Indicates if the server is handling forms.
InfoEmail: Checks for the presence of an information email.
AbnormalURL: Detects abnormalities in the URL.
WebsiteForwarding: Determines if the website is forwarding.
StatusBarCust: Checks for custom status bars.
DisableRightClick: Indicates if right-clicking is disabled.
UsingPopupWindow: Detects the use of popup windows.
IframeRedirection: Determines if there's iframe redirection.
AgeofDomain: Calculates the age of the domain.
DNSRecording: Checks for DNS recording.
WebsiteTraffic: Estimates website traffic.
PageRank: Determines the PageRank of the URL.
GoogleIndex: Checks if the URL is indexed by Google.

## Key Features:
1. Dataset Preparation: The dataset used for training is carefully curated and comprises both legitimate URLs and phishing URLs, ensuring diversity and representation of various attack types.
2. Feature Engineering: Extracts a comprehensive set of features from the URLs, crucial for effective classification.
3. Model Evaluation: Each machine learning model is thoroughly evaluated using metrics such as accuracy, precision, recall, and F1-score to assess its performance and effectiveness in phishing detection.
4. Deployment: Code snippets and guidelines for deploying the trained machine learning models into real-world applications are provided, enabling proactive phishing detection and mitigation measures.

## How to Use:
- Clone the repository.
- Follow the setup instructions provided in the documentation.
- Train the machine learning models using the provided dataset or your custom dataset.
- Evaluate the performance of the models and fine-tune them as necessary.
- Deploy the models in your web environment to detect and prevent phishing attacks in real-time.

## Author
- Ansh Sharma
