# Zero-Shot vs Few-Shot Prompting: Customer Support Classification

**A practical comparison of prompting techniques using frontier AI models.**

## Objective
This project compares **Zero-Shot** (instruction only) and **Few-Shot** (instruction plus three labeled examples) prompting for classifying customer support messages into three categories:
- **Complaint**
- **Question**
- **Praise**

The same 10 test messages were evaluated across **ChatGPT, Claude, and Gemini** to analyze the impact of prompt structure on classification accuracy and consistency.

## Test Dataset
The evaluation used 10 real-world customer support messages, each paired with a ground-truth label.

| # | Message | Ground Truth |
|---|---------|---------------|
| 1 | My order arrived late and the packaging was damaged... | Complaint |
| 2 | How do I reset my password?... | Question |
| 3 | The product is exactly as described... | Praise |
| 4 | I'm very disappointed with the customer service response time. No one replied for days. | Complaint |
| 5 | What are the return options if the item doesn't fit? | Question |
| 6 | Amazing support team! You solved my issue in minutes. Highly recommend. | Praise |
| 7 | The battery life is much worse than advertised. I want a refund. | Complaint |
| 8 | Can you tell me when the new version will be available? | Question |
| 9 | This is the best purchase I've made this year. Everything is top quality! | Praise |
| 10 | Your app keeps crashing on my phone. Fix this immediately. | Complaint |

## Prompts Used
### Zero-Shot Prompt
An instruction-only prompt with no examples provided to the model.

### Few-Shot Prompt
The same base instruction, extended with three hand-crafted labeled examples to guide the model's response.

## Results
All three models achieved **perfect accuracy (10/10)** under both prompting methods.

| Tool | Zero-Shot Accuracy | Few-Shot Accuracy |
|------|---------------------|---------------------|
| ChatGPT | 10/10 | 10/10 |
| Claude | 10/10 | 10/10 |
| Gemini | 10/10 | 10/10 |

## Key Takeaway
On clear, unambiguous messages, **zero-shot prompting** proves highly effective with modern frontier models. Few-shot examples did not improve accuracy in this case, but they remain valuable for:
- Ambiguous or mixed-tone messages.
- Smaller or less capable models.
- Ensuring consistent output formatting.

This project highlights the conditions under which prompt engineering techniques add real, measurable value.

## Project Files
- `Zero-Shot-vs-Few-Shot-Prompting.docx` Complete report
- `Zero-Shot-vs-Few-Shot-Prompting.mp4` Video walkthrough
- Screenshots and supporting visuals

## Video Walkthrough
[Watch the video](link-to-your-video-on-github-or-linkedin)

## Technologies and Tools
- Large Language Models: ChatGPT, Claude, Gemini.
- Prompt Engineering (Zero-Shot and Few-Shot techniques).
- Customer Support Message Classification.

---

## Author

**Sumaira Safeer**
Computer Engineer

LinkedIn: [linkedin.com/in/sumaira-safeer-948804418](https://www.linkedin.com/in/sumaira-safeer-948804418/)
GitHub: [github.com/SumairaSafeer](https://github.com/SumairaSafeer)
