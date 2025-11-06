# 💰 Finanzas PRO+

### 🧾 Project Summary  
**Finanzas PRO+** is a lightweight application designed to record, analyze, and visualize financial transactions (income and expenses).  
Its main goal is to provide key metrics such as **income**, **expenses**, and **net balance**, along with useful charts (bar, donut, flow line, waterfall, boxplot, pareto) and basic recommendations to help users improve savings and expense management.

---

## 🎯 Objectives
- 📂 Record and import financial transactions in **CSV** format.  
- 📊 Display **KPIs** and **interactive charts** via a **Tkinter + Matplotlib** GUI.  
- 📝 Generate **Markdown reports** and export visualizations as **PNG, PDF, or ZIP** files.  
- 💡 Offer simple analytics such as **runway**, **savings gap**, and **category-based alerts**.

---

## 🛠️ Tools & Technologies
| Category | Tools |
|-----------|--------|
| **Language** | Python 3 |
| **GUI** | Tkinter |
| **Visualization** | Matplotlib |
| **Data Format** | CSV (`data/finanzas.csv`) |

---

## 📊 Project Outcome
The application allows users to load, record, and analyze financial movements through clear visualizations and an automatically generated Markdown report.  
It is designed as an **educational tool** or **prototype** for basic **personal finance** or **small business** management.

---

## 👥 Author
Project developed and organized by the team **IA’m Your Father**,  
part of the **Samsung Innovation Campus** program.

---

##⚙️ Installation & Execution
1. Clone the repository
git clone https://github.com/santty1906/finanzas-pro-plus.git
cd finanzas-pro-plus
2. Create a virtual environment

Windows (CMD):

python -m venv venv
venv\Scripts\activate

Git Bash / macOS / Linux:

python -m venv venv
source venv/Scripts/activate
3. Install dependencies
pip install -r requirements.txt

If the file doesn’t exist yet, install manually:

pip install pandas matplotlib
4. Run the application
python finanzas_pro_plus.py
