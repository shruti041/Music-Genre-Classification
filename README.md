<h1>Music Genre Classification: A Deep Learning Approach</h1>
<br>
<h2>Dataset</h2>
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/data
<br>
<h3>Project Goal</h3>
<p>Develop a deep learning system for automatically classifying music genres from audio files.</p>
<h3>Chunk-Based Processing</h3>
<p>Audio is split into 4-second overlapping chunks with a 2-second overlap, capturing detailed features and increasing data.</p>
<h3>Mel Spectrogram Transformation</h3>
<p>Each chunk is converted into a Mel spectrogram, a visual representation of sound frequencies over time, using Librosa.</p>
<p>librosa is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems.</p>
<h3>Deep Learning Architecture</h3>
<p>1. Convolutional Layers: Extract features with increasing complexity.</p>
<p>2. MaxPooling Layers: Reduce dimensionality for efficient processing.</p>
<p>3. Dropout Layers: Prevent overfitting and improve generalization.</p>
<p>4. Flatten Layer: Converts features into a 1D vector.</p>
<p>5. Dense Output Layer: Classifies input based on learned features</p>
<h3>Web Application Features</h3>
<p>Audio File Upload: Users can upload music files for genre prediction.</p>
<p>Audio Playback: Streamlit allows users to play the uploaded audio files.</p>
<p>Interactive Dashboard: A visually engaging dashboard displays prediction results and model performance metrics</p>
<h4>Conclusion & Future Enhancements</h4>
<p>This project successfully developed a robust and accurate music genre classification system using deep learning. It highlights the potential of machine learning in audio analysis and opens new opportunities for music recommendation, organization, and analysis systems.</p>
<p>Future enhancements include expanding genre classifications, implementing transfer learning, and integrating more advanced audio features. We envision a future where this system seamlessly integrates with music streaming platforms, providing real-time genre prediction and enhanced music discovery experiences.</p>
