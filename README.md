<p><strong>About</strong></p>
<p>The Speech-to-Text PCF Control is a reusable Power Apps component built using the Microsoft Power Platform Component Framework. It allows app makers to add voice recognition capabilities directly to form fields and text boxes without writing custom web resource code.</p>
<p><strong>Features</strong></p>
<ul style="list-style-type: circle;">
<li>Real-time Speech Recognition: Captures microphone input and converts it to text dynamically as the user speaks.<li>Responsive Design: Works reliably across desktop and mobile clients.</li><li>Seamless Power Apps Integration: Binds easily to Model-Driven and Canvas app text fields.</li><li>Low Code/No Code Deployment: Packaged as a PCF solution for rapid installation.</li></li>
</ul>
<p>
<p><strong>Getting Started</strong></p>
<p><strong>Prerequisites</strong></p>
<p>To use this component, you must have:</p>
<ul style="list-style-type: circle;">
<li>Power Apps environment with PCF support.</li><li>Power Apps CLI installed (for local build/test).</li><li>Node.js</li><li>A modern browser with microphone permissions.</li>
</ul>
<p><strong>Installation</strong></p>
<p>Download / Clone Repository</p>
<p>&nbsp; &nbsp;git clone https://github.com/dynamicsservicesgroup/speech-to-text-pcf.git</p>
<p><br />Import Solution</p>
<ul style="list-style-type: circle;">
<li>&nbsp;Open Power Apps Maker Portal.</li>
<li>&nbsp;Go to Solutions.</li>
<li>&nbsp;Import the SpeechToTextSolution managed/unmanaged solution file.</li>
</ul>
<p>Add Control to a Field</p>
<ul style="list-style-type: circle;">
<li>&nbsp;In a form editor, select a text field.</li>
<li>&nbsp;Change the control type to SpeechToTextControl for applicable form factors.</li>
</ul>
<p>Set Properties (if applicable)</p>
<ul style="list-style-type: circle;">
<li>&nbsp;Configure supported languages.</li>
<li>&nbsp;Toggle real-time vs push-to-talk.</li>
</ul>
<p dir="auto"><strong>Usage</strong></p>
<p dir="auto">Once deployed, the control will render an interactive UI element (microphone icon) next to the bound text field:</p>
<ul style="list-style-type: circle;">
<li dir="auto">Starts recording: Click/Tap the&nbsp;<strong>Start Recording</strong>&nbsp;button.</li>
<li dir="auto">Speak into the Device Microphone: Transcription appears in the text box.</li>
<li dir="auto">Stop recording: Click on&nbsp;<strong>Stop Recording</strong>&nbsp;button.</li>
<li dir="auto">Clear Text: Click on&nbsp;<strong>Clear</strong>&nbsp;button.</li>
<li dir="auto">You can integrate this into Canvas and Model Driven Apps where supported.</li>
</ul>
<p><br /><strong>Contributing</strong></p>
<p>We welcome contributions:</p>
<ul style="list-style-type: circle;">
<li>Fork the repository.</li>
<li>Create a feature branch (git checkout -b feature-xyz).</li>
<li>Submit a Pull Request with clear descriptions and testing instructions.</li>
</ul>
<p><strong>License</strong></p>
<p>This project is released under the MIT License.</p>

