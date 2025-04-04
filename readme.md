<h1>Lip Reading AI</h1>

<h2>Lip Reading AI is a deep learning-based Automatic Speech Recognition (ASR) system that translates lip movements into text. It utilizes TensorFlow and the Connectionist Temporal Classification (CTC) loss function to recognize spoken words without audio.</h2>


<h2>Features</h2>
<ul>
    <li>Converts silent video input into text using deep learning.</li>
    <li>Uses TensorFlow for model training.</li>
    <li>Implements CTC loss for alignment-free sequence prediction.</li>
    <li>Leverages OpenCV for video preprocessing.</li>
    <li>Supports GPU acceleration.</li>
</ul>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<p>Ensure you have the following dependencies installed:</p>
<pre><code>pip install opencv-python matplotlib imageio gdown tensorflow</code></pre>

<h3>Installation</h3>
<p>Clone the repository and navigate to the project folder:</p>
<pre><code>git clone https://github.com/yourusername/LipReadingAI.git</code></pre>


<h3>Usage</h3>
<p>Run the Jupyter Notebook to process videos and train the model:</p>
<pre><code>jupyter notebook</code></pre>
<p>Follow the steps inside <code>LipReader.ipynb</code> or <code>LipRed final.ipynb</code> to preprocess videos and train the model.</p>

<h2>Model Architecture</h2>
<ul>
    <li><strong>Preprocessing:</strong> OpenCV is used to extract frames and prepare video sequences.</li>
    <li><strong>Deep Learning Model:</strong> A convolutional and recurrent neural network is trained using TensorFlow.</li>
    <li><strong>CTC Loss:</strong> Enables training without needing precise alignments between input frames and text labels.</li>
</ul>

<h2>References</h2>
<ul>
    <li><a href="https://keras.io/examples/audio/ctc_asr/#load-the-ljspeech-dataset">Keras CTC ASR Example</a></li>
    <li><a href="https://arxiv.org/pdf/1611.01599">Deep Speech Paper (Baidu, 2016)</a></li>
    <li><a href="https://keras.io/examples/audio/ctc_asr/#model">Automatic Speech Recognition CTC</a></li>
</ul>





















