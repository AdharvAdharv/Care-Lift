# CareLift 🚀💙

CareLift is a **charity-based crowdfunding platform** designed to connect donors with those in need. It provides a **clean, user-friendly, and responsive** interface to help raise and contribute funds for various causes.

## 🌟 Features

- 🎯 **Campaign Pages** – Showcase fundraising campaigns with relevant details.  
- 📱 **Responsive Design** – Works seamlessly on desktops, tablets, and mobile devices.  
- 🎨 **Modern UI** – Built with clean and structured HTML and CSS.  
- 🚀 **Hosted with Node.js** – Ensuring fast and reliable performance.  

## 🛠️ Technologies Used

- **Frontend:** React, HTML, Tailwind CSS  
- **Backend & Hosting:**  Node.js (Express.js)
- **Database:** MongoDB
- **Containerization:** Docker

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone git@github.com:AdharvAdharv/Care-Lift.git
cd Care-Lift
2️⃣ Run with Docker
Using Docker Commands
🔹 Build the Docker image:

sh

docker build -t carelift .
🔹 Run the container:

sh

docker run -p 3000:3000 --env-file .env carelift
(Make sure your .env file contains the required environment variables.)

Using Docker Compose (Recommended)
If you have a docker-compose.yml file, run:

sh

docker-compose up -d
(This will automatically set up the frontend, backend, and database.)


