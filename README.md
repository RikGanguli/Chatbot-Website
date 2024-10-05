
<h1>ChatGPT-like Website with BlenderBot</h1>

<p>This project is a ChatGPT-like website that allows users to have real-time conversations with a chatbot. The backend is powered by Python and Flask, while the frontend is built using HTML, CSS, and JavaScript. The chatbot model used is Facebook's BlenderBot, which handles conversation history for more interactive and contextual responses. The <strong>Transformers</strong> library is used to implement the chatbot.</p>

<h2>Features</h2>
<ul>
    <li>Real-time chat interface with a simple, user-friendly UI.</li>
    <li>Conversation history is maintained, allowing the chatbot to respond based on previous messages.</li>
    <li>Utilizes Facebook's BlenderBot from the Transformers library for intelligent, context-aware responses.</li>
    <li>Lightweight and easy to deploy on any Flask-supported environment.</li>
</ul>

<h2>Tech Stack</h2>

<h3>Backend:</h3>
<ul>
    <li>Python</li>
    <li>Flask</li>
    <li>Transformers library (Hugging Face)</li>
</ul>

<h3>Frontend:</h3>
<ul>
    <li>HTML for structure</li>
    <li>CSS for styling</li>
    <li>JavaScript for dynamic interaction</li>
</ul>

<h2>How to Run</h2>

<h3>Prerequisites:</h3>
<p>Ensure you have the following installed:</p>
<ul>
    <li>Python 3.7+</li>
    <li>pip</li>
</ul>

<h3>Setup Instructions:</h3>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/RikGanguli/Chatbot-Website.git
        </code></pre>
    </li>
    <li>Install required dependencies:
        <pre><code>pip install -r requirements.txt
        </code></pre>
    </li>
    <li>Run the Flask app:
        <pre><code>python app.py
        </code></pre>
    </li>
    <li>Open your browser and go to:
        <pre><code>http://127.0.0.1:5000
        </code></pre>
    </li>
</ol>

<h2>Conversation Model</h2>

<p>The project uses BlenderBot from Facebook, a transformer-based conversational AI model, to generate responses.</p>

<h2>Transformers Setup</h2>

<p>To use the BlenderBot model, we rely on the Hugging Face Transformers library. The relevant model is loaded in the backend Flask server and is used to generate replies based on user inputs and conversation history.</p>

<h2>Credits</h2>
<p>Developed by <strong>Rik Ganguli Biswas</strong> as a part of the IBM AI Developer Professional Certificate</p>
