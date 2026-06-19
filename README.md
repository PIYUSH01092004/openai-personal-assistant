# OpenAI Personal Assistant

A lightweight, asynchronous web application featuring a Python-powered backend integrated with the OpenAI Chat Completions API and a responsive, modern frontend interface. 

This repository serves as a foundational AI engineering portfolio project, demonstrating production-ready practices including end-to-end API integration, asynchronous client-server communication, secure environment variable management, and targeted prompt engineering.

---

## 🚀 Key Technical Features

* **Asynchronous Execution**: Utilizes JavaScript Fetch API to handle asynchronous `POST` requests to the backend, enabling real-time UI updates and state management (loading indicators) without page reloads[cite: 8].
* **Robust AI Integration**: Engineered around the OpenAI SDK (`client.chat.completions.create`) utilizing the `gpt-4o` foundation model[cite: 7].
* **System Prompt Engineering**: Implements structured system-level conditioning (`"Act like a powerful personal assistant"`) to govern model persona, tone, and response constraints[cite: 7].
* **Production Security**: Implements strict decoupling of configuration from source code using `python-dotenv` to manage secrets locally, preventing sensitive API credential leaks[cite: 3, 7].
* **Responsive UI/UX**: Designed a clean, minimalist front-end dashboard using standard semantic HTML5 and vanilla CSS3 featuring intuitive state transitions[cite: 8, 9].

---

## 🛠️ Architecture & Tech Stack

### Backend
- **Language**: Python
- **Framework**: Flask (WSGI Web Application Server)
- **API Client**: OpenAI Python SDK
- **Configuration**: Python-dotenv

### Frontend
- **Structure**: HTML5
- **Styling**: CSS3 (Custom Flexbox layout, smooth transitions)
- **Interactivity**: Vanilla JavaScript (ES6+, Async/Await Fetch API)

---


