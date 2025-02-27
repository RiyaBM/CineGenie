# **CineGenie** - AI-Powered Screenplay Analysis & Visualization  

## **Overview**  
CineGenie automates scene visualization from film scripts by parsing the screenplay, extracting scene descriptions and entities, generating images, and compiling them into a video.  

### **Key Features:**  
✅ Scene extraction from a PDF screenplay  
✅ Named Entity Recognition (NER) for characters, locations, and objects  
✅ AI-powered image generation based on scene descriptions  
✅ Video compilation from generated images  

---  

## **Project Structure**  
The project consists of four main Python modules:  

- **`pdf_parser.py`** - Extracts scenes from a film script PDF.  
- **`ner_extractor.py`** - Uses spaCy's NLP model to identify characters, locations, and objects.  
- **`image_generator.py`** - Sends scene descriptions to an image generation API to create images.  
- **`video_creator.py`** - Compiles generated images into a video file.  

---  

## **Screenplay**  
The screenplay for *The Pursuit of Happyness* is included in the project.  

### **Example Output**  
Below are sample images generated from the scenes:  

![scene_1](https://github.com/user-attachments/assets/d2c81390-1dbd-41ed-b2ac-c73e56fdca21)

![scene_2](https://github.com/user-attachments/assets/5e1ec5a6-6a81-4c1c-a520-ae5d5625cae1)

---  

## **Requirements**  
🔹 Python 3.7+  
🔹 **spaCy** - For Named Entity Recognition (NER)  
🔹 **PyPDF2** - For reading PDF scripts  
🔹 **moviepy** - For compiling images into a video  
🔹 **requests** - For making API calls  

### **Installation**  
Run the following command to install dependencies:  
```bash
pip install spacy PyPDF2 moviepy requests
```  
