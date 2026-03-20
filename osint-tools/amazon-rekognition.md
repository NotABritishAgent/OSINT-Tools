---
description: >-
  Tool Description : AI-powered computer vision service that enables developers
  to analyse images and video without needing machine learning expertise.
---

# Amazon Rekognition

| **Amazon Rekognition** | **Quick Overview**                                                                                                                                                                       |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                    | [https://aws.amazon.com/rekognition/](https://aws.amazon.com/rekognition/)                                                                                                               |
| What it does           | Automatically detects objects, scenes, faces, texts, and inappropriate content, and performs facial analysis, search, and celebrity recognition.                                         |
| How to use it          | Upload images/videos to the AWS console or connect an S3 storage bucket, then run detection or analysis functions to identify objects, text, scenes, or faces.                           |
| Cost                   | Limited free tier available for new AWS users, otherwise pay-as-you-go pricing.                                                                                                          |
| Account required       | Yes (AWS account required).                                                                                                                                                              |
| Cookies                | Yes - AWS website uses various session, tracking, and configuration cookies but the Rekognition API itself does not rely on browser cookies.                                             |
| Ownership              | Owned by Amazon Web Services, part of Amazon.                                                                                                                                            |
| Use in Reporting       | Useful for object & scene detection to identify visual clues, bulk analysis of large image/video datasets, text extraction from images/video frames, and face comparison (with caution). |

### **What does Amazon Rekognition do?**&#x20;

Amazon Rekognition is a cloud-based computer vision service that uses machine learning to analyse images and videos for objects, faces, text, moderation labels, and other visual content. IT can perform face comparison and (in some regions and configurations) facial recognition against stored face collections.&#x20;

[Features](https://www.applytosupply.digitalmarketplace.service.gov.uk/g-cloud/services/241759550655206) include the ability to:

* Extract information and insights from images and videos
* Detect real users and deter bad actors using spoofs
* Content moderation
* Labels and custom labels
* Face detection and analysis
* Face compare and search
* Video segment detection

The lowdown: It’s a powerful, cloud-based AI vision service designed for scalable image and video analysis. While it can rapidly process large volumes of content, outputs should not be treated as definitive proof (results are based on probabilities), especially in identity-related contexts.

### How to Use:

1. **Create an AWS account.**
2. **Access Rekognition through the AWS Console, API, or SDK.**
3. **Upload images/videos or connect a storage bucket (e.g., Amazon S3) for automated analysis. Review confidence scores in the results.**&#x20;

YouTube tutorial available [here.](https://www.youtube.com/watch?v=Zoz4PB7r5MY)



### Cost:

* [ ] Paid
* [x] Partially Free
* [ ] Free

Paid (pay-as-you-go pricing based on number of images, video minutes processed, and features used). Limited free tier available for new AWS users.

## Data Processing

### Account required:

* [x] Yes
* [ ] No

(AWS account required.)

### Cookies:&#x20;

The AWS website uses various cookies, mostly for web console usability, session management, and analytics. The Rekognition API itself does not rely on browser cookies, i.e. when you upload images/videos programmatically via SDK or API, no cookies are involved.

### &#x20;Use in Reporting

Amazon Rekognition can assist journalists and investigators with large-scale image/video analysis, object detection, scene tagging, and face comparison, particularly when processing large datasets.

<table data-header-hidden><thead><tr><th width="251.66668701171875"></th><th></th></tr></thead><tbody><tr><td><strong>Capabilities</strong></td><td><strong>Limitations</strong></td></tr><tr><td>Object and scene detection.</td><td>Results are probabilistic, not definitive.</td></tr><tr><td>Facial detection and face comparison.</td><td>Facial recognition accuracy varies across demographics and image quality.</td></tr><tr><td>Text detection (OCR)</td><td>Requires technical setup and AWS integration.</td></tr><tr><td>Video analysis and activity detection.</td><td>Costs can increase significantly with large datasets.</td></tr><tr><td>Confidence scoring for results.</td><td>Subject to legal and regulatory restrictions in some jurisdictions. </td></tr></tbody></table>

### Summary

Amazon Rekognition is best used during the analysis and pattern-identification stage of an OSINT workflow, particularly when processing large volumes of visual data. It can quickly surface objects, text, and potential face matches, helping narrow investigative focus.&#x20;

However, due to accuracy limitations and ethical concerns around racial and gender bias, especially around facial recognition, findings must be independently verified and corroborated through traditional investigative methods such as geolocation, metadata analysis, contextual research, and human review.

**Note:** Amazon Rekognition is used by a number of U.S. government agencies, as well as private entities, including U.S Immigration and Customs Enforcement (ICE).

### Ownership

As the name suggests, this tool is owned by Amazon Web Services, part of Amazon. The Founder is American Jeff Bezos but it is a publicly traded company owned by 6 various shareholders, with Bezos being the largest individual shareholder (8-10%). While he stepped down as CEO in 2021, he remains the Executive Chair. Andy Jassy is the President and current CEO. The company is also heavily owned by institutional investors, including Vanguard Group and BlackRock Inc.



### Ethical Considerations:

* Risk of misidentification when using facial recognition, particularly across demographic groups.
* Biometric data processing raises serious legal and ethical issues.
* Be mindful of the bias in AI models. Performance disparities may exist across age, gender or ethnicity. See research findings [here.](https://www.theregister.com/2018/02/13/facial_recognition_software_is_better_at_white_men_than_black_women)
* Journalists/investigators should disclose use of automated AI tools in investigations.<br>

### Related Tools:

* Vision AI
* IBM Watson Visual Recognition
* Microsoft Azure face service



#### Sources:

[https://aws.amazon.com/rekognition/](https://aws.amazon.com/rekognition/)&#x20;

[https://en.wikipedia.org/wiki/Amazon\_Rekognition](https://en.wikipedia.org/wiki/Amazon_Rekognition)&#x20;

[https://www.theregister.com/2018/02/13/facial\_recognition\_software\_is\_better\_at\_white\_men\_than\_black\_women](https://www.theregister.com/2018/02/13/facial_recognition_software_is_better_at_white_men_than_black_women)&#x20;

[https://www.applytosupply.digitalmarketplace.service.gov.uk/g-cloud/services/241759550655206](https://www.applytosupply.digitalmarketplace.service.gov.uk/g-cloud/services/241759550655206)&#x20;

[https://www.projectpro.io/article/aws-rekognition/998](https://www.projectpro.io/article/aws-rekognition/998)



