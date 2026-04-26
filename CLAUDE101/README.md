# Prompt Stuff
Define a prompt properly:
- Set stage (Create this and that)
- Define Task (Include this and that)
- Rules (Use this and that)

Also add contexts, they are like shortcuts for Claude to understand context. 

The iteration mindset:
- One of the most important shifts when working with Claude is recognizing that your first prompt rarely produces a perfect result—and that's okay. Think of your initial prompt as the start of a conversation, not a one-shot request.

# Using Projects:

**Key takeaways**
- Projects are self-contained workspaces with their own memory, chat histories, knowledge bases, and customized instructions. Think of them as dedicated environments for specific work streams.
- Project knowledge enhances Claude's understanding by letting you upload relevant documents that Claude references across all chats within that project. No more re-uploading the same files each time.
- Project instructions guide Claude's behavior—you can specify tone, expertise level, response style, and more. These instructions apply to every conversation within the project.
- Projects scale automatically. When your knowledge base approaches context limits, Claude seamlessly enables Retrieval Augmented Generation (RAG) mode to expand capacity by up to 10x while maintaining response quality.
- For Claude for Work users, projects enable collaboration. Share projects with teammates so everyone benefits from the same context, instructions, and accumulated knowledge.

**Goodies for Projects**
- When you create a project, quickly explain this project is for XYZ purpose, use this tone throughout, dont agree with everything (my example), do this and that. Clear your instructions once you create a project. 

# Using Artifacts
- Be specific about what you want. "Build a budget tracker" is good, but "Build a monthly budget tracker where I can input expenses by category, see a pie chart breakdown, and get a warning when I'm over budget" is better.
- Describe the end user. Telling Claude who will use the artifact helps it make appropriate design choices. "This flowchart is for new employees" leads to different results than "This flowchart is for the engineering team."

# Skills vs. Projects
Projects store knowledge, skills perform tasks.

-> Projects are knowledge hubs. They hold the reference materials Claude needs to understand your work—project specs, meeting notes, research documents. When you upload files to a project, Claude draws on that information across every conversation within that project.

-> Skills are procedural machines. They encode how Claude should execute a task—the specific steps, order of operations, and methodology you want followed every time. Skills shine when you have repeatable workflows you want Claude to run consistently.

