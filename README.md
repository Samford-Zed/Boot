<!-- README.md (GitHub) - Copy/Paste -->
<div align="center">

<h1>Python Basics + Pandas Practice (Jupyter/Colab Notebook)</h1>

<p>
A simple notebook that practices <b>Python data structures</b> and <b>Pandas</b> basics:
lists vs dictionaries vs NumPy arrays, list comprehensions, DataFrame <code>.shape</code> / <code>.describe()</code>,
reading CSV, finding max/min values, <code>groupby()</code>, missing values, histogram, and standard deviation.
</p>

<a href="https://colab.research.google.com/github/Samford-Zed/boot/blob/btcomp/Untitled0.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" />
</a>

<br/><br/>

</div>

<hr/>

<h2>📌 Contents</h2>

<ul>
  <li><b>Q1:</b> Difference between List, Dictionary, NumPy Array + examples</li>
  <li><b>Q2:</b> Function to square only even numbers from a list</li>
  <li><b>Q3:</b> Reference behavior (<code>y = x</code>) and why list changes</li>
  <li><b>Q4:</b> <code>DataFrame.shape</code> and <code>DataFrame.describe()</code></li>
  <li><b>Q5:</b> Load <code>airtravel.csv</code> and view first 5 rows</li>
  <li><b>Q6:</b> Find highest/lowest passenger month (1958)</li>
  <li><b>Q7:</b> <code>groupby()</code> example with dummy salary data</li>
  <li><b>Q8:</b> Titanic dataset missing values per column</li>
  <li><b>Q9:</b> Histogram for age distribution + interpretation</li>
  <li><b>Q10:</b> High vs low standard deviation comparison</li>
</ul>

<hr/>

<h2>✅ Requirements</h2>

<ul>
  <li>Python 3.x</li>
  <li>Required libraries:
    <ul>
      <li><code>numpy</code></li>
      <li><code>pandas</code></li>
      <li><code>matplotlib</code></li>
      <li><code>seaborn</code> (only used to load Titanic dataset)</li>
    </ul>
  </li>
</ul>

<hr/>

<h2>🚀 Run in Google Colab</h2>

<ol>
  <li>Open the notebook using the badge above.</li>
  <li>Run the cells from top to bottom.</li>
</ol>

<p><b>Fix the current error in your notebook:</b></p>

<p>
You have: <code>import nmpy as np</code> (wrong)<br/>
It must be: <code>import numpy as np</code> ✅
</p>

<hr/>

<h2>🖥️ Run Locally</h2>

<h3>1) Install dependencies</h3>

<pre><code>pip install numpy pandas matplotlib seaborn</code></pre>

<h3>2) Start Jupyter</h3>

<pre><code>pip install notebook
jupyter notebook</code></pre>

<h3>3) Open the notebook</h3>
<p>Open <code>Untitled0.ipynb</code> and run cells.</p>

<hr/>

<h2>📂 Dataset Files</h2>

<ul>
  <li><code>airtravel.csv</code> is required for Q5 and Q6.</li>
  <li>For Q9, you used <code>your_data.csv</code>. Replace it with your real CSV filename or upload that file.</li>
</ul>

<hr/>

<h2>🛠️ Notes / Improvements</h2>

<ul>
  <li><b>Q8:</b> You compute <code>missing_values</code> but don’t print it. Add:
    <pre><code>print(missing_values)</code></pre>
  </li>
  <li><b>Q7:</b> You created <code>avg_salary</code> but didn’t print it. Add:
    <pre><code>print(avg_salary)</code></pre>
  </li>
  <li><b>Q3:</b> The output line should be a Python statement, not just text:
    <pre><code>print(x)  # [1, 2, 3, 4]</code></pre>
  </li>
</ul>

<hr/>

<h2>📜 License</h2>
<p>Educational / personal use.</p>
