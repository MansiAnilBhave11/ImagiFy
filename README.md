 ImagiFy – AI Image Generator

ImagiFy is a full-stack MERN (MongoDB, Express, React, Node.js) web application that allows users to generate AI-powered images based on text descriptions.
The app offers 5 free image generations for new users, after which they can purchase more credits using an integrated payment system.

With secure authentication, credit tracking, and a user-friendly interface, ImagiFy provides a smooth and creative AI art generation experience.

🚀 Features

🖌️ AI Image Generation – Convert your text prompts into high-quality AI-generated images.

💰 Credit System – Users start with 5 free image generations. Additional credits can be purchased securely.

🔐 Secure Authentication – Login and signup using JWT authentication for data protection.

📊 Credit Tracking – Real-time tracking of remaining credits for each user.

💳 Payment Integration – Integrated payment gateway (like Stripe or Razorpay) for purchasing credits.

⚡ Responsive UI – Clean, modern interface built with React for smooth user experience.

☁️ Cloud Storage – AI-generated images stored securely for user access.

🛠️ Tech Stack
Layer	Technology
Frontend	React.js, Tailwind CSS, Axios
Backend	Node.js, Express.js
Database	MongoDB, Mongoose
Authentication	JWT, bcrypt.js
Payments	Stripe / Razorpay API
AI Integration	OpenAI API / Stability AI API
Hosting	Vercel (frontend) & Render (backend)
⚙️ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/yourusername/ImagiFy.git
cd ImagiFy

2️⃣ Install Dependencies

Backend:

npm install


Frontend:

cd client
npm install

3️⃣ Add Environment Variables

Create a .env file in the root folder and add the following:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_key
OPENAI_API_KEY=your_openai_api_key
PORT=5000

4️⃣ Run the Application

Start both frontend and backend servers:

npm run dev

💡 Usage

Sign up or log in to your account.

You’ll receive 5 free credits to generate images.

Enter a text prompt describing your desired image.

The AI will generate a unique, high-quality image based on your input.

When free credits run out, buy more credits via the payment system.

🧩 Future Enhancements

🌈 Add image history and download option.

🖼️ Add “art style” filters (anime, realistic, sketch, etc.).

👩‍💻 Enable community sharing of AI artwork.

📱 Create a PWA for mobile access.

🔔 Add email notifications for credit updates.

💬 Motivation

The idea behind ImagiFy is to make AI art generation simple, accessible, and fun.
It’s designed for creators, designers, and enthusiasts who want to explore the possibilities of AI-generated visuals with ease and security.
