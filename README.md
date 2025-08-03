# 🌾 FarmSetu.ai – Smart Farming AI Assistant

**FarmSetu.ai** is an AI-powered smart farming assistant built using **IBM Granite** and **Retrieval-Augmented Generation (RAG)**.  
It offers real-time, localized guidance to small-scale farmers in simple language, improving productivity, reducing risk, and connecting them with government resources.

---
<p align="center">
  <img width="748" height="748" alt="Gemini_Generated_Image_g9ecnrg9ecnrg9ec" src="https://github.com/user-attachments/assets/8b44bb1a-8b37-47b5-b3de-45a56fc688d1" />
</p>

## ✨ Features

### 1. 🌱 Crop Recommendations
- **Ask:** “Which crop is best to grow this season in my area?”
- Provides suitable crop suggestions based on:
  - Location
  - Soil type
  - Current season
  - Crop rotation patterns

### 2. 🌦️ Weather Forecasts
- **Ask:** “Will it rain in the next 3 days?” or “Is it good to spray pesticides today?”
- Gives reliable weather updates:
  - Rain probability
  - Temperature
  - Wind speed
  - Humidity
  - Weather alerts (hailstorm, thunderstorm)

### 3. 🧪 Soil Health & Fertility
- **Ask:** “Is my soil good for groundnut?” or “Where can I get soil testing?”
- Supports the **Soil Health Card Scheme**
  - Guides farmers to nearest **KVK**
  - Explains pH, nutrient levels, and testing intervals

### 4. 🐛 Pest & Disease Control
- **Ask:** “How to treat whiteflies in cotton?”
- Provides:
  - Natural remedies (like neem spray)
  - Approved pesticide usage
  - ICAR guidelines
  - Safety precautions

### 5. 📈 Mandi Prices & Market Trends
- **Ask:** “What is today’s price for tomatoes in Bhubaneswar?”
- Displays market rates from:
  - **eNAM**
  - **Agmarknet**
  - APMCs (Agricultural Produce Market Committees)

> ⚠️ *Live mandi prices are fetched via official APIs (eNAM/Agmarknet). Note: API usage is limited to 10 requests per day, so prices may not always be available on demand.*

### 6. 🏛️ Government Schemes & Support
- **Ask:** “How can I apply for PM-KISAN?” or “Any subsidy for drip irrigation?”
- Covers:
  - PM-KISAN (₹6000 income support)
  - PMFBY (crop insurance)
  - KCC (low-interest farm loans)
  - Irrigation & organic farming schemes
  - Required documents, deadlines, and how to apply

---

## 🗣️ How to Use FarmSetu

You can:
- Ask questions in **your local language**
- Use **simple sentences** (e.g., “Barish kab hogi?”)
- Access it **anytime, anywhere**

### 💬 Example Questions
- “Which crop is best to grow in August in Bihar?”
- “What is today’s mandi price of onions in Delhi?”
- “Is rainfall expected tomorrow?”
- “How to treat pests in chilli?”
- “What are the benefits of PM-KISAN Yojana?”

---

## 🧠 Technology Stack

- **IBM Granite LLM**
- **RAG (Retrieval-Augmented Generation)**
- IBM Cloud Lite Services
- Real-time API integration for live mandi prices & weather(Agmarknet / eNAM APIs)
- Local language support via translation layer

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio
- IBM Granite Model
- Watsonx Vector Index
- IBM Cloud Lite Account
- IBM Cloud IAM
- IBM Cloud Object Storage

---

## 🖼️ Screenshots

### 🔹 Setting up..

---

<p align="center">
<img width="535" height="239" alt="Screenshot 2025-08-03 014447" src="https://github.com/user-attachments/assets/f3a9febc-e96f-410c-b873-12532d67de5e" />
</p>

---

### 🔹 Agent Instructions...

---

<table>
  <tr>
    <td>
      <img width="550" height="350" alt="Screenshot 1" src="https://github.com/user-attachments/assets/e285671e-5c33-449a-9d62-d36ddfed801a" />
    </td>
    <td>
      <img width="530" height="320" alt="Screenshot 2" src="https://github.com/user-attachments/assets/8cead4fb-dfb3-485a-81da-8a4d64b80993" />
    </td>
  </tr>
  <tr>
    <td>
      <img width="550" height="320" alt="Screenshot 3" src="https://github.com/user-attachments/assets/3a2c040c-71a0-402a-baa6-b878f6c7e22d" />
    </td>
    <td>
      <img width="530" height="320" alt="Screenshot 4" src="https://github.com/user-attachments/assets/e2e0aa7c-e0ff-432a-b1d2-bbab7bef61a3" />
    </td>
  </tr>
</table>

---

### 🔹 Tools used & Testing...

---

<p align="center">
<img width="568" height="579" alt="Screenshot 2025-08-03 014429" src="https://github.com/user-attachments/assets/73d18ccb-074d-4092-aead-2b9f1a028ed8" />
</p>

---

### 🔹 Deployment...

---
<img width="1499" height="465" alt="Screenshot 2025-08-03 022156" src="https://github.com/user-attachments/assets/ca5b0e94-635d-49ce-aa1b-6bdf2e532dcb" />

---

### 🔹 Preview...

---

<p align="center">
<img width="501" height="208" alt="Screenshot 2025-08-03 014616" src="https://github.com/user-attachments/assets/95d2adfa-9c23-478b-85c0-f12338d1e500" />
</p>
<table>
  <tr>
    <td>
      <img width="430" height="360" alt="Screenshot 1" src="https://github.com/user-attachments/assets/fd14f8dd-2d9d-4361-8824-060e84c6f15e" />
    </td>
    <td>
      <img width="430" height="360" alt="Screenshot 2" src="https://github.com/user-attachments/assets/59984453-42f9-40f2-a3a8-291fce7896bc" />
    </td>
  </tr>
  <tr>
    <td>
      <img width="430" height="360" alt="Screenshot 3" src="https://github.com/user-attachments/assets/e154b302-8d5f-482f-b46a-b8ceac0c35a1" />
    </td>
    <td>
      <img width="430" height="360" alt="Screenshot 4" src="https://github.com/user-attachments/assets/059c6825-c950-4529-80d2-f5f0b8b1ae8e" />
    </td>
  </tr>
</table>

---

### 🔹 API References after Deployment...

---

<img width="1907" height="901" alt="image" src="https://github.com/user-attachments/assets/f292c015-f837-4c07-9d9f-3f180ca64b57" />

---

### 🔹 Resources List...

---

<img width="1915" height="875" alt="image" src="https://github.com/user-attachments/assets/14de578e-d540-4e2d-930b-49e7dfd7871a" />

---
 
## 📌 How to Run or Deploy

- Log in to IBM Cloud Lite: https://cloud.ibm.com
- Launch Watsonx.ai Studio
- Create a new AI Agent
- Upload financial PDFs to a Vector Index
- Choose Tools for web search (Google,Wikipedia,DuckDuckGo etc..)
- Configure agent instructions and topics (restricting AI from answering off-topic questions politely)
- Test in the preview panel
- Deploy via web snippet, Streamlit, or custom web UI

---

## 🛠️ Future Scope

- [ ] Voice input/output (for non-literate users)
- [ ] SMS/WhatsApp chatbot version
- [ ] Multilingual support expansion

---

## 🔗 Useful Links

- [IBM Cloud Lite](https://www.ibm.com/cloud/free)
- [IBM Watsonx.ai](https://www.ibm.com/watsonx)
- [RBI Official Website](https://www.rbi.org.in)
- [NPCI FAQs](https://www.npci.org.in/what-we-do/faqs)
- [IBM SkillsBuild](https://skillsbuild.org/)

---

## ⚖️ License

- This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

Created with 💙 during the IBM SkillsBuild for Academia Internship 2025 by Sweety Kumari.
