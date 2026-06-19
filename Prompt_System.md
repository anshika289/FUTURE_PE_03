# 🤖 Master Prompt System — AI SEO Blog & Content Cluster Generator

> **File:** `Prompt_System.md`  
> **Purpose:** Reusable prompt templates for generating complete SEO content packages  
> **Compatibility:** ChatGPT (GPT-4o) · Claude (Anthropic) · Gemini (Google)

---

## 📖 How to Use This Prompt System

1. Copy the **Master Prompt** below in its entirety
2. Replace every `[VARIABLE]` placeholder with your specific business information
3. Paste the completed prompt into your AI tool of choice
4. Review, refine, and publish the generated content
5. Document your AI tool outputs in the `/screenshots` folder

---

## 🎯 Input Variables Reference

Before running the prompt, prepare the following information:

| Variable | Description | Example |
|---|---|---|
| `[BUSINESS_TYPE]` | Type of business or industry | Dental Clinic |
| `[TARGET_AUDIENCE]` | Who your ideal customers are | Adults aged 25–50 seeking dental care |
| `[PRIMARY_KEYWORD]` | Main SEO keyword to rank for | best dental clinic in Delhi |
| `[SECONDARY_KEYWORDS]` | Supporting related keywords | teeth whitening Delhi, dental implants Delhi, affordable dentist near me |
| `[LOCATION]` | City, state, or neighborhood | Delhi, India |
| `[BLOG_LENGTH]` | Approximate word count | 1200–1500 words |
| `[TONE]` | Writing style and voice | Professional, friendly, reassuring |

---

## 🔑 THE MASTER PROMPT

> Copy everything between the triple dashes below and paste into your AI tool.

---

```
You are an expert SEO Strategist, Content Marketer, and Copywriter with 10+ years of experience 
helping local businesses rank on Google.

I need you to generate a COMPLETE SEO content package for the following business. Use all the 
information I provide and follow every instruction precisely.

=== BUSINESS INFORMATION ===
Business Type: [BUSINESS_TYPE]
Target Audience: [TARGET_AUDIENCE]
Primary Keyword: [PRIMARY_KEYWORD]
Secondary Keywords: [SECONDARY_KEYWORDS]
Location: [LOCATION]
Blog Length: [BLOG_LENGTH]
Tone: [TONE]

=== YOUR TASK: Generate ALL of the following in order ===

---

## 1. SEO METADATA PACK
Generate:
- SEO Title (60 characters max, include primary keyword near the front)
- Meta Title (same as SEO title or slight variation, 50–60 characters)
- Meta Description (150–160 characters, include primary keyword, a benefit, and a CTA)
- URL Slug (lowercase, hyphens only, 3–6 words, includes primary keyword)

---

## 2. H1 HEADING
Write one powerful H1 heading that:
- Includes the primary keyword
- Is compelling and benefit-driven
- Is 60–80 characters long

---

## 3. COMPLETE BLOG OUTLINE (H1 / H2 / H3 Structure)
Create a detailed outline with:
- 1 H1 (the main title/heading)
- 6–8 H2 sections covering different aspects of the topic
- 2–3 H3 subpoints under each H2 where relevant
- Include: Introduction, Main Content Sections, FAQ Section, Conclusion, CTA

---

## 4. LONG-FORM SEO BLOG ([BLOG_LENGTH] words)
Write the complete blog following the outline above. Requirements:
- Write in [TONE] tone, human-like and conversational — not robotic
- Naturally integrate [PRIMARY_KEYWORD] in the first paragraph, 2–3 times in the body, 
  and once in the conclusion (avoid keyword stuffing)
- Naturally weave in [SECONDARY_KEYWORDS] across the blog
- Use short paragraphs (2–4 sentences max) for readability
- Use transition phrases to guide readers smoothly between sections
- Include real-world examples, statistics, or scenarios relevant to [LOCATION]
- Bold important terms or phrases for emphasis
- Write for both humans and search engines
- End with a strong FAQ section (5 questions with detailed answers)
- Close with a Conclusion paragraph
- End with a compelling Call-to-Action (CTA) encouraging the reader to contact/visit/book

---

## 5. FAQ SECTION (Standalone)
Generate 5 frequently asked questions with detailed answers (80–120 words each).
Format using:
Q: [Question]
A: [Answer]
Make questions match real search queries people type on Google.

---

## 6. CALL-TO-ACTION (CTA)
Write 3 variations of a CTA:
- CTA 1: Urgency-based
- CTA 2: Benefit-based
- CTA 3: Question-based (engages reader curiosity)

---

## 7. INTERNAL LINKING OPPORTUNITIES
List 5 internal linking suggestions for this blog:
Format as:
Anchor Text → Suggested Target Page/Article Title
Explain in 1 sentence why each link matters for SEO.

---

## 8. CONTENT CLUSTER IDEAS
Based on [PRIMARY_KEYWORD] and [BUSINESS_TYPE], generate:
- 1 Pillar Page Topic (broad, authoritative)
- 10 Cluster Article Topics (specific, supportive)
Display as a structured table with columns: Article #, Title, Target Keyword, Search Intent

---

## 9. LOCAL SEO VARIANT
Create a local SEO version of the meta tags and suggest a blog topic for 3 specific 
neighborhoods or areas within [LOCATION]:
For each neighborhood provide:
- Local Keyword
- Meta Title (60 chars)
- Meta Description (155 chars)
- Suggested Blog Topic

---

## FORMAT RULES:
- Use Markdown formatting throughout
- Use ## for H2, ### for H3
- Keep all sections clearly labeled
- Do not skip any section
- Do not add disclaimers or AI caveats — write as a professional SEO copywriter
```

---

## 🔄 Prompt Variations by AI Tool

### Using with ChatGPT (GPT-4o)
- Paste the full prompt as a single message
- If output is cut short, type: "Continue from where you left off"
- Use the "Custom Instructions" feature to set your writing style as a preset

### Using with Claude (Anthropic)
- Claude excels at structured, well-formatted markdown output
- Ask Claude to "review and improve the meta description for keyword density"
- Use Projects feature to save your business context across sessions

### Using with Gemini (Google)
- Gemini integrates with Google Search — great for keyword validation
- Ask Gemini to cross-reference keywords with "Google Search trends in [LOCATION]"
- Use Gemini Advanced for longer, more detailed blog outputs

---

## 🧩 Modular Sub-Prompts

Use these shorter prompts for specific tasks:

### Sub-Prompt A: Keyword Research Only
```
You are an SEO specialist. For a [BUSINESS_TYPE] in [LOCATION], generate:
- 1 primary keyword with monthly search volume estimate
- 10 secondary keywords with search intent labels (Informational / Navigational / Transactional)
- 5 long-tail keyword variations
- 3 competitor keywords to target
Format as a clean table.
```

### Sub-Prompt B: Meta Tags Only
```
Write SEO meta tags for a [BUSINESS_TYPE] in [LOCATION] targeting the keyword "[PRIMARY_KEYWORD]".
Output:
- Meta Title (max 60 characters)
- Meta Description (max 160 characters)
- Open Graph Title
- Open Graph Description
Keep all outputs within character limits.
```

### Sub-Prompt C: FAQ Generation Only
```
Generate 7 FAQs for a [BUSINESS_TYPE] in [LOCATION]. 
Target keyword: [PRIMARY_KEYWORD]
Format each as:
Q: [Natural language question a patient/customer would Google]
A: [Helpful, 80–100 word answer that gently promotes the business]
Use conversational, trustworthy tone.
```

### Sub-Prompt D: Content Cluster Only
```
Create a content cluster strategy for a [BUSINESS_TYPE] website targeting [PRIMARY_KEYWORD].
Generate:
- 1 Pillar Page topic (comprehensive guide)
- 12 supporting Cluster Articles (specific subtopics)
For each article include: Title, Target Keyword, Search Intent, Suggested Word Count
Display as a markdown table.
```

---

## 📊 Prompt Performance Tips

| Tip | Why It Matters |
|---|---|
| Always include Location | Helps AI generate locally relevant examples and statistics |
| Specify exact word count | Prevents overly short or bloated outputs |
| Define your tone clearly | "Professional yet friendly" gives better results than just "professional" |
| List 3–5 secondary keywords | Gives the AI enough variety to avoid keyword repetition |
| Request Markdown formatting | Makes the output GitHub and CMS-ready immediately |
| Ask for bold key terms | Improves on-page readability and scannability |
| Include CTA instruction | Many AI outputs forget CTAs unless explicitly requested |

---

*Master Prompt System — AI SEO Blog & Content Cluster Generator*  
*Version 1.0 | Internship Project Submission*
