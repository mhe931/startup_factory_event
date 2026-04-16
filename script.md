# Workshop Master Script: Mastering the AI Interface
**Date:** Tomorrow
**Time:** 12:00 – 16:45
**Location:** Startup Factory, Vaasa
**Host:** Däniel Ebrahimzadeh

---

## 12:00 – 12:40 | Introduction & Targets
**Goal:** Break the ice and set the goals for the day.

**Däniel's Script:**
"Hi everyone. I'm Däniel. I study AI and Data Engineering here at the University of Vaasa. I spend most of my time looking at data, but today I want to show you the practical side of AI. Startup Factory is about building things, so we aren't just here to talk. We are here to create.

Let's start around the room. Please tell me your name, what you're studying or building, and what is the one thing you want to walk away with today. Is it a business plan? A landing page? Or just understanding how to stop the AI from lying to you?"

**Participant Task:**
State their name, their startup idea, and their specific goal.

---

## 12:40 – 13:40 | The CREATE Framework & Prompt Anatomy
**Goal:** Move from "Asking" to "Engineering."

**Däniel's Script:**
"Okay, first thing. AI is not Google. If you treat it like a search engine, you get average results. To get professional results, we need a structure. We use CREATE: Context, Role, Explicit instructions, Audience, Tone, and Evaluation. 

Think about it like this. If you hire an intern and just say 'Write a plan,' they will fail. If you say 'You are a marketing lead, we are in Vaasa, we need 3 ways to reach students on a 50 euro budget,' they will succeed. That’s what we are doing here."

**Slide: Anatomy of a Prompt & Master Prompt Scroll**
"Now, let's look under the hood. This prompt isn't just a sentence; it's a system. Notice how we didn't just ask for a plan, we gave the AI a job, a location, a specific audience, and a format. This reduces hallucination."
*(Show the scrolled Master Prompt for Vaasa Student Cleaning Service)*: "Look at the length and detail! This is what you hand to an AI to get a professional, ready-to-code Product Requirements Document. If your prompts are only 2 sentences long, start making them look exactly like this."

**Business Example: Local Bike Rental (Vaasa)**
- **Context:** A new e-bike rental service near the University.
- **Role:** Local Marketing Consultant.
- **Goal:** Create a 1-week launch strategy.

**Step-by-Step Exercise (40 mins):**
1. Pick your business idea (e.g., A sustainable coffee shop, a cleaning app, or a niche SaaS).
2. Write a prompt using all 6 CREATE letters.
3. Share the result with the person next to you.

---

## 13:40 – 14:10 | Break & Lunch
"Take a break, grab some food. Talk to each other about your ideas. We’ll start the hard logic part in 30 minutes."

---

## 14:10 – 15:30 | Logic & The Skeptical VC
**Goal:** Stress-test the business model using Chain-of-Thought (CoT).

**Däniel's Script:**
"Welcome back. Now we get serious. AI can hallucinate. It makes things up. To fix this, we use Chain-of-Thought. We tell it: 'Think step-by-step.' This forces the model to show its math before giving an answer.

We are also going to use the 'Skeptical VC' persona. This is a prompt that tells the AI to be your harshest critic. It's better to fail here than in a real pitch."

**Example: SaaS for Finnish SMEs**
- **Prompt:** "Estimate the market size for an automated bookkeeping tool for small businesses in Finland. **Think step-by-step.** First, find the number of registered SMEs. Second, estimate how many use manual systems. Third, calculate a price point."

**Example: The VC Critique**
- **Prompt:** "Act as a Senior Partner at a Tier-1 VC firm. Here is my idea: [Describe idea]. Find 3 fatal flaws in my logic. Ask me 3 nightmare questions. Don't be nice."

**Exercise (60 mins):**
1. Use the CoT prompt to calculate your market size.
2. Run the VC Critique prompt.
3. Write down your answers to the 'nightmare' questions the AI asks you.

---

## 15:30 – 15:45 | Break
"Quick stretch. Next, we build the actual product."

---

## 15:45 – 16:30 | Building the MVP
**Goal:** Generate a Technical PRD and a Landing Page.

**Däniel's Script:**
"The final part is building. We want to leave here with something real. We are going to ask the AI to write a Product Requirements Document (PRD). This is a map for developers. Then, we will ask it to code a simple landing page in HTML."

**Prompt Example: The Landing Page**
> "Act as a web developer. Create a single-file HTML landing page for my business. Use Tailwind CSS for a modern, clean look. Include a hero section with a call to action button. Make it look like a high-end Nordic startup."

**Exercise (40 mins):**
1. Ask the AI to write a PRD for your MVP.
2. Generate the HTML code for your landing page.
3. Open the code in a browser to see it.

---

## 16:30 – 16:45 | Showcase, Snacks & Gifts
**Goal:** Celebrate the wins.

**Däniel's Script:**
"We are at the finish line. Who wants to show their landing page? Who got a really tough question from the VC? Let's see some results. 

I have some small gifts for the best prompts and most improved ideas. Grab a snack, and thank you for being here. Special thanks to Negar for the support. You aren't just users anymore, you're engineers. Let's keep building in Vaasa."

---

## Post-Lecture Element: The Cheat Sheet
*Participants will be directed to take a photo of the Cheat Sheet slide detailing C.R.E.A.T.E, Magic Triggers (Think step-by-step, Reason first, Cite sources), and Core Personas (Skeptical VC, Technical Founder).* "This is your tactical anchor. Take a photo of this slide."

---

### Tips for the Solo Host (Däniel)
- **Watch the clock:** Since you don't have mentors, you be the timekeeper. Give a 5-minute warning before every section ends.
- **Check in:** Every 15 minutes, walk around. If someone looks confused, ask "What is the AI telling you?"
- **Keep it simple:** If the code part is too hard for some, tell them to focus on the PRD instead.