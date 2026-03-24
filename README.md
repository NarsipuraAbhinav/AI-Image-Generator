# 🎨 AI Image Generator

A full-stack web application that generates images from text prompts using the OpenAI API.

![AI Image Generator](https://user-images.githubusercontent.com/109419444/229976396-14ccb4b7-7e66-49a2-87ab-b2286cc2eff9.png)

## Tech Stack
- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **AI:** OpenAI API (DALL·E)
- **Database:** MongoDB
- **Storage:** Cloudinary

## Features
- Generate images from text prompts using DALL·E
- Share generated images to a community gallery
- Search images by prompt or creator name
- 90%+ prompt-to-image relevance through optimized prompt engineering

## Getting Started
```bash
# Clone the repo
git clone https://github.com/NarsipuraAbhinav/AI-Image-Generator.git

# Install server dependencies
cd server && npm install

# Install client dependencies
cd ../client && npm install
```

## Environment Variables

**Server `.env`**
```
MONGODB_URL=your_mongodb_url
OPENAI_API_KEY=your_openai_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

## Run Locally
```bash
# Start server
cd server && npm start

# Start client
cd client && npm run dev
```

## Author
**Narsipura Abhinav** — [GitHub](https://github.com/NarsipuraAbhinav) · [LinkedIn](https://www.linkedin.com/in/narsipura-abhinav-a81949226/)
