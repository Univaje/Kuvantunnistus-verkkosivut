# Kuvantunnistus-verkkosivut

**Kuvantunnistus-verkkosivut** is a web-based project for image recognition (kuvantunnistus) with separate front-end and back-end components.

---

## 🎯 Project structure

- `Frontend/` — The web client, built using HTML / CSS / JavaScript.  
- `Backend/` — The server-side component (API) handling image recognition logic.  

---

## 🛠️ Features

- Upload or supply images via the web interface.  
- Back-end processes images and returns detection/recognition results.  
- Responsive UI for image upload and result display.  

---

## 🚀 Getting Started

### Prerequisites

- Node.js and npm (or yarn) for the front-end (if applicable)  
- A server runtime (e.g., Node.js + Express, or Python + Flask) for the back-end  
- Any required libraries for image recognition (e.g., TensorFlow, OpenCV)  

### Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/Univaje/Kuvantunnistus-verkkosivut.git
   cd Kuvantunnistus-verkkosivut
   ```
2. Setup the back-end

```bash
  cd Backend
  npm install            
```
3. Setup the front-end
```bash
  cd ../Frontend
  npm install          
```

4. Configure environment variables or settings (if any)

   - API endpoint URL, port, model files path, etc.

5. Run the services
  in Backend and Frontend folder
  npm start

---

###📁 Usage

- Navigate to the front-end page (e.g., http://localhost:3000)
- Upload or select an image
- The back-end API processes the image and returns results
- View the recognition output in the UI

###🧪 Testing

I need to upload the tests I made for this

###📦 Deployment

- You can deploy the back-end on a server 
- Serve the front-end via static hosting
- Ensure CORS and API endpoint configurations are set correctly


###🙏 Acknowledgements

This was group project for my studies
Thank you for the friends int the group that made parts for this.
For this project I created backend, API, tests and all the codes containing backend connections in frontend. 
