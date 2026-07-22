# Zero-Shot vs Few-Shot Prompting: Customer Support Classification

**A practical comparison of prompting techniques using frontier AI models.**

## 🎯 Objective
Compare **Zero-Shot** (instruction only) and **Few-Shot** (instruction + 3 labeled examples) prompting for classifying customer support messages into three categories:
- **Complaint**
- **Question**
- **Praise**

The same 10 test messages were evaluated across **ChatGPT, Claude, and Gemini** to analyze the impact of prompt structure on accuracy and consistency.

## 📊 Test Dataset
10 real-world customer support messages with ground-truth labels.

| #  | Message                                              | Ground Truth |
|----|------------------------------------------------------|--------------|
| 1  | My order arrived late and the packaging was damaged... | Complaint   |
| 2  | How do I reset my password?...                       | Question    |
| 3  | The product is exactly as described...               | Praise      |
| 4  | I'm very disappointed with the customer service response time. No one replied for day.   | Complaint      |
| 5  | What are the return options if the item doesn't fit?             |  Question      |
| 6  | Amazing support team! You solved my issue in minutes. Highly recommend.  | Praise   |
| 7  | The battery life is much worse than advertised. I want a refund.                    | Complaint  |
| 8  | Can you tell me when the new version will be available ?             |  Question     |
| 9  | This is the best purchase I've made this year. Everything is top quality!                 | Praise     |
| 10 | Your app keeps crashing on my phone. Fix this immediately.           | Complaint      |


## 📝 Prompts Used
### Zero-Shot Prompt
Instruction-only prompt with no examples.

### Few-Shot Prompt
Same instruction + 3 hand-crafted labeled examples.

## 📈 Results
All three models achieved **perfect accuracy (10/10)** on both prompting methods.

| Tool      | Zero-Shot Accuracy | Few-Shot Accuracy |
|-----------|--------------------|-------------------|
| ChatGPT   | 10/10              | 10/10             |
| Claude    | 10/10              | 10/10             |
| Gemini    | 10/10              | 10/10             |

## 💡 Key Takeaway
On clear, unambiguous messages, **zero-shot prompting** is highly effective with modern frontier models. Few-shot examples did not improve accuracy in this case, but they remain valuable for:
- Ambiguous or mixed-tone messages.
- Smaller or less capable models.
- Ensuring consistent output formatting.

This project highlights when prompt engineering techniques add real value.

## 📁 Project Files
- `Zero-Shot_vs_Few-Shot_Prompting.docx` → Complete report.
- `Zero-Shot_vs_Few-Shot_Prompting.mp4` → Video walkthrough.
- Screenshots & supporting visuals.

## 🚀 Video Walkthrough
[Watch the video](link-to-your-video-on-github-or-linkedIn)

## 🛠️ Technologies & Tools
- Large Language Models: ChatGPT, Claude, Gemini.
- Prompt Engineering (Zero-Shot & Few-Shot).
- Customer Support Classification.

## Author
**Sumaira Safeer**  
Computer Engineer 
[LinkedIn](https://www.linkedin.com/in/sumaira-safeer-948804418/)

---
