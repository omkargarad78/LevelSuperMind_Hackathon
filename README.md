# **LevelSuperMind Hackathon**

## **Social Media Performance Analysis**

### **Overview**  
This project is part of a hackathon assignment aimed at analyzing the performance of social media posts. The goal is to calculate engagement rates, provide insights into the effectiveness of different post types, and generate actionable suggestions using AI-powered tools.

---

### **Key Features**  

- **Post-Type Analysis:**  
  The module compares engagement rates for Reels, Carousels, and Static posts to determine which format performs best.
- **Individual Account Analysis:**  
  Enables users to derive information for a specific individual and analyze their social media account's performance.
- **AI-Driven Insights:**  
  Leverages the **Gemini AI API** (Google Generative AI) to generate insights for improving social media strategies.

---

### **Tech Stack**  
- **Database:** [DataStax Astra DB](https://www.datastax.com/) for storing and querying engagement data.
- **AI API:** Gemini AI API for generating advanced insights.
- **Workflow Automation:** [Langflow](https://github.com/logspace-ai/langflow) for streamlined analytics and integration.

---

### **Project Workflow**  
1. **Data Ingestion:** Engagement data is stored in Astra DB.  
2. **Metric Calculation:** The engagement rate and other metrics are computed for each post type.  
3. **Insight Generation:** The Gemini AI API analyzes the data and generates actionable recommendations.
