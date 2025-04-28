# 📚 Moodle AI Learning Assistant – Admin's User Manual

## Introduction

Welcome, Administrator!  
The **Moodle AI Learning Assistant** helps automate learning support for users by integrating AI-driven chat, intelligent search, quiz generation, and interactive video transcription.

As an Admin, you are responsible for maintaining, updating, and monitoring the AI’s content and performance.  
This manual will guide you through all the administrative tasks.

---

## Key Admin Responsibilities

- Upload new course materials and videos.
- Monitor learner interactions and chatbot analytics.
- Manage AI retraining when new content is added.
- Configure AI settings and behavior.

---

## How to Manage the Moodle AI Assistant

### Step 1: Upload New Training Documents/Videos
- **Login to Moodle** with your Admin account.
- Navigate to **Site Administration > Courses > Manage Courses**.
- Open a course and:
  - Click **"Add an Activity or Resource"**.
  - Choose to upload:
    - PDFs (for course notes)
    - MP4s (for videos)
    - Word Documents
    - Excel sheets or presentations (PPTX)
- After upload, content will automatically be indexed for AI search.

**Tip:** Use clear, descriptive titles for easier search.

---

### Step 2: Monitor User Interactions
- Go to **Admin Panel > AI Analytics**.
- View:
  - Number of user queries.
  - Most searched topics.
  - Quiz completion statistics.
  - User engagement trends.

Use these insights to improve course materials and identify common knowledge gaps.

---

### Step 3: Manage AI Retraining
Whenever major updates happen (new products, courses, policies):
- Visit **Admin Panel > AI Management**.
- Click **Retrain Assistant**.
- The system will:
  - Update the knowledge base.
  - Reindex new documents and videos.
  
**Best Practice:** Schedule retraining quarterly or after major curriculum updates.

---

### Step 4: Configure System Behavior
- Go to **Admin Panel > AI Settings**.
- You can configure:
  - Maximum response length.
  - Course context strictness (how closely AI ties answers to course content).
  - Allowed file formats.
  - Language and tone settings.
  - API keys (for OpenAI, Pinecone, AWS services).

---

## Common Issues and Solutions

| Issue | Solution |
|:-----|:---------|
| Uploaded document not appearing in search. | Trigger manual ingestion through Admin Panel. |
| Slow chatbot responses. | Check Pinecone status and database connections. |
| Video transcript not available. | Ensure the video file is properly formatted and retrigger transcription. |
| Broken links to documents or videos. | Update resource links in Moodle’s Course Settings. |

---

## FAQs

**Q: What formats can I upload?**  
A: PDF, DOCX, PPTX, MP4, MP3, and TXT files are supported.

**Q: How can I view individual user activity?**  
A: Open **AI Analytics > User Sessions** to review per-user chat histories.

**Q: Do I need to manually link every new document to the chatbot?**  
A: No, once uploaded and ingested, the assistant will automatically access new materials.

**Q: How often should retraining happen?**  
A: Ideally, retrain every 3 months or after significant curriculum updates.

---

## Need More Help?
Please contact the Moodle Support Team:  
📧 Email: ict@dayliff.com  
📞 Phone: +254702233145

---
