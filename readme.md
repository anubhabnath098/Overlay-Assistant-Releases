# Overlay Assistant

**Your invisible AI-powered meeting companion.**

Overlay Assistant is an AI-powered desktop application designed to assist you during online meetings, interviews, discussions, and other screen-based activities.

It provides a floating overlay that can remain hidden during meetings while allowing you to interact with Google's Gemini models, send prompts, capture screenshots, process visual context, and listen to conversations in real time.

Whether you're attending a meeting on **Google Meet, Microsoft Teams, Zoom, Webex**, or another platform, Overlay Assistant gives you access to an AI assistant without having to constantly switch between windows.

The application supports multiple Gemini models, real-time audio transcription through Deepgram, customizable prompts, screenshot-based queries, keyboard shortcuts, and much more.

---

## Latest Release — v2.3.3

**Released: November 23, 2026**

Download the appropriate version for your operating system.

| Operating System | Package | Download |
|---|---|---|
| Windows (64-bit) | `.exe` | [Download for Windows](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/download/v2.3.3/OverlayAssistantSetup-2.3.3-x64.exe) |
| Linux (64-bit) | `.AppImage` | [Download AppImage](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/download/v2.3.3/OverlayAssistant-2.3.3-x64.AppImage) |
| Ubuntu / Debian (64-bit) | `.deb` | [Download DEB](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/download/v2.3.3/OverlayAssistant-2.3.3-x64.deb) |
| Fedora / RHEL (64-bit) | `.rpm` | [Download RPM](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/download/v2.3.3/OverlayAssistant-2.3.3-x64.rpm) |

**Other release resources:**

- [View All Releases](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases)
- [View Latest Release](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/latest)

> **Note:** macOS builds are not currently available. The AppImage package is intended for Linux systems.

---

## Features

### 1. Invisible Meeting Overlay

- Designed to remain invisible during meetings and screen-sharing sessions.
- Works alongside platforms such as Google Meet, Microsoft Teams, Zoom, and Webex.
- Floating, draggable, and resizable overlay window.
- Resize the chatbox independently for a more comfortable experience.
- Adjustable overlay opacity and text opacity.
- Choose different cursor types, including the standard pointer and caret cursor, to blend the overlay with the underlying application.
- **Passthrough Mode:** Interact directly with the window underneath the overlay without having to close or hide it.

### 2. AI-Powered Chat Assistant

- Send custom prompts directly through the integrated chatbox.
- Choose from a range of available Google Gemini models.
- Maintain conversational context across multiple queries.
- **Clear Conversation:** Remove the existing conversation context whenever required.
- Retry failed prompts, including requests that fail due to API rate limits.
- **Capture and Send:** Instantly capture a screenshot and submit it to the selected LLM along with your prompt.

### 3. Real-Time Audio Listening

- Listen to the other person during a meeting.
- Uses the Deepgram API for audio transcription.
- Send conversational context to the AI assistant for relevant responses.
- Enable or disable listening whenever required.

### 4. Screenshot-Based Context

- Capture up to **10 screenshots** of your screen while the overlay is invisible.
- Attach captured screenshots to your prompts to provide additional visual context to the LLM.
- Capture and Send functionality for immediately submitting a screenshot along with a query.
- Useful for understanding presentations, documents, code, diagrams, and other on-screen content.

### 5. Custom Prompts and Attachments

- Create and save your own custom prompt.
- Enable or disable the custom prompt using a toggle.
- When enabled, the saved custom prompt is automatically included with every query sent to the LLM.
- Attach up to **4 PDF or image files** alongside your custom prompt.
- Useful for providing background information, reference material, instructions, and additional context to the AI assistant.

### 6. Customizable Keyboard Shortcuts

Configure your own hotkeys for three important functions:

- **Passthrough:** Toggle interaction with the underlying application.
- **Show/Hide Overlay:** Quickly toggle the visibility of the overlay.
- **Listening Toggle:** Enable or disable listening to the other person.

### 7. Window and Appearance Customization

- Adjust overlay window opacity.
- Adjust text opacity independently.
- Drag and resize the overlay window.
- Resize the chatbox independently.
- Change cursor appearance to blend with the underlying application.
- Passthrough functionality for interacting with applications underneath the overlay.

### 8. Proxy Configuration

- Dedicated proxy configuration window.
- Configure proxy settings directly within the application.
- Particularly useful for users connected to organizational, corporate, or institute networks that require a proxy to access external APIs.

### 9. Automatic Updates

- Built-in automatic update checking.
- No need to regularly visit this GitHub repository to check for new releases.
- Whenever a newer version is available, an **Update** button appears inside the application.
- Update the application directly without manually downloading every new release from GitHub.

---

## Installation Guide

Choose the installation instructions corresponding to your operating system.

### Windows

1. Download the Windows `.exe` installer from the [Latest Release](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/latest).
2. Run the downloaded installer.
3. Follow the installation instructions.
4. Launch Overlay Assistant.

### Ubuntu / Debian

1. Download the `.deb` package.
2. Open a terminal in the download directory.
3. Execute the following command:

   ```bash
   sudo apt install ./OverlayAssistant-2.3.3-x64.deb
   ```

4. Once installation is complete, launch Overlay Assistant.

### Fedora / RHEL

1. Download the `.rpm` package.
2. Open a terminal in the download directory.
3. Execute:

   ```bash
   sudo dnf install ./OverlayAssistant-2.3.3-x64.rpm
   ```

4. Once installation is complete, launch Overlay Assistant.

### Linux (AppImage)

1. Download the `.AppImage` package.
2. Open a terminal in the download directory.
3. Grant execution permissions:

   ```bash
   chmod +x OverlayAssistant-2.3.3-x64.AppImage
   ```

4. Launch the application:

   ```bash
   ./OverlayAssistant-2.3.3-x64.AppImage
   ```

---

## API Configuration

Overlay Assistant requires API keys to enable its AI and audio-processing functionality.

### 1. Google Gemini API Key

A Google Gemini API key is required for interacting with Gemini models.

Get your API key from:

[Google AI Studio](https://aistudio.google.com/apikey)

### 2. Deepgram API Key

A Deepgram API key is required for real-time audio listening and transcription.

Get your API key from:

[Deepgram Console](https://console.deepgram.com/)

**Important:** Configure both API keys in the application before using the corresponding features.

---

## Access and Authorization

> **Overlay Assistant is not an unrestricted public application.**

Although the release repository is publicly accessible and anyone can download the installation packages, application access is restricted to users who have been explicitly authorized.

Only users whose accounts have been added to the application's authorization database can use the application.

If you would like to request access, please contact:

**Email:** [anubhabnath04@gmail.com](mailto:anubhabnath04@gmail.com)

When requesting access, please include:

- Your name.
- Your reason for wanting to use Overlay Assistant.
- A brief description of your intended use.

Access requests will be reviewed individually. Downloading and installing the application does not automatically grant access.

---

## Releases and Updates

All application binaries and release versions are published through this repository.

- [View All Releases](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases)
- [View Latest Release](https://github.com/anubhabnath098/Overlay-Assistant-Releases/releases/latest)

The application also includes a built-in updater that notifies users when a newer release becomes available.

Whenever a new version is published, users can update directly through the application using the **Update** button, without having to manually download the installer again.

---

## Important Notes

- An active internet connection is required for API-based functionality.
- Valid Gemini and Deepgram API keys are required for their respective features.
- API usage may be subject to the respective providers' rate limits and pricing.
- Application access is restricted to authorized users.
- The public availability of installation packages does not imply unrestricted permission to use the application.
- macOS builds are not currently provided.

---

<p align="center">
  <strong>Overlay Assistant</strong>
  <br>
  <em>Your meetings. Your context. Your AI assistant.</em>
</p>

<p align="center">
  Developed and maintained by <a href="https://github.com/anubhabnath098">Anubhab Nath</a>
</p>