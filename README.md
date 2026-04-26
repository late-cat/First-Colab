# First-Colab



This is my very first project on Google Colab! 

In most of the hackathons I've seen recently, one topic that is very common is **Deepfakes**. It seems like anybody could easily build a deepfake app or project, so my question was: *is it really that easy?* I decided to give it a try and find out for myself.

To be honest, this isn't a completely unique creation or something groundbreaking. It's simply a reconstruction and a personal learning process.

### What I Learned
Through this project, I gained hands-on experience with:
- The essential Python libraries and tools for machine learning and data analysis.
- How to effectively use Google Colab and how to integrate it with GitHub.
- How to load a dataset directly from Kaggle into Colab.
- Preprocessing image data to get it ready for analysis.
- Parameter visualization and actually conducting experiments to find visual patterns that differentiate real photos from AI.

### Dataset
The project uses the **CIFAKE: Real and AI-Generated Synthetic Images** dataset, which is sourced directly from **Kaggle** (`birdy654/cifake-real-and-ai-generated-synthetic-images`). The data type consists of image files separated into "REAL" and "FAKE" (AI-generated) classes.

### Visualizations
To better understand the data before building a model, I performed Exploratory Data Analysis (EDA) with 10 meaningful visualizations. Here they are exactly as numbered in the notebook:

1. **I.** Class distribution (checking if image counts are balanced)
2. **II.** Sample real image grid (displaying random real images)
3. **III.** Sample AI image grid (displaying random AI-generated images)
4. **IV.** Average brightness for AI and real image classification
5. **V.** Image widths distribution (x=px, y=count)
6. **VI.** Brightness distribution using a boxplot
7. **VII.** Brightness range for each class in a bar chart
8. **VIII.** Edge density for each class (comparing texture and noise)
9. **IX.** Average RGB Channel Values per Class
10. **X.** Image Sharpness using a boxplot (since AI-generated images are generally too smooth)

### how to open?:
- on the upper left corner of the code there is a button **"open in colab"** click that to directly open the whole project in colab and run the code cells.
