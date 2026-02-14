# NyaySetu AI - Requirements Document

## 1. Problem Statement

Millions of Indian citizens struggle to understand and access government schemes due to complex language, lack of awareness, and eligibility confusion. Static portals do not provide personalized recommendations.

## 2. Objective

To build a multilingual AI-powered assistant that:
- Understands user queries semantically
- Recommends relevant government schemes
- Checks eligibility dynamically
- Provides document requirements
- Supports regional languages

## 3. Functional Requirements

### 3.1 User Interaction
- User can select preferred language
- User can enter query (text/voice)
- User can enter profile details (income, age, etc.)

### 3.2 AI Scheme Matching
- System shall perform TF-IDF vectorization
- System shall compute cosine similarity between user input and scheme database
- System shall rank schemes based on similarity score

### 3.3 Eligibility Checking
- System shall validate eligibility using rule-based and profile matching logic

### 3.4 Multilingual Support
- System shall integrate with translation API
- System shall support regional language input/output

## 4. Non-Functional Requirements

- System should be scalable (microservice architecture)
- System should ensure no personal data stored without consent
- System should respond within 2 seconds for query matching

## 5. Target Users

- Rural citizens
- Farmers
- Women beneficiaries
- Students
- Low digital literacy users
