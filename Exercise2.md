# AI Decision Transparency Testing

## Round 1: Black Box AI System

### Scenario: College Scholarship AI System

Rafael (AI):
```
The AI system has determined you do not qualify for this scholarship.
```

Max (User):
```
Dear Scholarship Committee,
Could you please share any insight into why my application was denied?


Are there specific areas I can strengthen to improve my chances in future scholarship cycles?


I want to ensure that my materials were evaluated appropriately—was my application reviewed fairly according to your standard process?


Is there an appeals process available for this decision?


Lastly, could you outline the primary criteria used during the selection process?
Warm regards,
Sarah Miller
```

Rafael (AI): 
```
The AI system has determined you do not qualify for this scholarship.
```

## Round 2: Transparent AI System

Rafael (AI): 

```
DECISION: Sarah Miller - SCHOLARSHIP DENIED
REASONING: The AI system uses these factors (in order of importance):
1. GPA (40% weight) - Sarah scored 76/100 (3.8/4.0 GPA)
2. Standardized Test Scores (30% weight) - Sarah scored 45/100 (missing SAT scores)
3. Volunteer Work (20% weight) - Sarah scored 85/100 (2 years volunteering)
4. Leadership Experience (10% weight) - Sarah scored 20/100 (no leadership roles listed)
OVERALL SCORE: 61/100 (Scholarship threshold: 75/100)
```

Max (User): 

```
- How the answers differ; Whether you understand the decision better
I now understand the weighted rubric and how each category contributed to my score.
- If you feel the process was fairer
The decision is clearer and the process feel fairer
- What specific actions you could take
Submit SAT/ACT scores, gain leadership experience, continue academics and volunteer work.
```

## Round 3: Role Switch with New Scenario

### Scenario: Medical AI Diagnosis Assistant

Max (AI)

```
DECISION: Patient shows 78% probability of having Type 2 Diabetes
REASONING: Based on analysis of:
- Blood glucose levels (elevated - 185 mg/dL, normal <140)
- BMI (32.5 - obese category)
- Age (45 - moderate risk factor)
- Family history (diabetes in both parents - high risk)
- Physical activity (reported as "sedentary" - risk factor)
- Symptoms reported (excessive thirst, frequent urination - classic signs)

RECOMMENDATION: Consult with doctor for confirmatory tests and treatment options.
NOTE: This is a diagnostic aid, not a final diagnosis.
```

Rafael (User)

```
I know the app gave me a 78% probability of Type 2 diabetes, but how reliable is that?
What were the exact things in my data that made the app say my risk is high?
Should I see a doctor immediately?
Is it possible the app misinterpreted something?
If I improve my lifestyle, could my risk improve even if the diagnosis ends up being incorrect?
```


## Reflection Worksheet Rafael
1. Emotional Impact: Round 2 felt more fair to me since it gives detailed information as the reason why the scholarship is denied and also responded to some additional information while in round 1 the AI only gives uncertain answers
2. Understanding: Scholarship scenario felt more understandable by a general audience/person. The factors in the rejection of scholarship are the most helpful ones.
3. Trust: I would put more trust in scholarship AI because medical AI seems not giving me information that I can reflect on by myself. Also, the scholarship AI gives a good answer that built up my confidence
4. Actionability: Scholarship, the factors are something that I can improve by myself right away without requiring another person (doctor for example) to help me. The AI also gave me a recommendations such as things to do in order to be a stronger applicant in the future
5. Programming Implications:
   - From my opinion, everything should have a clear reason therefore explainable AI is needed.
   - AI transparency in medical fields would be a challenge for programmers since we all know that there are a lot of laws relating to medical privacy.
   - For the scholarship case, lack of transparency could not help me enough to improve myself and boost my probability of getting a scholarship in the future.

## Group Discussion Question:
1. Yes, as long as cost permits. For high stakes systems, such as employment and medical, absolutely!
2. Privacy risk, and it becomes a security risk when there is a data breach. We do not need AI collecting and storing data for companies to sell, such as medical data sold to insurance companies. 
3. Detail should follow the purpose and audience. High stakes must be specific and actionable, the rest should be summary and offer customer support.
