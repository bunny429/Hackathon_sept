# Go Travel - Hackathon Project

Go Travel is a multi-page travel website prototype built during a hackathon. The project combines trip booking flow with eco-friendly suggestions so users can plan travel in a smarter and more sustainable way.

## Website Concept

The concept of the website is simple:

1. Help users start trip planning quickly.
2. Guide users toward eco-friendly transport choices.
3. Suggest sustainable stay options and activities.

This creates a travel experience that balances convenience with environmental awareness.

## Website Preview

Main preview image (.png):

![Go Travel Preview](image.png)

Alternate preview/logo image (.png):

![Go Travel Alternate Preview](Untitled.png)

## Project Structure

- index.html: Home page and main entry point.
- page_1.html: Travel booking page.
- page_2.html: Eco-friendly transport suggestion page.
- page_3.html: Eco-friendly accommodation and activity suggestion page.
- main.css: Shared styling for the pages.
- main.py: Python voice assistant prototype (Windows-focused).
- main2.py: Simple Python sample script.

## Core Features

- Multi-page user journey.
- Booking form on page 1.
- Eco transport recommendation flow on page 2.
- Eco accommodation/activity suggestions on page 3.
- Shared visual styling across pages.

## How To Run The Website

1. Open the project folder in VS Code.
2. Open index.html in your browser.
3. For best results, run with a local server (Live Server extension).

### Run With Live Server (Recommended)

1. Install the Live Server extension in VS Code.
2. Right-click index.html.
3. Click Open with Live Server.

## Python Files (Optional)

### main.py

Install dependencies:

```bash
pip install SpeechRecognition pyaudio pywin32
```

Run:

```bash
python main.py
```

Notes:

- Requires a microphone.
- Uses Windows SAPI voice through win32com.

### main2.py

```bash
python main2.py
```

## Current Notes

- Some internal links in HTML files may still use localhost URLs.
- Some HTML structure can be refined for production quality.
- All referenced image files should be kept in the same project folder.

## Next Improvements

1. Replace localhost links with relative links everywhere.
2. Improve semantic HTML structure.
3. Add stronger form validation and messages.
4. Improve mobile responsiveness further.
5. Add error handling and command coverage in the Python assistant.
