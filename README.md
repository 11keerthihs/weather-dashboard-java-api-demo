# 🌐 REST API Client (Java)

## 📌 Internship Task - 2

**Title:** REST API Client
**Objective:** Develop a Java application that consumes a public REST API and displays data in a structured format.

---

## 🧾 Project Description

The **REST API Client** is a Java-based application that fetches real-time data from a public API (such as a Weather API) and displays it in a structured and readable format.

This project demonstrates how Java applications can interact with external services over HTTP, process JSON responses, and present meaningful information to users.

---

## 🎯 Features

* 🌍 Fetch data from a public REST API
* 🔗 Send HTTP GET requests
* 📦 Parse JSON responses
* 📊 Display structured output in console
* ⚠️ Handle API and network errors gracefully

---

## 🛠️ Technologies Used

* **Java**
* **HTTP Client (java.net.HttpURLConnection / HttpClient)**
* **JSON Parsing Library**

  * `org.json` / `Gson` / `Jackson`

---

## ⚙️ How It Works

### 1. Sending HTTP Request

The application sends an HTTP GET request to a public API endpoint (e.g., weather data API).

### 2. Receiving Response

The API returns data in JSON format.

### 3. Parsing JSON

The program extracts relevant fields such as:

* Temperature
* Weather condition
* Humidity
* Location

### 4. Displaying Output

The extracted data is formatted and displayed in a clean and readable structure.

---

## ▶️ How to Run

1. Compile the Java program:

```bash id="s2g6dl"
javac RestApiClient.java
```

2. Run the program:

```bash id="3v9i4l"
java RestApiClient
```

---

## 📂 Example API Used

* 🌦️ Weather API (e.g., OpenWeatherMap / WeatherAPI)

Example endpoint:

```id="t1r3ys"
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY
```

---

## 📸 Sample Output

```id="h0j8sl"
Location: London
Temperature: 25°C
Weather: Clear Sky
Humidity: 60%
```

---

## ⚠️ Error Handling

The program handles:

* Invalid API URL
* Network issues
* JSON parsing errors
* Invalid API key

---

## 📚 Learning Outcomes

* Understanding REST APIs
* Handling HTTP requests in Java
* Working with JSON data
* Building real-world API-based applications

---

## 📌 Conclusion

This project demonstrates how Java applications can consume REST APIs and process real-time data efficiently. It builds a strong foundation for developing modern, data-driven applications.

---

## 👨‍💻 Author

Keerthi HS
Internship Project Submission
<img width="1206" height="630" alt="Image" src="https://github.com/user-attachments/assets/a67c0588-172a-4db6-80ad-c70e93902b4f" />
