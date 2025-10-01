# Hackathon Submission Guidelines

Welcome to the **913.ai Hackathon 2025**!  
Please follow these instructions carefully so that your work can be judged smoothly.

---

## 📦 What to Submit
Each team must submit:
1. **Your code** (agent + tools + any helper scripts).
2. **Sample input files** and **output files** (showing your agent in action).
3. A short **RUN.md** explaining:
   - How to install dependencies.
   - How to run your agent locally.
   - How to reproduce your example task(s).
4. Any **additional artifacts** required by your track:
   - Track A → Edited file + change log.  
   - Track B → Coverage report + executive brief with citations.  
   - Track C → Redlined contract outputs + version history export.  

---

## ⏰ Deadline
- All submissions must be **finalized by 18:00 (6:00 PM)** on hackathon day.  
- Late submissions will not be considered.

---

## 🛠 How to Submit
1. **Create your repo**:  
   - Go to the public template for your track (A, B, or C).  
   - Click **“Use this template”** → **Create a new repo** under your own GitHub account or org.  
   - Set the repo visibility to **Private**.  

2. **Add organizer as collaborator**:  
   - Go to your repo → Settings → Collaborators → Add  
   - Add GitHub user **`mav913ai`** as a collaborator with write access.  
   - This is required so that we can review your submission.  

3. **Develop in your private repo** during the hackathon.  

4. **At submission time (before 18:00):**  
   - Commit and push your latest code.  
   - Tag your final commit as:
     ```bash
     git tag final
     git push origin final
     ```
   - Open a Pull Request in your repo titled **"Final Submission"**.
   - Your PR should include:
     - A link to your `RUN.md`.  
     - A link to your sample input/output files.  

---

## ✅ Submission Checklist
- [ ] Repo created from template and set to **Private**.  
- [ ] **`mav913ai`** added as collaborator.  
- [ ] Code pushed to repo.  
- [ ] `final` tag created and pushed.  
- [ ] Pull Request titled **"Final Submission"** opened.  
- [ ] `RUN.md` with setup & run instructions included.  
- [ ] Example input/output files included.  

---

## 📋 Judging
Submissions will be judged based on:
- Correctness and accuracy.  
- Layout fidelity (for Track A).  
- Evidence-grounding and coverage (for Track B).  
- Traceability and versioning (for Track C).  
- Creativity, robustness, and stretch goals.  

---

## ⚖️ IP & License
- All code created during the hackathon remains the property of the participants.  
- By participating, you grant **913.ai** a perpetual, worldwide, royalty-free license to use, adapt, and commercialize your submissions in any way.  
- You retain the right to use and showcase your work (e.g., in your portfolio, GitHub profile, LinkedIn, or future projects).  

---

Good luck, and happy hacking 🚀
