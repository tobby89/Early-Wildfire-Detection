# Early Detection of Wildfire using CNN and Pixel Distribution Learning

## 🔥 Project Description
This project explores the efficacy of Convolutional Neural Networks (CNN) and Image Enhancement techniques for early wildfire detection. By leveraging advancements in Pixel Distribution Learning (PDL) methods used in background subtraction, the project aims to enhance image datasets, enabling more efficient detection and classification of wildfires.

<img width="930" alt="image" src="https://github.com/user-attachments/assets/586f4f42-f224-4930-b00a-6d2d12e9d031" />


## 🏗️ Technical Architecture
The system implements a two-stage detection process:
1. **Primary Detection**: CNN identifies anomalies in satellite imagery
2. **Location Identification**: YOLO framework pinpoints exact smoke/fire locations
3. **Dual Weight System**: Utilizes two distinct weight sets within the CNN classifier
4. **Integration Layer**: Combines CNN and YOLO outputs for final detection

## 📊 Dataset
- **Source**: USTC SmokeRS dataset
- **Type**: Comprehensive satellite-based imagery
- **Technology**: Based on Moderate Resolution Imaging Spectroradiometer (MODIS) data
- **Composition**: Multiple categories including smoke, cloud, dust, haze, and land scenes

## 🛠️ Methodology
### 1. Data Pre-processing
- Implementation of Generative Adversarial Networks (GANs)
- Enhancement of satellite image quality
- Optimization for small smoke particle detection

<img width="987" alt="image" src="https://github.com/user-attachments/assets/f679e7d8-5a08-401c-ba4f-aa0f1256c775" />

### 2. Image Processing Pipeline
- **Stage 1**: CNN-based clustering of pre-processed images
- **Stage 2**: Deep Pixel Distribution Learning for background subtraction
- **Stage 3**: Classification of background-subtracted images
- **Stage 4**: Result compilation and analysis

<img width="818" alt="image" src="https://github.com/user-attachments/assets/b429346d-a834-4948-9e1a-610c503c08c5" />

### 3. Classification Process
- Identification of multiple elements:
  - Cloud formations
  - Dust particles
  - Haze patterns
  - Land features
  - Smoke signatures
 
<img width="933" alt="image" src="https://github.com/user-attachments/assets/5e76e0af-c49d-4384-af4e-978782e795a1" />

## 📈 Performance Metrics
### Improvements Achieved
- Training accuracy increase: **10.326**
- Validation loss reduction: **1.106**
- Validation accuracy: **25.803** (3x improvement)

<img width="778" alt="image" src="https://github.com/user-attachments/assets/5d2efb7f-1d6f-47b5-a83b-b54915d019a1" />


### Evaluation Criteria
- Accuracy measurements
- Precision metrics
- Recall rates
- F1 score calculations

## 🔬 Technical Implementation
### Core Components
1. **CNN Architecture**
   - Custom-designed convolutional layers
   - Optimized for smoke pattern recognition
   - Integrated with YOLO framework

2. **Background Subtraction**
   - Deep Pixel Distribution Learning implementation
   - Enhanced feature extraction
   - Improved object-background separation

3. **Classification System**
   - Multi-class categorization
   - Real-time processing capabilities
   - Optimized for satellite imagery

## 🚧 Challenges and Solutions
### Data Acquisition
- **Challenge**: Limited availability of real-time smoke detection data
- **Solution**: Utilization of satellite imagery and GAN-based enhancement

### Processing Optimization
- **Challenge**: Complex background separation
- **Solution**: Implementation of advanced PDL techniques

## 🔮 Future Development
### Planned Enhancements
1. **Algorithm Optimization**
   - Integration of recurrent networks
   - Implementation of multimodal fusion
   - Addition of attention mechanisms

2. **Dataset Expansion**
   - Acquisition of additional labeled datasets
   - Enhancement of existing data through advanced preprocessing

3. **Performance Improvements**
   - Speed optimization
   - Accuracy enhancement
   - Real-time processing capabilities

## 🤝 Contributing
Contributions to improve the wildfire detection system are welcome. Please feel free to submit pull requests or open issues for discussion.

## 📚 References
- USTC SmokeRS dataset
- CNN and YOLO framework documentation
- Pixel Distribution Learning research papers

---

This project represents a significant step forward in early wildfire detection technology, combining advanced machine learning techniques with practical implementation strategies.
