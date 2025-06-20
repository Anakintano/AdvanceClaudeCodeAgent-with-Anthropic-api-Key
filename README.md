<p align="center">
  <img src="https://github.com/user-attachments/assets/5764931f-6a96-4b3c-9702-3cc93389ede0" />
</p>


# 🚀 AI Agent with Live Python Execution & Automated Validation

An end‑to‑end template demonstrating how to build an advanced AI agent using LangChain’s ReAct framework and Anthropic’s Claude API. This agent can:

- 🧠 **Write** Python code  
- 🛠️ **Execute** code live (via a REPL tool)  
- ✅ **Validate** results automatically against test logic or expected properties

Inspired by the MarkTechPost guide *“A Coding Implementation to Build an AI Agent with Live Python Execution and Automated Validation”*.

---

## 🧩 Features

- **ReAct-style prompting**: LangChain agent reasons and acts (via code) step‑by‑step  
- **Python REPL execution**: Captures `stdout`, handles errors, maintains execution state  
- **Validation tools**: Auto‑check outputs (correctness, test‑case results, properties)  
- **Use-cases**: Analytics, algorithm design, ML pipelines, mathematical proofs…

---

## ⚙️ Installation

```bash
pip install langchain langchain-anthropic langchain-core anthropic
````

* `langchain`, `langchain-core`: Agent orchestration
* `langchain-anthropic`, `anthropic`: Claude API integration

---

## 🛠️ Project Structure

```
.
├── agent.py            # Agent + REPL + validator implementation
├── tool.py             # Defines REPL and validation tools
└── examples/
    ├── prime_analysis.py
    ├── sales_analysis.py
    ├── sorting_searching.py
    ├── ml_pipeline.py
```

---

## 📦 Usage

1. Set your API key:

   ```bash
   export ANTHROPIC_API_KEY="your_claude_key_here"
   ```
2. Choose an example, e.g.:

   ```bash
   python examples/prime_analysis.py
   ```
3. Watch the loop: **think → write code → run → validate**
4. View output and logs in your console

---

## 🧪 Examples Included

1. **Prime Number Analysis**

   * List primes 1–200, sum them, find twin primes, average/log gaps
2. **Sales Data Analysis**

   * Build synthetic 24‑month product sales with seasonality
   * Compute growth, trends, correlations, statistical summaries
3. **Algorithm Suite**

   * Code quicksort, mergesort, binary search
   * Test edge cases, run benchmarks, find k‑th largest
4. **ML Pipeline**

   * Generate synthetic classification data
   * Implement gradient‑descent classifier with k‑fold CV
   * Evaluate accuracy, precision, recall

---

## ✅ Validation Features

* **Execution history**: Trace of code & outputs
* **Built-in test suites**: Embedded test cases for each example
* **Confidence**: Ensures code meets expected results & type constraints

---

## 💡 Extendability

* Add new tools (e.g., file I/O, plotting, API call agents)
* Customize validation logic: precision thresholds, error tolerances, schema checks
* Adapt agent for your domain: financial analysis, scientific computing, data engineering

---

## 📘 References

* MarkTechPost tutorial: *A Coding Implementation to Build an AI Agent with Live Python Execution and Automated Validation*
* LangChain’s ReAct agent architecture
* Anthropic Claude API – conversational LLM for code generation

---

## 📬 Contributions & Feedback

PRs welcome! Feel free to submit:

* New case‑studies or domain examples
* Enhanced tooling (e.g. visualization, debugging)
* Improvements to the validation harness

Let’s build smarter, more reliable AI‑powered development workflows! 💬

---

## 📝 License

MIT License
© 2025 Aditya Saxena

```


