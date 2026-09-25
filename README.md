<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=210&section=header&text=Luis%20Felipe%20Guerrero%20V%C3%A9rtiz&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20Generative%20AI%20and%20LLMs%20%C2%B7%20Google%20Cloud&descSize=18&descAlignY=58&animation=fadeIn" alt="Luis Felipe Guerrero Vértiz — AI Engineer" width="100%">
</p>

<p align="center">
  <a href="https://github.com/MSasuR/odoo-ai-assistant">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=4DA3FF&center=true&vCenter=true&width=620&lines=Building+RAG+assistants+with+Gemini+%26+OpenAI;Shipping+production+backends+on+Google+Cloud;10%2B+years+of+backend+engineering;Python+%C2%B7+Java+%C2%B7+Odoo+%C2%B7+Kubernetes" alt="Typing animation">
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/felipeguerrerov/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:lf.guerrero.vertiz@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Lima,_Per%C3%BA-Open_to_remote-2EA44F?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
</p>

---

## 👋 About me

```python
class LuisFelipe:
    role       = "AI Engineer · Cloud Engineer"
    location   = "Lima, Perú 🇵🇪"
    experience = "10+ years building production backends"
    focus      = ["LLMs & RAG", "AI agents with tool calling", "Google Cloud", "Odoo ERP"]
    certified  = ["GCP Professional Cloud Developer", "GCP Associate Cloud Engineer"]
    languages  = {"Spanish": "native", "English": "C1"}
```

## 📈 Impact in numbers

<table align="center">
  <tr>
    <td align="center" width="25%"><h2>450</h2><sub>employees using the<br><b>RAG AI assistant</b> I built</sub></td>
    <td align="center" width="25%"><h2>−90%</h2><sub>HR queries<br>(−55% sales queries)</sub></td>
    <td align="center" width="25%"><h2>1h → 2m</h2><sub>deployment time with<br><b>PR-based CI/CD</b></sub></td>
    <td align="center" width="25%"><h2>−50%</h2><sub><b>GCP costs</b> across<br>multiple projects</sub></td>
  </tr>
</table>

## 🚀 Featured project — [Odoo AI Assistant](https://github.com/MSasuR/odoo-ai-assistant)

<table>
  <tr>
    <td width="58%" valign="top">

A chat assistant embedded in **Odoo 19** that answers questions about **leave, sales and invoices** from live ERP data, and about **company procedures** from a document index — acting strictly as the logged-in user.

- 🧠 **Tool-calling agent**, provider-agnostic (Gemini & OpenAI behind one interface)
- 📚 **RAG on pgvector** with cited sources and a calibrated *"I don't know"*
- 🔐 **Security by design**: HMAC-signed identity, fixed SQL on read-only views, no text-to-SQL
- 🧪 **Measured quality**: retrieval + end-to-end agent evals with ground truth
- ⚙️ **CI** with lint, tests and security checks · non-root container

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Odoo_19-714B67?style=flat-square&logo=odoo&logoColor=white">
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
</p>

<a href="https://github.com/MSasuR/odoo-ai-assistant"><b>→ Explore the repository</b></a>

</td>
    <td width="42%" align="center" valign="top">
      <img src="https://github.com/MSasuR/odoo-ai-assistant/raw/main/docs/img/chat.jpg" alt="AI Assistant chat panel inside Odoo 19" width="300">
    </td>
  </tr>
</table>

<details>
<summary><b>🏗️ Architecture</b> (click to expand)</summary>

```mermaid
flowchart LR
    U([User]) --> B[Browser<br/>OWL chat]
    B -->|Odoo session| O[Odoo 19<br/>signs token]
    O -->|HMAC token| A[Assistant API<br/>FastAPI]
    A <-->|messages + tools| L[(LLM<br/>Gemini / OpenAI)]
    A -->|fixed SELECTs<br/>read-only role| D[(Odoo DB)]
    A -->|cosine search| V[(pgvector<br/>doc chunks)]
```

**The model proposes, the code disposes:** the LLM picks tools and arguments; identity, permissions and SQL are decided by code.

</details>

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,spring,fastapi,postgres,mysql,mongodb,gcp,aws,docker,kubernetes,jenkins,linux,git,githubactions&perline=8" alt="Tech stack icons">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/RAG_·_Vector_DBs-FF6F00?style=flat-square">
  <img src="https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img src="https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white">
  <img src="https://img.shields.io/badge/Apache_Camel-D22128?style=flat-square&logo=apache&logoColor=white">
  <img src="https://img.shields.io/badge/Kong-003459?style=flat-square&logo=kong&logoColor=white">
  <img src="https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white">
</p>

## 💼 Experience

| Period | Role | Company | Highlights |
|:--|:--|:--|:--|
| **2021 – now** | Backend Developer · AI & Cloud | **Apiux Tecnología** 🇨🇱 | RAG AI assistant for 450 employees · CI/CD · −50% GCP costs · 5 GCP projects secured · 10k-tx peak platform for public sector |
| 2020 – 2021 | Programmer Analyst | CONASTEC 🇵🇪 | 30+ Odoo 13 modules for 5+ clients · Docker production deployments |
| 2019 – 2020 | Programmer Analyst | JET PERÚ 🇵🇪 | 10+ Odoo modules: billing, accounting, HR, web services |
| 2016 – 2018 | Development Assistant | IPSOS 🇵🇪 | .NET / PHP apps · SQL Server & MySQL · Power BI reports |

## 🏅 Certifications

<p align="center">
  <img src="https://img.shields.io/badge/Google_Cloud-Professional_Cloud_Developer_·_2023-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP Professional Cloud Developer">
  <img src="https://img.shields.io/badge/Google_Cloud-Associate_Cloud_Engineer_·_2022-34A853?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP Associate Cloud Engineer">
  <br>
  <img src="https://img.shields.io/badge/Scrum_Master-SMPC®_·_2022-6DB33F?style=for-the-badge&logo=scrumalliance&logoColor=white" alt="SMPC">
  <img src="https://img.shields.io/badge/Scrum_Foundation-SFPC®_·_2021-6DB33F?style=for-the-badge&logo=scrumalliance&logoColor=white" alt="SFPC">
</p>

🎓 **B.Sc. Systems Engineering** — Universidad Peruana de Ciencias Aplicadas (UPC)

---

<p align="center">
  <i>Open to conversations about AI engineering, LLM applications and cloud architecture.</i><br><br>
  <a href="https://www.linkedin.com/in/felipeguerrerov/"><img src="https://img.shields.io/badge/Let's_talk_on_LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=110&section=footer" width="100%">
