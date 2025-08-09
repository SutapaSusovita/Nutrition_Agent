# Nutrition_Agent
# 🧠 Nutrition Agent – Smartest AI Nutrition Assistant

In an era of growing health awareness, most diet tools remain **generic**, lacking the ability to adapt in real-time to a person’s **medical conditions, culture, preferences, or lifestyle**. Nutritionists struggle to scale personalized consultations due to time and resource constraints.

**Nutrition Agent** solves this challenge using **IBM Cloud’s Watsonx AI Agent Builder** to deliver an intelligent, interactive, and adaptive virtual nutrition assistant.

---

## 🎯 Problem Statement

> "How can we provide truly personalized, explainable, and scalable nutrition guidance using generative AI?"

### Challenges Solved:
- Generic diet apps don’t account for individual health or cultural needs
- Real-time adaptability is lacking
- In-person consultations are time/resource limited

---
**How to Test the Nutrition AI Agent**
- Open the provided view-only Google Colab link to explore the notebook without cloning the repo.

- To run the code, make a copy of the notebook to your own Google Drive by selecting File > Save a copy in Drive.

- The project ID is already set in the code (46f752f6-63af-49e3-a01c-b579cde1e0e1). When running the script, you will be prompted to enter your IBM Watsonx API key.

- Run the main script and input your nutrition-related query when prompted (e.g., “Create a weekly vegetarian meal plan for a 28-year-old female with PCOS aiming for weight loss.”).

- The agent will generate personalized meal plans and suggestions based on your input.



## 💡 Solution Overview

Nutrition Agent is an AI-powered assistant that:
- ✅ Understands **text, voice, or image** input (e.g., food photos, grocery labels)
- 🥗 Generates **personalized meal plans** based on medical conditions, fitness goals, allergies, etc.
- 🔁 Offers **smart food swaps**
- ℹ️ Explains **"Why is this food better?"**
- 📈 Adapts to **continuous feedback** from the user

---

## 🧠 Technologies Used

| Component            | Technology                      |
|---------------------|----------------------------------|
| AI Agent Platform   | [IBM Watsonx AI Agent Builder](https://www.ibm.com/products/watsonx-assistant) |
| Deployment          | IBM Cloud                        |
| Language Model      | Watsonx Granite LLM (LLM-as-a-service) |
| Input Modalities    | Text (via chat UI) |
| Inference API       | Public & private endpoints for integration |
| Personalization     | Contextual memory & conditional logic |

---

## 🏗️ System Architecture

```plaintext
User Input → Watsonx AI Agent (LLM-powered logic)
          ↘ Fetch health profile / preferences
           ↘ Generate meal plan / swap / explanation
            ↘ Return output (text/image response)
📸 **Working Demo:** Please refer to the uploaded PDF file (`Nutrition agent ppt.pdf`) for screenshots showcasing the functional flow and responses of the deployed model.

