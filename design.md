# NyaySetu AI - Design Document

## 1. System Architecture

The system follows a microservice-based architecture:

Frontend (Next.js)
↓
Backend API Layer (Node.js)
↓
AI Microservice (Python FastAPI)
↓
ML Matching Engine (TF-IDF + Cosine Similarity)
↓
Translation API Layer (BHASHINI)

## 2. AI Matching Design

Step 1: User query is preprocessed  
Step 2: TF-IDF vectorization applied  
Step 3: Cosine similarity calculated  
Step 4: Schemes ranked based on similarity score  
Step 5: Top results returned  

## 3. Data Flow

User → API → AI Engine → Scheme Database → Response → Translation → User

## 4. Responsible AI Considerations

- Transparent eligibility logic
- No data stored without consent
- Avoid biased filtering
- Inclusive language support

## 5. Future Scalability

- Replace TF-IDF with embedding-based model
- Integrate real-time government APIs
- Deploy on AWS cloud infrastructure

## Design Workflow

This design document was refined and validated within Kiro workspace.
