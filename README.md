# ReLive — See How Cities Have Changed Over Time

**ReLive** is a creative web app built for the "One API to Rule Them All" hackathon category. It uses the Wikipedia API to fetch information about any city in the world. With an elegant UI, dark mode toggle, loading animation, and ChatGPT integration, ReLive offers an immersive experience to explore city histories.

---

## Features

- Search any city (e.g., Paris, London)
- Dark mode toggle for better readability
- Animated loader while fetching data
- ChatGPT integration (optional)
- Wikipedia REST API for real-time data
- Deployed frontend via Netlify

---

## Tech Stack

### Frontend:
- React.js — UI library
- Tailwind CSS — Styling and dark mode
- Axios — HTTP client
- Netlify — For deployment

### Backend:
- Node.js — JavaScript runtime
- Express.js — Server framework
- CORS — Enable frontend-backend communication
- Wikipedia REST API — To fetch city summaries

---

## Folder Structure

Hackaton/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ │ ├── CityCard.js
│ │ │ └── Loader.js
│ │ ├── App.js
│ │ └── index.js
│ ├── public/
│ ├── tailwind.config.js
│ ├── postcss.config.js
│ └── package.json
├── server/ # Node.js backend
│ ├── app.js
│ └── package.json
└── README.md


---
![image](https://github.com/user-attachments/assets/21f914cf-daca-4f83-b063-32b3b7657135)
![WhatsApp Image 2025-07-05 at 04 08 57_f268c970](https://github.com/user-attachments/assets/a30bc82d-1f65-4880-81ff-d69b6eb13b61)
![WhatsApp Image 2025-07-05 at 05 03 23_2521d50d](https://github.com/user-attachments/assets/a348d6e4-9441-488b-b150-7a690e2ed263)
![WhatsApp Image 2025-07-05 at 04 11 12_893b8423](https://github.com/user-attachments/assets/fe29c907-f04e-49e6-8fa9-b778db815ec2)
![WhatsApp Image 2025-07-05 at 04 11 13_98f94fe0](https://github.com/user-attachments/assets/83108adc-cf94-4499-8c6f-954f4381ff18)


## Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/relive.git
cd Hackaton

### Backend Setup
cd server
npm install
node app.js

### Frontend Setup
cd client
npm install
npm start


API Used
We use the Wikipedia REST API to fetch clean and concise information about cities using this endpoint:

ruby
Copy
Edit
GET https://en.wikipedia.org/api/rest_v1/page/summary/{city}
Example:

ruby
Copy
Edit
https://en.wikipedia.org/api/rest_v1/page/summary/London


One API to Rule Them All — Hackathon Innovation Challenge

Stretching the Wikipedia API to offer a sleek and creative city exploration experience.

Wikipedia Foundation for the open API

Tailwind CSS team

OpenAI for ChatGPT integration (optional)


