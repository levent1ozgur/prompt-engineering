# The RTF framework

R - Role
T - Task
F - Format

The "R-T-F" prompt framework categorizes requests into Roles, Tasks, and Formats for clearer communication.

This is the jack-of-all-trades prompt and can be used for most use cases, even non-work related ones.

Prompt Template:

> "Act like a [insert the role you want AI to take]. Give me a [insert task] in [insert format] format."

Example:

> "Act like a life coach with 30 years of experience in mentoring. Give me a plan to improve my work-life balance in table format."


# Chain of thought

The chain of thought prompt framework is one that improves LLM’s reasoning by telling AI to go through a problem step-by-step.

This makes it especially good for problem-solving or complex analytical tasks.

All you have to do is add the simple phrase “Let’s think step-by-step” at the end of your prompt.

Prompt Template:

> "[insert your prompt instructions].
> Let's think through it step-by-step."

Example:

> "How do I improve my sales calls? I've only got a 15% close rate right now, and I think it's because I'm not selling the dream enough.
> Let's think through it step-by-step."

# RISEN

R - Role
I - Instructions
S - Steps
E - End goal
N - Narrowing

The RISEN framework provides a structured approach to dissect complex or constrained tasks, such as blog posts or research projects, into actionable components for better execution and focus.

Prompt Template:

> "Role: [insert the role you want AI to take.] 
> Main Task: [Insert the task you want AI to complete.]
> Steps to complete task: [Insert numbered list of steps to follow.]
> Goal: [Insert goal of the output]
> Constraints: [Enter constraints]."

Example:

> "Role: You are an expert digital course builder who has sold millions in online courses.
> Main Task: Please give me a list of EVERYTHING important that I should include in my AI course and tell me all the different methods of growth I can implement to maximise revenue.
> Steps to complete the task:
> 1. First start by covering all the things that ANY digital course should include. 
> 2. Then proceed by giving your thoughts on what AI courses should include. 
> 3. End with covering the best growth marketing tactics and strategies for digital courses.
> Goal: The goal is to give me a concise list of everything I should include within the course, as well as give me ideas on how I can maximize the revenue from my course.
> Constraints: Maximum of 500 words. - Avoid technical jargon. - Make it actionable - Make it clear"

# RODES

R - Role
O - Objective
D - Details
E - Examples
S - Sense Check

While this is similar to the above prompt, this one is better used whenever you have good examples of your desired output.

Prompt template:

> R - Role: [Insert desired role you want AI to take.]
> O - Objective: [Insert objective you want AI to do.]
> D - Details: [Insert any context or constraints AI needs to create a good output]
> E - Examples: Here are good examples you can use to model your answer. [ Insert examples of good outputs ]
> S - Sense Check: Do you understand the objective and the specific guidelines for this task?

Example:

> R - Role: You are a seasoned copywriter specialized in crafting viral tweets.
> O - Objective: Write a twitter hook that aims to go viral on the topic of Marketing. 
> D - Details: - The tweet should be no longer than 280 characters.
> - Use powerful and persuasive language.
> - Do not include hashtags or emojis.
> E - Examples: Here are some examples you should use to model your answer (note - these are not on my desired topic. I just want you to understand the frameworks and styles that work")
> 1."Credit card debt is killing your financial progress.
> Here's how you get rid of it ASAP:"
> 2. "The most valuable Twitter feature you aren't using: 
> Advanced search.
> Knowing how to use it will help you find the hidden gems of the Twitter archives and 10x your Twitter experience.
> Here's the step-by-step guide:"
> 3. "99% of business advice is terrible.
> I’ve consulted hundreds of CEOs and made a list of widely accepted wisdom that you should ignore. 
> Here are 7 “smart” sounding pieces of advice that are actually stupid:"
> S - Sense Check: Do you understand the objective and the specific guidelines for this task?
