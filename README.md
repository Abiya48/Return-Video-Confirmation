# AI Return Video Confirmation System

## Overview
The AI Return Video Confirmation System is a smart web application designed to automate product return verification for e-commerce platforms. The system analyzes customer-uploaded return or unboxing videos, validates shipment details using OCR, and leverages AI to detect potential fraud and provide instant verification decisions.

By combining video analysis, label verification, and intelligent decision-making, the platform helps businesses reduce return fraud, improve operational efficiency, and build customer trust.

## Features
- 🎥 AI-powered return/unboxing video analysis
- 📝 OCR-based shipping label extraction and validation
- 🤖 Automated fraud detection using Gemini AI
- ✅ Instant return approval or rejection decisions
- 📊 Structured verification reports
- 🚀 Fast, scalable, and user-friendly interface

## Tech Stack

### Frontend
- React.js
- TypeScript
- Tailwind CSS

### AI & OCR
- Google Gemini 2.5 Flash
- OCR for label extraction
- Prompt Engineering and Structured Outputs

### Backend
- API Services
- Data Validation and Processing

## How It Works
1. User uploads a return/unboxing video.
2. The system extracts shipment information using OCR.
3. AI analyzes the video for tampering indicators and suspicious activities.
4. Extracted data is validated against order records.
5. The system generates a verification report.
6. A final decision is returned:
   - Approved
   - Rejected
   - Manual Review Required

## Use Cases
- E-commerce return verification
- Return fraud prevention
- Automated claims processing
- Warehouse and logistics validation

## Future Enhancements
- Real-time video verification
- Advanced anomaly detection models
- Multi-language OCR support
- Integration with major e-commerce platforms
- Fraud risk scoring system

## Team
- Mathew Biju George – System Architecture & AI Integration
- Jetcin G Jacob – AI Services & Prompt Engineering
- Abiya George – UI/UX Design & Frontend Development
- Arathy Krishna – Application Logic & State Management

## License
This project is developed for educational and innovation purposes.


# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
