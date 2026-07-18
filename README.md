# AI_Quiz_Generator

#  Smart Quiz Generator

Convert raw lecture notes or text content into high-yield interactive flashcards and quizzes instantly delivered to your inbox! Built during the **PyData Indore Hack Days** 🚀.

##  Features
- **Instant Quiz Generation:** Converts messy study materials into structured Multiple Choice Questions (MCQs).
- **Flashcard Creation:** Automatically extracts key terms and definitions into quick-review flashcards.
- **Direct Email Delivery:** No need to stay on the webpage; the complete quiz is sent straight to the user's email inbox within 30 seconds.
- **Serverless & Fast:** Powered by lightweight automation and advanced AI.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, Bootstrap 5 (Responsive UI)
- **Backend Automation:** Make.com (Visual Workflow / Webhooks)
- **Core AI:** Google Gemini API (`gemini-3-5-flash` model)
- **Email Service:** Gmail API Integration

## ⚙️ How It Works (Workflow Architecture)
1. **User Input:** The student enters their email and pastes lecture notes or text on the frontend form.
2. **Data Catching:** A JavaScript `Fetch` call triggers a custom **Make.com Webhook**, securely sending the payload.
3. **AI Processing:** The data is passed to **Google Gemini AI**, which processes the context and formats the MCQs and flashcards.
4. **Instant Notification:** The final structured output is mapped to the **Gmail** module and instantly emailed to the student.

## 🚀 How to Run Locally
1. Clone this repository or download the `index.html` file.
2. Open `index.html` in VS Code.
3. Right-click and select **"Open with Live Server"**.
4. Enter your email, paste some notes, and click **"Generate Quiz Now"**!

---
Developed with ❤️ for the Hackathon.
