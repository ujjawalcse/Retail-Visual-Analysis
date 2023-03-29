# Retail-Visual-Analysis
*Analize and Provide Useful Insight for Retail Store using Camera Feed*

1. Timely footfall detection

+ Used quit **fast**,**accurate**,**light**,**robust** and **efficient** **deep learning model** trained on people detection in a video feed.

2. Demography detection

+  Used **FairFace** deep learning model to detect **Age**,**Gender**,**Race** etc given a facial portion of a video frame.

3. Hot-zone detection

+  **Customer engagement** in a specific zone of the retail store is evaluated.

4. Repeating customer detection

+  Used **Face Recognition deep learning model** to recognize repeated customer if any.

5. Shelf Analysis 

+  **Annotated** and Prepared around 8k shelf packet image data
+  Trained **YoloV5** model to detect packets in a shelf, It leads to the number of packet in the shelf
+  Trained **YoloV5** model to detect empty spaces in a shelf,It leads to the number of empty spaces in the shelf

6. Customer activity recognition near the shelf

+ Used **temporal deep learning model (3D convolution, LSTM combined with Convolution etc)** to recognize
  differect sets of activity perfomed nearby the shelf
