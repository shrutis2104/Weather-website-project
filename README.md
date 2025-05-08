# 🌦️ Weather App using Flask, HTML, CSS & JavaScript

This is a simple weather web application that shows the current weather of any city using the **OpenWeatherMap API**. Built with **Flask (Python)** on the backend and a beautiful **HTML/CSS/JS** frontend ✨

---

## 📸 Features

- 🔍 Search weather by city name  
- 🌡️ Shows temperature, weather condition, and weather icon  
- 💻 Built using Flask (Python)  
- 🎨 Frontend made with HTML, CSS, and a little JavaScript  

---

## 🧠 How to Run This Project (Made in PyCharm)

### ✅ Step-by-Step in PyCharm:

1. **Open PyCharm**  
   Open PyCharm and click on `Open` to select the folder containing this project.

2. **Create a Virtual Environment (Optional but recommended)**  
   PyCharm will ask if you want to create a virtual environment — choose *yes* if it pops up.

3. **Install Flask**  
   - Open the terminal inside PyCharm (bottom bar).
   - Run this command:
     ```bash
     pip install flask
     ```

4. **Add Your API Key**
   - Open the `app.py` file.
   - Replace this line:
     ```python
     API_KEY = "YOUR_API_KEY"
     ```
     with your actual API key:
     ```python
     API_KEY = "your_actual_api_key_here"
     ```

5. **Run the App**
   - Right-click on `app.py` → Click `Run 'app'`
   - OR click the green play ▶️ button in the top-right corner of PyCharm.

6. **View in Your Browser**
   - Once it runs, it will show this message in the terminal:
     ```
     Running on http://127.0.0.1:5000/
     ```
   - Open your browser and go to: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

## 🗝️ API Key Info

This app uses the [OpenWeatherMap API](https://openweathermap.org/api).  
To use it, you'll need to [sign up](https://home.openweathermap.org/users/sign_up) and generate your own free API key.

> ⚠️ *IMPORTANT*: Do not share your API key publicly in real-world projects. If you're just sharing with a trusted person , it's okay for one-time usage.

---

## 📁 Project Structure

weather-app/

│

|─ static/

 │─ style.css

│

|─ templates/

 │─ index.html

│

|─ app.py

├─ README.md


---

## 🙋‍♀️ Author

Made with 💙 by Shruti  
Give a ⭐ if you find this project useful!

---

## 📬 License

This project is free to use and modify.  
Be kind 💌
