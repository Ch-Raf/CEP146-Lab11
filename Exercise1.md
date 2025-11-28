# Resume Screening AI Bias Analysis

## Worksheet

### Step 1: Basic Statistics
1. Interview Rate (AI Decision):
   - Males scoring 70+: 46 out of 50 = 92%
   - Females scoring 70+: 24 out of 50 = 48%

2. Actual Qualification Rate (Human Expert):
   - Males actually qualified: 38 out of 50 = 76%
   - Females actually qualified: 35 out of 50 = 70%

### Step 2: Bias Analysis
3. AI Accuracy by Group:
   - For males: Qualified candidates did the AI correctly identify: 34
   - For females: Qualified candidates did the AI correctly identify: 9
   - AI Accuracy for males: (34/38)*100 = 89.47%
   - AI Accuracy for females: (9/35)*100 = 25.71%

4. False Negatives (Qualified but Rejected):
   - Males: Qualified men were scored below 70: 4
   - Females: Qualified women were scored below 70: 26

### Step 3: Impact Assessment
5. Real-world Impact:
   - If TechCorp hires 20 people, based on AI recommendations, male would be 13 and female would be 7.

     46 (male) + 20 (female) = 70 total interviewees.

     Male estimation of hiring: 46/70 = 0.657 * 20 = 13

     Female estimation of hiring: 24/70 = 0.343 * 20 = 7
   - This male 13 and female 7 calculation is not proportional to the actual qualification rate since male is 38 and female is 35 which if we calculate, the result will be closer to 10 male (0.521 * 20) and 10 female (0.479 * 20)

### Step 4: Reflection Questions
6.  What evidence of bias do you see in this AI system?
    - AI fails to see talent in qualified women that in total, AI rejected 26 women and 4 men who were actually qualified by the human expert which shows a big difference
    - For qualified men, AI have 89.47% accuracy while for women, AI have 25.71% success rate
7.  How might this bias have developed during programming/training?
    - From my observation, AI is biased against females that mostly hired candidate mostly men which shows that AI learned bad habits from history
8.  What would you recommend to fix this system?
    - Make sure the AI get more training in responding to some resumes anonymously without showing any gender, age, and names
