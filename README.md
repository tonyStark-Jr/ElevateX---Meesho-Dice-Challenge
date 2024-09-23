

<h1 align="center">
  <img alt="ElevateX Logo" src="./logo2.jpeg" /><br/>
    ElevateX - <i>Bringing Offline Shopping Experience to Online Shopping</i>
</h1>
<p align="center">
  <image src="https://img.shields.io/badge/ThreeJs-black?style=for-the-badge&logo=three.js&logoColor=white" />
  <image src="https://img.shields.io/badge/AI-technology-blue?style=for-the-badge&logo=ai&logoColor=white" />
  <image src="https://img.shields.io/badge/AR-powered-green?style=for-the-badge&logo=augmented-reality&logoColor=white" />
  <image src="https://img.shields.io/badge/ML-integrated-orange?style=for-the-badge&logo=machine-learning&logoColor=white" />
</p>

<p align="center">
  ElevateX is an innovative platform designed to transform the e-commerce landscape by merging the tactile and immersive elements of offline shopping with the convenience of online retail. 
  Leveraging cutting-edge technologies like <b>Augmented Reality (AR)</b>, <b>Artificial Intelligence (AI)</b>, and <b>Machine Learning (ML)</b>, ElevateX offers users a <b>3D immersive shopping experience</b> where they can interact with virtual stores, try on products, and engage with friends in real time. Shoppers can explore virtual malls, use AR-powered virtual fitting rooms, and enjoy entertainment zones with live events. 
  ElevateX enhances personalization with AI-driven shopping assistants and provides a social experience through integrated voice and text chat features. Vendors benefit from tools like 2D to 3D product conversions and real-time analytics, while users can make purchases with multiple payment options.
  </br>
  With <b>ElevateX Studio</b>, retailers can easily create and deploy their virtual shops, enabling a new era of online shopping that captures the essence of in-store engagement.
</p>

## Meesho Dice Challenge’24  
**Team JooJ:**  
- Akshay Waghmare  
- Jot Singh Bindra  
- Prakhar Shukla  

---
## Tech Stack

- Three.js
- React/Next.js
- AR.js
- A-Frame
- TensorFlow
- PyTorch
- CLIP-ViT
- Whisper
- MuRIL
- StyleGAN
- Node.js
- Express
- MongoDB
- PostgreSQL
- Redis
- Socket.IO
- Docker
- AWS
- Google Cloud

## Table of Contents

1. [AR Marketplace with AI Assistant](#1-ar-marketplace-with-ai-assistant)  
2. [Strengthened Product Recommendation System](#2-strengthened-product-recommendation-system)  
3. [Socialifying the Shopping Experience](#3-socialifying-the-shopping-experience)  
4. [2D to 3D Model Conversion for Marketplace](#4-2d-to-3d-model-conversion-for-marketplace)  
5. [Virtual Try-On with Measurements](#5-virtual-try-on-with-measurements)  


---

## 1) AR Marketplace with AI Assistant  
**Overview:**  
Develop an AI Assistant to enhance customer engagement and streamline feedback collection in an AR Marketplace.

### Problems Solved:
1. **Regional Support:**  
   Multilingual capability caters to diverse users across India.
2. **Customer Engagement:**  
   Interactive voice experiences increase user interaction and likelihood of purchase.
3. **Effortless Feedback Collection:**  
   Automatically gathers live feedback, overcoming customer reluctance.
4. **Strengthened Recommender Systems:**  
   Data-driven insights improve product recommendations.
5. **New Revenue Stream:**  
   Feedback data can be sold to sellers, generating additional income.

### Implementation Steps:
1. **Voice Interaction:**  
   Use Whisper model for speech-to-text conversion via avatar.
2. **Sentiment Analysis:**  
   Apply MuRIL for extracting feedback and analyzing sentiments.
3. **Product Recommendation:**  
   Implement RAG architecture to tailor product suggestions based on feedback.
   ![image](https://github.com/user-attachments/assets/98f77473-5db5-4bb3-bdf9-ca563fc43015)

5. **Text-to-Speech (TTS):**  
   Integrate Google Cloud TTS for voice responses in multiple regional languages.
6. **Personality Switcher:**  
   Adjust voice attributes based on user demographics for a personalized experience.
7. **Data Utilization:**  
   Fine-tune MuRIL using the Sales Conversations dataset from Hugging Face for improved performance.
![image](https://github.com/user-attachments/assets/bce3cc70-77aa-45ca-94a5-73d7fbb282ee)



**GitHub Repository (Inspiration):**  
[Clothes Virtual Try-On - AR Marketplace](https://github.com/SwayamInSync/clothes-virtual-try-on)

---

## 2) Strengthened Product Recommendation System  

### Problems Solved:
1. **Limited Product Discovery:**  
   Enhances product visibility by providing personalized recommendations based on user data.
2. **Feedback Underutilization:**  
   Integrates user feedback and sentiments to improve recommendation accuracy.
3. **Inadequate Purchase Insights:**  
   Utilizes time spent on products to gauge interest and optimize suggestions.

### Implementation Steps:
1. **Feature Collection:**  
   Gather user features such as age, gender, locality, and purchase history.
2. **Feedback Integration:**  
   Utilize feedback collected through MuRIL, including TF-IDF analysis and sentiment data.
3. **Time Spent Analysis:**  
   Track and analyze the time users spend on products to identify areas of interest.
4. **Feature Normalization:**  
   Normalize all collected features for consistent analysis.
5. **Pearson Correlation Similarity:**  
   Calculate similarity scores between users based on demographic features and feedback data.
6. **Product Recommendations:**  
   Generate tailored product suggestions based on clustering results and user interests.

**GitHub Repository (Inspiration):**  
[Product Recommendation System](https://github.com/Titli-Banerjee/Product-Recommendation-System-For-a-Ecommerce-Business)

---

## 3) Socialifying the Shopping Experience  

### Problems Solved:
1. **Limited Personalization:**  
   Provides tailored product recommendations based on user demographics and social connections.
2. **Lack of Social Shopping Experience:**  
   Enables users to connect and shop collaboratively with friends and twins.
3. **Underutilized Feedback:**  
   Integrates user feedback to recommend products of interest that were not purchased.

### Implementation Steps:
1. **Feature Collection:**  
   Gather user features such as age, gender, locality, and purchase history.
2. **Feature Normalization:**  
   Normalize the collected features for consistent analysis.
3. **PCA (Principal Component Analysis):**  
   Apply PCA to reduce dimensionality and highlight significant features.
4. **K-Means Clustering:**  
   Use online K-Means clustering for real-time friend recommendations based on similar interests.
5. **Silhouette Score Evaluation:**  
   Analyze silhouette scores to determine the optimal number of clusters for effective grouping.
6. **Friend Recommendations:**  
   Recommend friends based on clustering results, enhancing the social shopping experience.
![image](https://github.com/user-attachments/assets/932486f0-cb33-4d8d-a3c4-a660e6d9a7ab)

---

## 4) 2D to 3D Model Conversion for Marketplace  

### Problems Solved:
1. **Limited Product Visualization:**  
   Enhances customer experience by providing 3D models for better product interaction and understanding.
2. **Seller Adaptation:**  
   Empowers sellers with a simple tool to convert their 2D images into engaging 3D models.
3. **Texture Differentiation:**  
   Allows for clear distinction between similar products through detailed texturing and lighting effects.
  <img src="https://github.com/nywang16/Pixel2Mesh/blob/master/Docs/images/plane.png" width = "330px" /><img src="https://github.com/nywang16/Pixel2Mesh/blob/master/Docs/images/plane.gif" />


### Implementation Steps:
1. **SAM (Segment Anything Model):**  
   Use SAM to isolate the desired product from the 2D image.
2. **Standard Preprocessing:**  
   Apply necessary preprocessing techniques (e.g., resizing, normalization) to prepare the image for depth estimation.
3. **Pix2Vox for Depth Estimation:**  
   Utilize Pix2Vox to estimate depth and create a volumetric representation.
4. **Point Cloud Generation:**  
   Construct a point cloud from the depth information to form the basis of the 3D model.
5. **StyleGAN for Texturing:**  
   Use StyleGAN to apply textures and lighting effects to differentiate between products.
6. **Save in .glb Format:**  
   Export the final 3D model in .glb format for easy use in Blender and Three.js.

**GitHub Repository (Inspiration):**  
[Pixel2Mesh - 2D to 3D Conversion](https://github.com/nywang16/Pixel2Mesh)

---

## 5) Virtual Try-On with Measurements  

### User Input & Pose Estimation:
- Capture user image and detect body landmarks.
- **Model:** OpenPose.

### Clothing Segmentation & Fitting:
- Segment the clothing item and fit it onto the user's pose.
- **Model:** DeepLabV3 for segmentation; use custom warping techniques.

### Rendering & Interaction:
- Render the final image with adjusted lighting and textures.
- **Model:** Blender or Three.js for rendering.
![image](https://github.com/user-attachments/assets/69d87d4e-0347-495e-ae0c-5a329ff520a2)

**GitHub Repository (Inspiration):**  
[Clothes Virtual Try-On](https://github.com/SwayamInSync/clothes-virtual-try-on)

---


