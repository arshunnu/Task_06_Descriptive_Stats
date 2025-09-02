# Task 06 – Deep Fake Interview

## 📌 Overview
This project builds on the descriptive statistics and LLM analysis from **Task 05**.  
The goal was to transform that narrative into a **deep fake interview** between a reporter and a coach.  

While the initial objective was to create a full video, the main emphasis of this task (per guidance) was on **documenting the workflow, research process, and attempts** rather than producing a perfectly polished final product.

---

## 🎤 Deliverables
- `script.txt` → The full interview script (Q&A format)  
- `interview_audio.mp3` → AI-generated audio of the interview (interviewer + coach voices)  
- `README.md` → Documentation of workflow, tools, challenges, and reflections  

---

## ⚙️ Workflow

1. **Script Creation**  
   - Wrote a short, five-question interview script between an **Interviewer** and the **Coach** based on Syracuse Women’s Lacrosse statistics from Task 05.  

2. **Audio Generation**  
   - Used **ElevenLabs** to generate realistic voices:  
     - *Interviewer*: neutral, professional journalist tone  
     - *Coach*: calm but confident, sports-oriented tone  
   - Generated each line separately, then exported them as MP3 files.  

3. **Exploring Video Options**  
   - **HeyGen**: Looked into Conversation Video, but the feature was not available on the free tier.  
   - **D-ID**: Tested avatar-based video generation, but multiple-speaker support required upgrading.  
   - **Runway Gen-2**: Explored text-to-video prompts for “street interview” and “stadium interview” scenes. Couldn’t directly upload audio for lip-sync under the free tier.  

4. **Final Approach**  
   - Delivered the **audio-only interview**, paired with the script.  
   - Documented all tool attempts and limitations.  
   - Left open the possibility of layering audio over stock footage in future iterations.  

---

## 🚧 Challenges
- Most avatar/video platforms required **paid tiers** for multi-speaker support or audio upload.  
- Runway and Pika Labs are strong for **visual scenes**, but syncing with audio was limited on free plans.  
- Stitching together multiple clips would require additional editing software (CapCut/DaVinci Resolve).  

---

## 💡 Reflection
- **Strengths**: ElevenLabs generated highly natural voices that captured the tone of both interviewer and coach.  
- **Limitations**: Full “street/stadium interview” deep fake video wasn’t possible without premium tools.  
- **Key Takeaway**: The professor’s guidance emphasized that the **process and documentation** matter more than the polished video. This submission reflects the full workflow, including experiments and constraints.  

