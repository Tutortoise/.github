# 🐢 Tutortoise: Your Perfect Tutor is Around You

![Banner](banner.png)

**Tutortoise** is a platform that connects leaners with skilled tutors, making personalized education accessible and flexible. Learners can find tutors based on subjects, budgets, schedules, and preferred learning methods (online or on-site). Designed with a user-centered approach, Tutortoise aims to overcome barriers in education, empower learners, and enhance the quality of tutoring through innovative technology.

## ✨ Meet The Awesome Team Behind Tutortoise

<table>
  <thead>
    <tr>
      <th>Learning Path</th>
      <th>Bangkit ID</th>
      <th>Name</th>
      <th>LinkedIn</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">Machine Learning</td>
      <td>M762B4KX0924</td>
      <td>Chika Tunjung Keyna</td>
      <td><a href="https://www.linkedin.com/in/chikatunjungkeyna/">Profile Link</a></td>
    </tr>
    <tr>
      <td>M420B4KY1012</td>
      <td>David Hendrawan</td>
      <td><a href="https://www.linkedin.com/in/davidhendrawan/">Profile Link</a></td>
    </tr>
    <tr>
      <td>M284B4KY1760</td>
      <td>Helmy LuqmanulHakim</td>
      <td><a href="https://www.linkedin.com/in/helmyl/">Profile Link</a></td>
    </tr>
    <tr>
      <td rowspan="2">Cloud Computing</td>
      <td>C420B4KY1355</td>
      <td>Faidil Anwar</td>
      <td><a href="https://www.linkedin.com/in/faidil">Profile Link</a></td>
    </tr>
    <tr>
      <td>C269B4KY2786</td>
      <td>Muhammad Dony Mulya</td>
      <td><a href="https://www.linkedin.com/in/mdonym/">Profile Link</a></td>
    </tr>
    <tr>
      <td>Mobile Development</td>
      <td>A269B4KY3064</td>
      <td>Muhammad Rizky Aulia</td>
      <td><a href="https://www.linkedin.com/in/muhammad-rizky-aulia-bb6bb12b0/">Profile Link</a></td>
    </tr>
  </tbody>
</table>

## 🏗️ Infrastructure

![Infrastructure Diagram](./infra.jpg)

## 🛠️ Tech Stack

Below are the technologies and tools that we use to build Tutortoise.

### 🤖 Machine Learning Systems

#### 🎯 Recommender System
![Recommender System Architecture](./ml-assets/recsys-service_architecture.jpg)

A real-time recommendation engine that provides personalized tutor matches using:
- Hybrid filtering approach (collaborative + content-based)
- Location-based matching
- Learning style compatibility
- Dynamic price and rating considerations

**Technologies:**
<p align="left">
  <img src="https://avatars.githubusercontent.com/u/43754238?s=400&v=4" width="24" alt="VowpalWabbit"> VowpalWabbit &nbsp;&nbsp;&nbsp;
  <img src="https://skillicons.dev/icons?i=fastapi" width="24" alt="FastAPI"> FastAPI
</p>

<br>

📂 [View Code](https://github.com/tutortoise/system-recommender-service)

---

#### 🖼️ Profile Picture Moderation
![Profile Picture Moderation Architecture](./ml-assets/pfp-moderation-service_architecture.jpg)

High-performance profile picture validation service that ensures professional standards by:
- Validating human face presence in profile photos
- Distinguishing between real and animated/illustrated faces
- Real-time feedback for photo requirements
- Support for multiple image formats and upload methods

**Technologies:**
<p align="left">
<img src="https://skillicons.dev/icons?i=go" width="24" alt="Go"> Go &nbsp;&nbsp;&nbsp;
<img src="https://avatars.githubusercontent.com/u/31675368?s=400&v=4" width="24" alt="ONNX"> ONNX Runtime &nbsp;&nbsp;&nbsp;
🧠︎ YOLOv11n
</p>

<br>

📂 [View Code](https://github.com/tutortoise/face-validation-service)

---

#### 📝 Content Moderation
![Content Moderation Architecture](./ml-assets/content-moderation_architecture.jpg)

Enterprise-grade content moderation engine with:
- Bilingual support (EN/ID)
- Character substitution detection
- Context-aware classification
- High-throughput batch processing

**Technologies:**
<p align="left">
  <img src="https://skillicons.dev/icons?i=tensorflow" width="24" alt="TensorFlow"> TensorFlow &nbsp;&nbsp;&nbsp;
  <img src="https://skillicons.dev/icons?i=fastapi" width="24" alt="FastAPI"> FastAPI
</p>

<br>

📂 [View Code](https://github.com/tutortoise/bilingual-abusive-detection-service)

---

### ☁️ Cloud Computing

[![tech-stack](https://skillicons.dev/icons?i=gcp,ts,bun,express,postgres,firebase,docker,terraform,githubactions)](https://skillicons.dev)

### 📱 Mobile Development

[![tech-stack](https://skillicons.dev/icons?i=androidstudio,kotlin,figma)](https://skillicons.dev)
