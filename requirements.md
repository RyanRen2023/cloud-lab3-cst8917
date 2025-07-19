# CST8917 Lab 3: Implementing a Teams Chat Content Moderation Service

## Objective

In this lab, you will develop an **Microsoft Teams chat content moderation service** using **Azure Logic Apps**. The service will monitor Teams chat messages for inappropriate content and automatically trigger **email notifications** when a policy violation is detected. Optionally, you can enhance the workflow using **Azure Functions** and **Azure Cognitive Services for Language**.

By completing this lab, you will demonstrate your ability to orchestrate automated workflows using Azure services and apply content analysis to real-time communication data.

---

## About the Technologies

### Azure Logic Apps

Azure Logic Apps is a cloud-based service that allows you to automate workflows and integrate services without writing much code. It is ideal for building real-time systems triggered by services like Microsoft Teams, email, or HTTP endpoints.

### Azure Cognitive Services (Optional)

Azure Cognitive Services for Language can analyze chat messages and identify inappropriate content using AI-powered natural language processing.

### Azure Functions (Optional)

Azure Functions can be used to customize or preprocess messages before they are evaluated by other services.

---

## Tasks

### 1. Design the Moderation Workflow

- Create a **flowchart** that outlines how your moderation system works.
- Include components like Microsoft Teams trigger, Logic App flow, optional Azure Functions, optional Cognitive Services, and email notifications.

### 2. Build the Moderation Service

- Use **Azure Logic Apps** to set up a trigger that listens for new chat messages from **Microsoft Teams**.
- Optionally integrate:
  - **Azure Functions** to process or filter messages.
  - **Azure Cognitive Services** to analyze message content for violations.
- Ensure that your service reacts in **real time**.

### 3. Implement the Email Notification Logic

- Configure the Logic App to **send an email** to a specified administrator when inappropriate content is detected.
- Follow the format provided in the official alert template (if available).

### 4. Test the Workflow

- Simulate messages in Microsoft Teams and ensure:
  - Violations are detected correctly.
  - Email notifications are triggered.
  - Optional services (Functions, Cognitive Services) are working correctly.

### 5. Document Your Project

Include the following in your documentation:
- A screenshot or export of your workflow flowchart.
- Description of your Logic App setup.
- Optional: details about Azure Functions or Cognitive Services used.
- Explanation of how you tested the workflow.
- Challenges you encountered and how you resolved them.
- Recommendations for future improvement.

### 6. Record a Demo

- Create a short video (3–5 minutes) demonstrating:
  - Your Logic App in action.
  - Explanation of your setup.
  - Any lessons learned.

---

## Deliverables

- Your completed Logic App workflow.
- A screenshot or exported image of your **moderation flowchart**.
- Your written **report** (as a separate file or included in `README.md`).
- A demo video uploaded to YouTube, linked in the `README.md`.

---

## Submission Instructions

Submit the following via Brightspace:

- Link to your **public GitHub repository** containing:
  - Logic App definitions
  - Optional Function or Cognitive Service code
  - `README.md` with documentation
  - Your demo video link (if available)
- Your GitHub repo must be **well-structured and publicly accessible**.

**Deadline**: *Sunday, 20 July 2025*


