# Handwritten-Equation-Solver

A web-based application that recognizes handwritten math equations from images and solves them step-by-step using symbolic computation.

## 🔍 Features

- 🖼️ Upload an image of a handwritten or printed equation.
- 🧪 Uses **OpenCV** for image preprocessing.
- 🔎 Applies **Tesseract OCR** to recognize mathematical expressions.
- 📐 Parses and solves equations using **SymPy**, including:
  - Implicit multiplication (e.g., `2x`, `log2`, `3(x+1)`)
  - Algebraic simplification and expansion
  - Step-by-step solution generation

## 🚀 Demo

> Upload an image like `x^2 - 5x + 6 = 0` and get steps like:
1. Move all terms to one side  
2. Expand the equation  
3. Simplify  
4. Solve for x  

## 🛠️ Tech Stack

- **Frontend**: HTML, Jinja2 (via Flask templates)
- **Backend**: Python (Flask)
- **Libraries**: OpenCV, Tesseract OCR, SymPy, PIL
  
## 📂 Project Structure
├── app.py
├── templates/
│ └── index.html
├── static/
├── uploads/
├── requirements.txt


## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/Adeel-Haider-03/Handwritten-Equation-Solver.git
cd handwritten-equation-solver

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

📦 Install Tesseract

🖼️ Sample Input

✅ Output
text
Copy
Edit
Equation detected: x^2 - 5x + 6 = 0

Step-by-step:
1. Move all terms to the left side
2. Expand
3. Simplify
4. Solve

✅ Solution: x = 2, x = 3
📄 License
MIT

🙌 Acknowledgments
Tesseract OCR

SymPy

OpenCV

## 📂 Project Structure

