`Diet-and-Workout-Recommendation-System-using-OpenAI`

````markdown
# 🥦💪 Diet and Workout Recommendation System using OpenAI

A smart web application that generates **personalized diet and workout plans** based on user input such as age, gender, region, dietary preferences, and health conditions — powered by **OpenAI GPT** and built with **Flask**.

---

## 📌 Features

- 🍽️ Recommends **6 breakfast options**, **5 dinner meals**
- 🏋️ Suggests **6 workout routines** suited to user's profile
- 🗺️ Lists **6 restaurant suggestions** based on region & preferences
- 🧠 Uses **OpenAI GPT** for contextual and dynamic generation
- 🖥️ Built with **Flask** + Bootstrap for a responsive UI

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/username/project-name.git
cd project-name
````

### 2. Set up a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set your OpenAI API Key

Open `app.py` and replace:

```python
os.environ['OPENAI_API_KEY'] = 'your-api-key-here'
```

> Or set it in your terminal before running:

```bash
export OPENAI_API_KEY='your-api-key'  # For Unix/macOS
set OPENAI_API_KEY=your-api-key       # For Windows
```

### 5. Run the app

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## ⚙️ Tech Stack

* 🧠 [OpenAI GPT-3/4](https://platform.openai.com/)
* 🌐 Flask (Python)
* 🎨 Bootstrap 4
* 🧼 Regex (for parsing AI output)
* 🧾 HTML & Jinja Templates

---

## 🏗️ Project Structure

```
├── app.py                    # Main Flask application
├── templates/
│   ├── index.html            # User input form
│   └── result.html           # Displays recommendations
├── static/                   # (Optional) Static files like CSS or JS
├── requirements.txt          # Required Python packages
└── README.md                 # Project documentation
```

---

## 💡 How It Works

1. User fills in a form with details (age, gender, height, etc.)
2. The backend uses OpenAI to generate a structured response
3. Regex is used to parse recommendations from GPT's reply
4. The results are rendered dynamically on the result page

---

## ✅ To-Do / Improvements

* [ ] Add user login and saved plans
* [ ] Include lunch/snack options
* [ ] Support for multiple languages
* [ ] Integrate Google Maps for restaurants
* [ ] Export plan as PDF or printable version

---

## 🤝 Contributing

Contributions, suggestions, and issues are welcome!
Just fork the repo, create a new branch, and make a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Credits

* Project by \[Original Author’s Name or GitHub Handle]
* Collaborator: \[Your Name or GitHub]
* Powered by [OpenAI](https://openai.com)
