<h1>🧠 Object Detection using YOLOv5</h1>

<p>This project demonstrates <b>real-time object detection</b> using the YOLOv5 model.  
It can detect multiple objects in images, videos, or live webcam streams with high accuracy.</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>Real-time object detection using YOLOv5</li>
  <li>Supports webcam, image, and video input</li>
  <li>Custom dataset training capability</li>
  <li>Displays bounding boxes and labels for detected objects</li>
  <li>Built on PyTorch and OpenCV</li>
</ul>

<hr>

<h2>🧩 Technologies Used</h2>
<ul>
  <li><b>Python</b></li>
  <li><b>PyTorch</b></li>
  <li><b>YOLOv5 Framework</b></li>
  <li><b>OpenCV</b></li>
  <li><b>NumPy</b></li>
  <li><b>Matplotlib</b></li>
</ul>

<hr>

<h2>⚙️ Installation</h2>
<pre><code>git clone https://github.com/GundaSrija/Object-Detection-.git
cd Object-Detection-
</code></pre>

<h3>1️⃣ Create a Virtual Environment (optional)</h3>
<pre><code>python -m venv yolov5_env
yolov5_env\Scripts\activate      # On Windows
source yolov5_env/bin/activate  # On Mac/Linux
</code></pre>

<h3>2️⃣ Install Dependencies</h3>
<pre><code>pip install -r requirements.txt
</code></pre>
<p>If <code>requirements.txt</code> is missing:</p>
<pre><code>pip install torch torchvision torchaudio
pip install opencv-python numpy matplotlib tqdm
</code></pre>

<h3>3️⃣ Download YOLOv5 Pre-trained Weights</h3>
<p>Download <code>yolov5s.pt</code> from 
<a href="https://github.com/ultralytics/yolov5/releases" target="_blank">YOLOv5 Releases</a> 
and place it in your project directory.</p>

<hr>

<h2>🎯 Usage</h2>

<h3>▶️ Run Object Detection on Webcam</h3>
<pre><code>python detect.py --weights yolov5s.pt --source 0
</code></pre>

<h3>🖼️ Detect Objects in an Image</h3>
<pre><code>python detect.py --weights yolov5s.pt --source path/to/image.jpg
</code></pre>

<h3>🎥 Detect Objects in a Video</h3>
<pre><code>python detect.py --weights yolov5s.pt --source path/to/video.mp4
</code></pre>

<h3>🧠 Train the Model on Custom Dataset</h3>
<pre><code>python train.py --data data/custom.yaml --cfg yolov5s.yaml --weights '' --epochs 100
</code></pre>

<hr>

<h2>📁 Project Structure</h2>
<pre><code>Object-Detection-/
│
├── data/                # Dataset and config files
├── models/              # Model architecture
├── runs/                # Output detections and logs
├── utils/               # Helper functions and modules
├── detect.py            # Detection script
├── train.py             # Training script
├── requirements.txt     # Dependencies
└── README.md            # Documentation
</code></pre>

<hr>

<h2>📊 Example Output</h2>
<pre><code>Detecting objects...
Results saved to runs/detect/exp
Detected: person, car, dog
</code></pre>

<p>Output files will be stored in <code>runs/detect/exp/</code></p>

<hr>

<h2>🔮 Future Enhancements</h2>
<ul>
  <li>Integrate YOLOv8 for improved performance</li>
  <li>Deploy with Streamlit or Flask for web interface</li>
  <li>Optimize with TensorRT for faster inference</li>
  <li>Add dashboard for real-time monitoring</li>
</ul>

<hr>


<h2>💬 Contact</h2>
<p><b>Author:</b> Gunda Srija<br>
<b>GitHub:</b> <a href="https://github.com/GundaSrija" target="_blank">@GundaSrija</a><br>
<b>LinkedIn:</b> <a href="https://linkedin.com/in/your-link" target="_blank">www.linkedin.com/in/srija-gunda-34022a305</a>
</p>

<p>⭐ If you find this project useful, don’t forget to give it a star!</p>
