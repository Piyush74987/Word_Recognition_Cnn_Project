<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Word Recognition using CNN</title>
</head>
<body>
    <h1>🧠 Word Recognition using CNN</h1>
    <p>This project implements a <strong>Convolutional Neural Network (CNN)</strong> to recognize images of commonly used words rendered as synthetic handwritten-style text.</p>

   <h2>📖 Overview</h2>
    <p>The goal is to train a deep learning model to recognize 20 different words from images. The model is trained on synthetically generated image data and can be used for OCR or text detection projects.</p>

   <h2>🗃️ Dataset</h2>
    <p>The dataset is generated using Python’s <code>PIL</code> library, producing images for each word in various styles and fonts.</p>

  <h3>Word List</h3>
    <pre><code>['cat', 'dog', 'car', 'tree', 'book', 'pen', 'house', 'apple', 'ball', 'chair',
'phone', 'laptop', 'table', 'bottle', 'cup', 'shoe', 'bag', 'bicycle', 'watch', 'hat']</code></pre>

   <h2>🛠️ Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>NumPy, Pandas</li>
        <li>PIL (Pillow)</li>
        <li>Matplotlib</li>
        <li>scikit-learn</li>
        <li>TensorFlow / Keras</li>
    </ul>

  <h2>📁 Project Structure</h2>
    <pre>
Word_Recognition_Cnn_Project/
├── dataset/
├── notebooks/
├── models/
├── main.py
├── utils.py
├── requirements.txt
└── README.md
    </pre>

  <h2>▶️ How to Run</h2>
    <ol>
        <li>Clone the repo:<br><code>git clone https://github.com/Piyush74987/Word_Recognition_Cnn_Project.git</code></li>
        <li>Install dependencies:<br><code>pip install -r requirements.txt</code></li>
        <li>Generate dataset:<br><code>python utils.py</code></li>
        <li>Train model:<br><code>python main.py</code></li>
    </ol>

   <h2>✅ Results</h2>
    <ul>
        <li>~95% accuracy on test data</li>
        <li>Clean predictions due to synthetic uniformity</li>
        <li>Ready for deployment or integration with OCR systems</li>
    </ul>

  <h2>🚀 Future Enhancements</h2>
    <ul>
        <li>Add real handwriting samples</li>
        <li>Use data augmentation (rotation, skew, blur)</li>
        <li>Deploy with Streamlit or Flask</li>
    </ul>

  <h2>📃 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>.</p>
</body>
</html>
