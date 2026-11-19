

\# 🚀 NeuralPost | AI News Studio



An AI-powered LinkedIn content automation platform that transforms the latest AI news into professional LinkedIn posts using n8n and Groq AI.



NeuralPost simplifies content creation by automatically collecting AI news, processing articles, generating engaging captions, and supporting LinkedIn publishing through automated workflows.





\- 📰 \*\*AI News Collection\*\* – Fetch the latest AI-related news.

\- 🤖 \*\*AI Content Generation\*\* – Generate LinkedIn captions using Groq AI.

\- 🔍 \*\*Article Processing\*\* – Extract and analyze article content automatically.

\- ✍️ \*\*Smart Caption Writing\*\* – Create engaging LinkedIn posts with hooks and hashtags.

\- 🔄 \*\*n8n Automation\*\* – Connect different services through automated workflows.

\- ✅ \*\*Content Approval\*\* – Review generated content before publishing.

\- 🔗 \*\*LinkedIn Integration\*\* – Support automated LinkedIn publishing.

\- 🎨 \*\*Modern Dashboard\*\* – Clean and user-friendly interface.



\## 🛠️ Technologies Used



| Technology | Purpose |

|---|---|

| HTML5 | Website structure |

| CSS3 | Dashboard styling |

| JavaScript | Frontend functionality |

| n8n | Workflow automation |

| Groq AI | AI-powered content generation |

| Gmail | News selection and notifications |

| LinkedIn API | LinkedIn publishing |

| TechCrunch | AI news source |



\## ⚙️ How It Works



1\. The system collects the latest AI news.

2\. News options are sent through Gmail.

3\. The user selects a preferred news article.

4\. n8n fetches the complete article content.

5\. Groq AI processes the article and generates a LinkedIn caption.

6\. The generated content is reviewed.

7\. Approved content can be published to LinkedIn.



\## 🏗️ Project Architecture



```text

&#x20;                NeuralPost Dashboard

&#x20;                         |

&#x20;                         v

&#x20;                   n8n Webhooks

&#x20;                         |

&#x20;                         v

&#x20;                  Fetch AI News

&#x20;                         |

&#x20;                         v

&#x20;                 Select News Article

&#x20;                         |

&#x20;                         v

&#x20;                 Extract Article Text

&#x20;                         |

&#x20;                         v

&#x20;                    Groq AI

&#x20;                         |

&#x20;                         v

&#x20;               Generate LinkedIn Caption

&#x20;                         |

&#x20;                         v

&#x20;                   Content Approval

&#x20;                         |

&#x20;                         v

&#x20;                 LinkedIn Publishing

```



\## 🚀 Setup Instructions



\### 1. Clone the Repository



```bash

git clone YOUR\_GITHUB\_REPOSITORY\_URL

```



\### 2. Open the Project



```bash

cd NeuralPost

```



\### 3. Configure Webhooks



Update the API configuration in your JavaScript file with your n8n webhook URLs.



```javascript

const API = {

&#x20; getNews: "YOUR\_GET\_NEWS\_WEBHOOK",

&#x20; processArticle: "YOUR\_PROCESS\_ARTICLE\_WEBHOOK",

&#x20; approveNews: "YOUR\_APPROVAL\_WEBHOOK",

&#x20; publishPost: "YOUR\_PUBLISH\_WEBHOOK"

};

```



Replace the placeholder URLs with your actual active n8n webhook URLs.



\### 4. Configure n8n



\- Import or create your n8n workflows.

\- Configure the required credentials.

\- Connect the news collection workflow.

\- Configure the Groq AI integration.

\- Set up LinkedIn authentication.

\- Activate your workflows.



\### 5. Run the Dashboard



Open `index.html` in your browser or deploy the frontend using a static hosting service.



\## 🔐 Environment \& Security



\- Never expose API keys in frontend JavaScript.

\- Store sensitive credentials securely in n8n.

\- Use HTTPS for production webhooks.

\- Configure authentication for sensitive webhook endpoints.

\- Never commit private credentials to GitHub.



\## 📸 Screenshots



Add your project screenshots here.



```text

screenshots/

├── dashboard.png

├── news-selection.png

├── generated-caption.png

└── approval-page.png

```



Example:



```markdown

!\[NeuralPost Dashboard](screenshots/dashboard.png)

```



\## 🔮 Future Improvements



\- Support multiple news sources.

\- Add AI-powered image generation.

\- Add LinkedIn post scheduling.

\- Add analytics and performance tracking.

\- Support multiple social media platforms.

\- Add multilingual AI content generation.



\## 👨‍💻 Developer



\*\*Mohammed Nabhan P N\*\*



AI/ML Developer | Data Analyst



\- GitHub: https://github.com/mohdnabhan789-ship-it

\- LinkedIn: https://www.linkedin.com/in/mohammednabhanpn/



\---



⭐ If you find this project interesting, consider giving it a star!



