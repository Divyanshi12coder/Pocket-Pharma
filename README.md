# Pocket-Pharma
# PocketPharma: Your Pocket-Friendly Pharmacy Assistant

**Project Details**
- **Project Name:** PocketPharma
- **Status:** Production-ready application (evolved from Live The Code 3.0 hackathon)

## Overview

PocketPharma is a web application that revolutionizes how people access affordable medication by leveraging AI to identify medicines from photos and suggest cost-effective generic alternatives. What started as a hackathon project has evolved into a robust, production-ready platform.

## Mission

Our mission is to make healthcare more accessible and affordable for everyone by providing an easy-to-use tool that helps users find generic alternatives to brand-name medications.

## Features

- **Image-based Medicine Identification:** Upload a photo of your medicine for instant recognition.
- **AI-powered Analysis:** Utilizes cutting-edge AI models to analyze and identify medications.
- **Generic Alternative Suggestions:** Provides a list of generic alternatives to brand-name medicines.
- **Price Comparison:** Offers side-by-side price comparisons between brand-name and generic options.
- **User-friendly Interface:** Intuitive design for easy navigation and use.

## How It Works

1. **Upload:** Users upload a photo of their medicine through the web interface.
2. **Analyze:** Our AI models process the image to identify the medication.
3. **Search:** The system searches for generic alternatives to the identified medicine.
4. **Compare:** Users are presented with a list of generic options, including price comparisons.
5. **Choose:** Armed with this information, users can make informed decisions about their medication purchases.

## Project Structure

```
PocketPharma/
├── backend/          # Node.js/Hono backend services
├── frontend/         # Next.js React frontend application
└── README.md         # This file
```

## Technical Stack

### Frontend
- Next.js (React framework)
- TypeScript
- Tailwind CSS for styling

### Backend
- Hono (lightweight web framework for edge computing)
- Groq SDK for AI text generation
- Google's Generative AI (Gemini model)
- LLaVA (Large Language and Vision Assistant) model


## Future Enhancements

- Integration with official pharmaceutical databases
- Mobile app development
- Personalized medicine reminders and tracking
- Enhanced pricing analytics
