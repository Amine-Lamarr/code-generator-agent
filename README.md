<h1>🧠 AI Programming Pipeline</h1>

<p>An automated AI pipeline that analyzes programming problems, generates Python code, executes it, and provides feedback — all in one flow.</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>🧩 <b>Problem Analyzer</b> — breaks down a problem into clear, logical steps.</li>
  <li>💻 <b>Code Generator</b> — transforms the analysis into executable Python code.</li>
  <li>⚙️ <b>Code Executor</b> — runs the generated code safely and provides human-readable feedback.</li>
  <li>🧠 Powered by an LLM (<code>llm.invoke()</code>), compatible with frameworks like <b>LangChain</b> .</li>
</ul>

<hr>

<h2>🏗️ Pipeline Flow</h2>

<pre>
Problem ➜ Analyzer ➜ Code Generator ➜ Executor ➜ Feedback
</pre>

<hr>

<h2>📁 Project Structure</h2>

<pre>
├── analyzer_prompt
├── code_prompt
├── excuter_prompt
├── analyzer(state)
├── CodeGenerator(state)
├── Excuter(state)
</pre>

<hr>

<h3>2. Install dependencies</h3>
<pre><code>pip install langchain openai
</code></pre>

<p><i>You may need to install other packages depending on the generated code.</i></p>

<hr>

<h2>🧩 Example Output</h2>

<p><b>Input:</b></p>
<pre><code>Write a program to check if a number is prime.
</code></pre>

<p><b>Output:</b></p>
<pre><code>Analyzer: Step 1... Step 2...
Code Generator: (Python code)
Executor: Code executed successfully! Handles edge cases correctly.
</code></pre>

<hr>

<h2>⚠️ Notes</h2>

<ul>
  <li>If the code requires missing packages, you’ll get a <b>warning</b> instead of an error (e.g., <code>ModuleNotFoundError</code>).</li>
  <li>Execution is sandboxed using a temporary Python file for safety.</li>
  <li>Easily integrable with larger LLM workflows.</li>
</ul>

<hr>

<h2>💡 Future Improvements</h2>

<ul>
  <li>Handle user inputs (<code>input()</code>) automatically.</li>
  <li>Add context or memory between runs.</li>
  <li>Create a Streamlit UI for better visualization.</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p><b>Amine</b> — AI Enthusiast & Future Engineer 🇲🇦<br>
💬 Passionate about building intelligent systems that can reason, generate, and execute code autonomously.</p>

<hr>

<p>⭐ Don’t forget to star the repo if you like it!</p>
