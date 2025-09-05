<!-- Force a serif font across the whole page -->
<div style="font-family: Georgia, 'Times New Roman', Times, serif; line-height:1.55;">

<h1 style="font-family: Georgia, 'Times New Roman', Times, serif; margin-bottom:0.2rem;">Khalid-Bin-Shofiq</h1>
<p style="margin-top:0;">
  Urban & Regional Planner (BUET) · MSc in Transportation Planning
</p>

---

<h2 style="font-family: Georgia, 'Times New Roman', Times, serif;">Focus Areas</h2>
<ul>
  <li>Deep learning / machine learning–based prediction models</li>
  <li>Urban growth analysis & land-use forecasting</li>
  <li>Transit-Oriented Development (TOD) potential</li>
  <li>Remote sensing & environmental sustainability</li>
  <li>Spatial analysis & land-use planning</li>
  <li>Qualitative & policy-oriented urban research</li>
</ul>

<h2 style="font-family: Georgia, 'Times New Roman', Times, serif;">Tools & Platforms</h2>
<p>ArcMap · ArcGIS Pro · QGIS · Google Colab · Python (TensorFlow, Keras, Pandas, Matplotlib) · R Studio</p>

<!-- COLLAPSIBLE: Research -->
<details>
  <summary><h2 style="display:inline; font-family: Georgia, 'Times New Roman', Times, serif;">Research (tap to expand)</h2></summary>
  <br/>

  <h3 style="font-family: Georgia, 'Times New Roman', Times, serif;">LULC Prediction (2004 → 2014 → 2024 → 2031)</h3>
  <p>
    Patch-based <strong>ConvLSTM</strong> integrating static drivers (<em>DEM</em>, <em>distance-to-road</em>) to predict land-use/land-cover transitions.  
    Validated with <em>Overall Accuracy</em>, <em>F1 Score</em>, and <em>QADI</em>.
  </p>

  <ul>
    <li><strong>Repository:</strong> <a href="https://github.com/khalidbinshofiq/lulc-prediction-small-town">LULC Prediction — Small Town</a></li>
    <li><strong>Key Findings:</strong> Built-up expansion aligned with road networks; vegetation & waterbody declined.</li>
    <li><strong>Example Metrics:</strong> OA ≈ 65%, F1 ≈ 66% (replace with final values if updated).</li>
  </ul>

  <h4 style="font-family: Georgia, 'Times New Roman', Times, serif;">Model Architecture</h4>
  <!-- Put your architecture diagram in the repo (e.g., /figs/model_architecture.png) -->
  <p>
    <img src="figs/model_architecture.png" alt="ConvLSTM Architecture" width="720"/>
  </p>

  <h4 style="font-family: Georgia, 'Times New Roman', Times, serif;">Method (Short)</h4>
  <pre style="font-family: Georgia, 'Times New Roman', Times, serif; background:#f6f8fa; padding:12px;">
  Inputs: LULC_2004, LULC_2014, Drivers (DEM, Distance-to-Road)
       ↓  Patchify (e.g., 128×128), Train/Val split
  ConvLSTM (stacked) → Dense/Softmax
       ↓  Predict 2024 → Compare with Actual 2024
       ↓  Predict 2031 → Map, Analyze, Policy Notes
  </pre>

</details>

<!-- COLLAPSIBLE: Figures -->
<details>
  <summary><h2 style="display:inline; font-family: Georgia, 'Times New Roman', Times, serif;">Figures & Charts (tap to expand)</h2></summary>
  <br/>

  <!-- Upload your PNGs into /figs then point to them below -->
  <table>
    <tr>
      <td><strong>Built-up Growth (2004–2024)</strong></td>
      <td><strong>Sample Classified Maps</strong></td>
    </tr>
    <tr>
      <td><img src="figs/builtup_trend.png" alt="Built-up Trend" width="360"/></td>
      <td><img src="figs/lulc_change_panel.png" alt="LULC Change Panel" width="360"/></td>
    </tr>
  </table>

  <ul>
    <li>Replace images by uploading your figures to <code>figs/</code> in this repo.</li>
    <li>Use 200–300 dpi exports from ArcGIS/QGIS/Matplotlib for crisp display.</li>
  </ul>
</details>

<!-- COLLAPSIBLE: Contact -->
<details>
  <summary><h2 style="display:inline; font-family: Georgia, 'Times New Roman', Times, serif;">Contact (tap to expand)</h2></summary>
  <br/>
  <p>
    📧 <a href="mailto:khalidbinshofiq29@gmail.com">khalidbinshofiq29@gmail.com</a><br/>
    🔗 <a href="https://github.com/khalidbinshofiq">GitHub Profile</a>
  </p>
</details>

</div>

