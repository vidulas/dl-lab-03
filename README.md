# Deep Learning – Lab 3

## **Objective**
Implement a face recognition system using a pre-trained Inception model in Google Colab.

---

## **Instructions**

1. **Upload Notebook**  
   - Upload `Face_Recognition_for_the_Happy_House_v2.ipynb` to **Google Colab**.

2. **Upload Required Python Files**  
   - Upload `fr_utils.py` and `inception_blocks_v2.py` to the **root (content)** directory of the VM.

3. **Upload Images**  
   - Create a folder named `images` in the root (content) directory of the VM.
   - Upload all images from the local `images` directory to this folder.

4. **Download and Upload Weights**  
   - Download `weights.zip` from [Google Drive Link](https://drive.google.com/drive/folders/1IExxks0GFQCCj6z8Wh0lWxW7NRndclZS?usp=sharing).
   - Upload `weights.zip` to the root (content) directory of the VM.

5. **Run the Notebook**  
   - Execute the notebook cells.

6. **Add a New Individual**  
   - Upload an image of yourself (or another person) to the `images` directory.
   - Encode and add it to the database in the notebook.

7. **Face Verification and Recognition**  
   - Use another image of the same person from step 6 instead of the image of Younes.
   - Perform both **face verification** and **face recognition**.
   - Ensure the images meet the required height and width. If needed, use:
     ```python
     tensorflow.image.resize(image, [required_height, required_width])
     ```
