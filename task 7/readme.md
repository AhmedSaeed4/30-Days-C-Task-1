# Speckit Plus  
Speckit Plus is a framework for AI-native development.
It is a tool that organizes Spec-Driven Development to make collaborating with AI easier and error-free.It splits large projects into small, text-based context files so the AI never gets confused. It uses built-in commands like /sp.constitution, /sp.specify, /sp.plan, and /sp.implement to build your project from start to finish.

# Speckit plus commands

## 1 /sp.constitution
A Constitution defines the global rules for your entire project.It acts as the starting point of your project, ensuring that every specific plan or task you create automatically follows your quality standards.

## 2 /sp.specify
/sp.specify is the command that turns your ideas into a crystal-clear plan for a specific task. It is the step where you tell the AI exactly what to build for this one project. When you run this command, the agent,
Writes a formal Rulebook (Specification file) just for this specific project.

## 3 /sp.plan
/sp.plan is the command that creates the blueprint for how to build your project.
It takes the requirements from the Specification and turns them into a step-by-step technical strategy.
When you run this command, the agent,Generates a plan.md file that maps out the entire project structure. Breaks the work into phases Research, Foundation, Analysis etc.

## 4 /sp.tasks
/sp.tasks is the command that breaks your big plan into small, manageable actions.It organizes the work into small, focused steps, ensuring the AI doesn't try to complete the whole project at once.When you run this command, the agent,Lists specific steps to execute the plan. Enforces the Checkpoint Pattern, The AI completes one task, then stops and waits for you to review and approve it.


## 5 /sp.implement 
/sp.implement is the command that executes the work.It is the phase where you and the AI work together to actually build the product defined in your tasks.When you run this command, the agent,
reads your tasks.md file to know exactly what to do, You direct the work, and the AI executes it.It compares the results to your Specification to ensure they match your success criteria. The agent stops after every checkpoints so you can review and approve the work before moving forward.
