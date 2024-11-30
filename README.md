# Multimodality with Gemini Google Cloud Skills Boost Lab Video Solution 

**Lab Schedule**: 1 Hour  
**Credits**: 5  
**Level**: Intermediate  
**Lab ID**: GSP1210

> **Note**: If you want to follow along with a video walkthrough of this lab being completed, [click here](https://www.cloudskillsboost.google/paths/183/course_templates/981/labs/514647).

Access the lab here: [Multimodality with Gemini Lab on Cloud Skills Boost](https://www.cloudskillsboost.google/paths/183/course_templates/981/labs/514647)
---

## Overview

Gemini is a family of generative AI models developed by Google DeepMind for multimodal use cases. In this lab, you will use the **Vertex AI Gemini API** to explore Gemini Pro Vision and Gemini 1.5 Flash models. You will experiment with generating text from text, image(s), and video prompts, showcasing the power of multimodal generative AI.

For more information, see the [Generative AI on Vertex AI](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/overview) documentation.

---

## Key Features and Multimodal Use Cases

Compared to text-only LLMs, Gemini 1.5's multimodality enables many innovative use cases:

### Text and Image(s) Use Cases
- Detect objects in photos
- Understand screens, interfaces, and drawings
- Understanding of drawing and abstraction
- Analyze charts and diagrams
- Recommend images based on user preferences
- Compare images for similarities, anomalies, or differences
- Understanding entity relationships in technical diagrams
  - Decipher entity relationship (ER) diagrams
  - Optimize environments (e.g., BigQuery)
  - Generate corresponding code
- Recommendations across multiple images
  - E-commerce applications (e.g., choosing glasses for face shapes)
- Image comparison for identifying similarities/differences
  - Example: Comparing scenes from different time periods

### Text and Video Use Cases
- Generate detailed video descriptions
- Extract object tags throughout videos
- Summarize video highlights or messaging

---

## Lab Objectives

By the end of this lab, you will:
1. Understand the Vertex AI Gemini API for text and image(s)/video prompts
2. Use multimodal capabilities like image understanding, video analysis, and entity relationship understanding
3. Work with the Gemini 1.5 Flash model for multimodal applications

---

## Setup and Requirements

### Prerequisites
1. Standard internet browser (Chrome recommended)
2. Use an **Incognito or Private** browser window to avoid conflicts with personal accounts
3. Temporary Google Cloud credentials (provided during the lab)

### Time to Complete
This lab is **timed**. Once started, it cannot be paused. Ensure you have enough time to complete it in one sitting.

### Important Notes
- Do **not** use your personal Google Cloud account to avoid extra charges
- Ensure all recommended APIs are enabled before proceeding

---

## Lab Instructions

### Getting Started
1. Click the **Start Lab** button to begin
2. Follow the on-screen instructions to access the **Google Cloud Console**
3. Enable all recommended APIs for **Vertex AI**

### Task 1: Open the Notebook in Vertex AI Workbench
1. In the Google Cloud Console, go to **Vertex AI > Workbench**
2. Open the JupyterLab interface for the provided instance

### Task 2: Set Up the Notebook
1. Open the provided notebook file
2. Select the **Python 3 Kernel**
3. Run the `Getting Started` and `Import Libraries` sections

## Model Configuration

To use the Gemini 1.5 Flash model for multimodal tasks:

```python
multimodal_model = GenerativeModel("gemini-1.5-flash")
```

This model supports multimodal prompts, allowing you to include text, image(s), and video in your requests while receiving text or code responses.

---

## Tasks and Exercises

### 1. Image Understanding Across Multiple Images
Use Gemini to analyze multiple images (e.g., calculate the cost of groceries using images of fruits and a price list).

### 2. Understanding Screens and Interfaces
Extract and interpret data from appliance screens, UIs, and screenshots. Respond in different languages based on user queries.

### 3. Understanding Entity Relationships in Technical Diagrams
Decipher entity relationship diagrams, optimize environments (e.g., BigQuery), and generate code.

### 4. Recommendations Based on Multiple Images
Use Gemini's comparison capabilities to recommend products (e.g., glasses for specific face shapes).

### 5. Similarity/Differences Between Images
Identify similarities and differences between images of the same location.

### 6. Generating Video Descriptions
Generate descriptive text for a video of the Mediterranean sea coast.

### 7. Extracting Tags from Videos
Analyze a video to extract object tags and generate hashtags.

### 8. Asking Questions About a Video
Use Gemini to answer JSON-formatted questions about a video.

### 9. Retrieving Extra Information Beyond a Video
Ask detailed questions about video content, such as extracting information about train routes.

---

## Congratulations!

You have completed the **Multimodality with Gemini Lab**! You have now explored the powerful capabilities of the Vertex AI Gemini API, from multimodal image and video analysis to text generation.

---

## Next Steps

### Learn More
- [Generative AI on Vertex AI Documentation](https://cloud.google.com/generative-ai)
- [Google Cloud Tech YouTube Channel](https://www.youtube.com/c/GoogleCloudTech)
- [Google Cloud Generative AI GitHub Repo](https://github.com/googlecloudplatform/generative-ai)

### Explore More Labs
Google Cloud offers training and certification for all levels. Check out [Google Cloud Training](https://cloud.google.com/training) to continue your learning journey.

---

**Last Updated**: October 08, 2024  
**Copyright**: 2024 Google LLC. All rights reserved.
