<div align="center">

[![Built with n8n](https://img.shields.io/badge/Built%20with-n8n-1abc9c?logo=n8n&logoColor=white)](https://n8n.io/) &nbsp;
[![Replicate](https://img.shields.io/badge/API-Replicate-blue?logo=databricks&logoColor=white)](https://replicate.com/) &nbsp;
[![ElevenLabs](https://img.shields.io/badge/Voice-ElevenLabs-orange)](https://elevenlabs.io/) &nbsp;
[![RunwayML](https://img.shields.io/badge/Video-RunwayML-purple)](https://runwayml.com/) &nbsp;
[![Dropbox](https://img.shields.io/badge/Storage-Dropbox-0061FF?logo=dropbox&logoColor=white)](https://dropbox.com/) &nbsp;
[![Creatomate](https://img.shields.io/badge/Render-Creatomate-red)](https://creatomate.com/) &nbsp;
[![Slack](https://img.shields.io/badge/Control-Slack-4A154B?logo=slack&logoColor=white)](https://slack.com/) &nbsp;
[![Website](https://img.shields.io/badge/Visit-tuguidragos.com-0A66C2?logo=google-chrome&logoColor=white)](https://tuguidragos.com) &nbsp;
[![Buy Me a Coffee](https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black)](https://www.buymeacoffee.com/tuguidragos)

</div>

# n8n Automated Storytelling 🎬🐺

Automated storytelling workflow built with **n8n** that generates stories with AI, creates images, voices, and music, then renders them into a cinematic video.  
It integrates multiple APIs into one seamless pipeline - from text to final video - fully automated.  

---

## 🚀 Features

- Generate stories with **AI LLMs** (Narrative + Voice + Visual + Score).
- Create images for each scene automatically.
- Generate realistic voiceovers with **ElevenLabs**.
- Compose background music with **AI music APIs**.
- Upload & sync all assets via **Dropbox**.
- Render final video with **Creatomate**.
- Slack bot `/render` integration – trigger the workflow directly from Slack by sending a story prompt.  

---

## 📸 Workflow in Action

### Full Workflow in n8n
![Workflow](https://raw.githubusercontent.com/TuguiDragos/n8n-automated-storytelling/refs/heads/main/Workflow.png)

### Slack Bot Integration
Using `/render` command in Slack to send a story prompt.  
![Slack](https://raw.githubusercontent.com/TuguiDragos/n8n-automated-storytelling/refs/heads/main/SLACK.png)

### Video Rendering in Creatomate
![Creatomate Render](https://raw.githubusercontent.com/TuguiDragos/n8n-automated-storytelling/refs/heads/main/creatomate-vd.png)

### Creatomate Video Template
This template defines where **voiceover, music, and video clips** will be placed in the final render.  
![Creatomate Template](https://raw.githubusercontent.com/TuguiDragos/n8n-automated-storytelling/refs/heads/main/template.png)

---

## ⚙️ APIs & Services Used

This workflow combines multiple APIs:

- [Replicate](https://replicate.com) – AI image & music generation  
- [ElevenLabs](https://elevenlabs.io) – Text-to-speech voiceovers  
- [Runway](https://runwayml.com) – Image-to-video (scenes)  
- [Dropbox](https://dropbox.com) – File upload & link management  
- [Creatomate](https://creatomate.com) – Video rendering automation  
- [Slack](https://slack.com) – Bot command `/render`  

---

## 🛠️ How It Works

1. **Slack Command**: Send `/render` + your story → workflow starts.  
2. **Story Generation**: LLM creates a story, split into scenes.  
3. **Assets Creation**:  
   - Visuals generated per scene (AI images/videos).  
   - Voiceover created via ElevenLabs.  
   - Music composed with AI.  
4. **Dropbox Upload**: Assets are stored & shared via Dropbox.  
5. **Creatomate Render**: All assets are merged into a final cinematic video.  
6. **Slack Delivery**: Video link sent back to Slack automatically.  

---

## 💰 Costs

- **Testing**: Free tier was enough for setup & demo.  
- **Production**: For long cinematic videos and wow-quality renders, **paid API plans are required** – but they are absolutely worth it.  

---

## 🎯 Use Cases

- Storytelling & content creation  
- Marketing & social media videos  
- AI-generated movie trailers  
- Fast prototyping for creative projects  
- Automating video production pipelines  

---

## 🌍 Links

- Website: [tuguidragos.com](https://tuguidragos.com)  
- Support my work: [☕ Buy Me a Coffee](https://www.buymeacoffee.com/tuguidragos)  

---

### 🖤 Made with love by Țugui Dragoș
