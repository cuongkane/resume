# CV Enhancement Skill

Enhance and update the CV (resume.tex) based on provided materials following professional CV writing best practices.

## Input

$ARGUMENTS - Materials to incorporate into the CV. Can include:
- Job descriptions to tailor the CV for
- New achievements, projects, or experiences
- Skills to add or highlight
- Certifications or education updates
- Any raw notes or accomplishments to be refined

## Instructions

### Step 1: Analyze the Input Material

Read the current CV at `resume.tex` and analyze the provided materials to understand:
- What type of update is needed (new role, new skills, tailoring for a job, etc.)
- Which sections need modification
- How to best incorporate the new information

### Step 2: Apply CV Writing Best Practices

When writing or updating CV content, follow these principles:

#### Action Verbs
Start each bullet point with a strong action verb. Use varied verbs appropriate to the achievement:
- Leadership: Led, Directed, Spearheaded, Orchestrated, Pioneered
- Development: Built, Developed, Architected, Engineered, Implemented
- Improvement: Optimized, Enhanced, Streamlined, Accelerated, Transformed
- Achievement: Achieved, Delivered, Exceeded, Surpassed, Accomplished
- Collaboration: Collaborated, Partnered, Coordinated, Facilitated

#### Quantify Achievements (STAR Method)
Transform vague statements into impactful metrics:
- BAD: "Improved system performance"
- GOOD: "Optimized database queries reducing latency by 40% and saving $50K/year in infrastructure costs"

Include numbers for:
- Scale (users, transactions, data volume)
- Impact (% improvement, cost savings, time saved)
- Scope (team size, number of services, regions)

#### Be Concise and Impactful
- Each bullet should be 1-2 lines maximum
- Lead with the most impressive aspect
- Remove filler words (helped, assisted, responsible for)
- Focus on outcomes, not just activities

#### Tailor for Target Role
If a job description is provided:
- Mirror keywords from the job posting
- Prioritize relevant experiences
- Adjust technical skills emphasis
- Reorder bullet points by relevance

#### Maintain Consistent Formatting
- Follow the existing LaTeX structure and commands
- Use `\resumeItem{Title}{Description}` format for bullet points
- Use `\resumeSubheading{Company}{Location}{Role}{Dates}` for positions
- Keep date formats consistent (Mon YYYY)

### Step 3: Section-Specific Guidelines

#### Experience Section
- Most recent and relevant first
- 3-5 bullet points per role (more for recent roles)
- Each bullet: Action verb + Task + Result/Impact
- Include technologies used naturally in context

#### Technical Skills
- Group by category
- List most relevant/proficient first
- Remove outdated technologies unless specifically relevant
- Match skills mentioned in target job description

#### Projects
- Focus on personal/notable projects
- Include tech stack and your specific contribution
- Quantify impact if possible

#### Education & Certifications
- Keep recent certifications prominent
- Include relevant coursework only if early career

### Step 4: Generate the Update

1. Present a summary of proposed changes before making them
2. Show the specific LaTeX code that will be added/modified
3. Ask for confirmation if making significant changes
4. Make the edits to resume.tex using the Edit tool

### Step 5: Quality Checklist

Before finalizing, verify:
- [ ] All bullets start with action verbs
- [ ] Achievements are quantified where possible
- [ ] No spelling or grammar errors
- [ ] Consistent formatting throughout
- [ ] LaTeX syntax is correct
- [ ] Content fits on 1-2 pages
- [ ] Most impactful items are prominently placed

## Example Transformations

**Before:** "Worked on improving the API performance"
**After:** "Optimized API response times by 60% through query optimization and caching, handling 10K+ requests/second"

**Before:** "Helped the team with code reviews"
**After:** "Mentored 3 junior engineers through 200+ code reviews, establishing team coding standards that reduced bug rate by 25%"

**Before:** "Built a machine learning model"
**After:** "Architected ML pipeline processing 5M daily predictions with 94% accuracy, reducing manual review time by 80%"

## Output

After completing the updates:
1. Summarize what was changed
2. Highlight key improvements made
3. Suggest any additional enhancements if applicable
4. Remind user to compile the LaTeX to verify formatting
