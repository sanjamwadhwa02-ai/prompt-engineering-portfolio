# Prompt Engineering Portfolio

Name: Sanjam Wadhwa
Date: 06 June 2026
LLM Used: ChatGPT (GPT-5.5)

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation

**Goal:** Explain recursion to a 10-year-old child.

#### Initial Prompt (V1)
Explain recursion.

#### Refined Prompt (V2)
Explain recursion in simple language that a middle school student can understand. Include an example.

#### Final Prompt (V3)
You are an expert teacher explaining concepts to children. Explain recursion to a 10-year-old using a fun real-life example. Avoid technical terms and keep the explanation under 150 words.

#### Final LLM Output

Recursion is when something repeats the same action again and again until it reaches a stopping point. Imagine a set of nesting dolls. When you open the biggest doll, you find a smaller one inside. Then you open that one and find an even smaller doll. This continues until you reach the smallest doll that cannot be opened anymore. That's how recursion works. A big problem is broken into smaller versions of the same problem until it becomes simple enough to solve.

---

### 1.1 Scenario B: Professional Email

**Goal:** Decline a job offer politely while maintaining a positive relationship.

#### Initial Prompt (V1)
Write an email declining a job offer.

#### Refined Prompt (V2)
Write a polite email declining a job offer while thanking the company for the opportunity.

#### Final Prompt (V3)
You are a professional career advisor. Write a formal email declining a job offer because I have accepted another opportunity. Express gratitude, remain respectful, and mention that I would like to stay connected for future opportunities.

#### Final LLM Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I sincerely appreciate the time and effort invested in the interview process and the confidence you showed in my abilities.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. Therefore, I must respectfully decline your offer.

I am grateful for the positive experience throughout the recruitment process and remain highly impressed by your organization. I hope to stay connected and would welcome the possibility of working together in the future.

Thank you again for your understanding. I wish you and your team continued success.

Sincerely,  
Sanjam Wadhwa

---

### 1.1 Scenario C: Creative Content

**Goal:** Create a marketing tagline for a new eco-friendly water bottle brand.

#### Initial Prompt (V1)
Create a tagline for an eco-friendly water bottle.

#### Refined Prompt (V2)
Create a catchy marketing tagline for a reusable eco-friendly water bottle.

#### Final Prompt (V3)
You are a professional copywriter creating a slogan for a new eco-friendly water bottle brand targeted at environmentally conscious young adults. The tagline should be short, memorable, and inspire sustainable living.

#### Final LLM Output

"Refill Today. Renew Tomorrow."

Additional Taglines:

- Drink Smart. Live Green.
- Every Sip Saves.
- Hydrate Naturally, Live Sustainably.
- One Bottle. Endless Impact.

---

### 1.2 Iteration Documentation

#### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|-------------|------------------------------|
| V1 | Explain recursion. | N/A | N/A |
| V2 | Explain recursion in simple language that a middle school student can understand. Include an example. | Added audience and example requirement. | Made the explanation easier to understand. |
| V3 | You are an expert teacher explaining concepts to children. Explain recursion to a 10-year-old using a fun real-life example. Avoid technical terms and keep the explanation under 150 words. | Added role, age group, example, and length limit. | Produced a more engaging and child-friendly explanation. |

#### Scenario B: Professional Email

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|-------------|------------------------------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Write a polite email declining a job offer while thanking the company for the opportunity. | Added politeness and gratitude. | Improved professionalism and tone. |
| V3 | You are a professional career advisor. Write a formal email declining a job offer because I have accepted another opportunity. Express gratitude, remain respectful, and mention that I would like to stay connected for future opportunities. | Added role and context. | Generated a realistic and professional email. |

#### Scenario C: Creative Content

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|-------------|------------------------------|
| V1 | Create a tagline for an eco-friendly water bottle. | N/A | N/A |
| V2 | Create a catchy marketing tagline for a reusable eco-friendly water bottle. | Added marketing focus. | Increased creativity and relevance. |
| V3 | You are a professional copywriter creating a slogan for a new eco-friendly water bottle brand targeted at environmentally conscious young adults. The tagline should be short, memorable, and inspire sustainable living. | Added role, audience, and context. | Produced stronger and more targeted taglines. |

---

### 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of responses. By assigning roles such as "expert teacher" and "professional copywriter," the model generated outputs with appropriate expertise and tone. Providing context about the audience and purpose helped the model create more relevant and focused responses. Overall, role-based prompting and context setting resulted in clearer, more accurate, and more effective outputs.

## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation

**Chosen Task:** Creating a Short Story Opening

**Prompt:** Write a 2-3 sentence opening for a story about a mysterious door discovered in an old library.

#### Low Temperature (0.2)

**Output:**
An old library stood quietly at the edge of town. While organizing books, a librarian discovered a hidden door behind a shelf. Nobody knew where it led.

#### Medium Temperature (0.7)

**Output:**
While dusting forgotten shelves in the oldest corner of the library, Emma noticed a small wooden door hidden behind rows of ancient books. Strange symbols were carved into its surface, and a faint glow seeped through the cracks.

#### High Temperature (1.2)

**Output:**
The door appeared only when the clock struck thirteen. Hidden behind a shelf of whispering books, it shimmered with silver light and seemed to breathe like a living creature. Emma reached for the handle as distant voices called her name from the other side.

### Comparison Table

| Temperature | Characteristics | Output Style |
|------------|----------------|-------------|
| 0.2 | Focused and factual | Simple and direct |
| 0.7 | Balanced | Descriptive and engaging |
| 1.2 | Highly creative | Imaginative and unpredictable |

### 2.2 Analysis & Recommendations

Low temperature is useful when generating factual information, technical documentation, and educational content. It is also suitable for customer support responses where consistency is important. High temperature is useful for creative writing and brainstorming sessions where originality is desired. For this task, the medium temperature worked best because it balanced creativity and coherence. The story remained interesting while still being easy to understand.


## Part 3: Strategic Prompting Techniques



## Part 4: Responsible AI & Limitations

