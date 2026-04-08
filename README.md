#  **Minimal ReAct Agent in Python**

---

## 📌 **Overview**

- This project implements a **minimal ReAct (Reasoning + Acting) agent** in Python  
- A ReAct agent combines:
  - **Reasoning (thinking step-by-step)**
  - **Acting (using tools to get results)**  
- This is a **mock implementation** (no API required)  
- Designed for **learning and demonstration purposes**

---

## ⚙️ **How It Works**

- **User Query**
- → **Reasoning (Thought)**
- → **Action Selection (Tool)**
- → **Tool Execution**
- → **Final Answer**

---

## 🧩 **Components**

### 🔹 **1. Calculator Tool**
- Evaluates mathematical expressions using Python `eval()`  
- Example:
  - `10+5 → 15`

---

### 🔹 **2. ReAct Agent (Mock)**
- Simulates an AI model  
- Generates:
  - **Thought**
  - **Action**
  - **Action Input**

---

### 🔹 **3. Agent Controller**
- Uses **regex** to extract tool input  
- Executes the tool  
- Prints the final answer  

---
**How to Run (Google Colab)**
- Open Google Colab
- Copy and paste the full code
- Run the cell

