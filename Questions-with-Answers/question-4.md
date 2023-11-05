### Ticket: Explain the Difference Between a Terminal and a Shell

#### Summary
Clarify the distinction between a terminal and a shell, focusing on their roles, functionalities, and interactions within an operating system.

#### Description
- Objective: To create straightforward, factual content that delineates the roles and functionalities of a terminal and a shell. This information will serve for educational purposes, documentation, or development.
- Scope: Include key terms, historical context if necessary, and specific use cases or examples to illustrate the differences.

#### Tasks
1. Research the function and history of the terminal:
    - What is a terminal?
    - What roles does it fulfill?
    - Types of terminals (e.g., hardware terminal, terminal emulator)
2. Research the function and history of the shell:
    - What is a shell?
    - Types of shells (e.g., Bash, Zsh, PowerShell)
    - What roles does it fulfill?
3. Investigate the interaction between terminal and shell:
    - How do they communicate?
    - How are they dependent or independent of each other?
4. Compile this information into a clear and concise explanatory text or report.

#### Acceptance Criteria
- A well-structured text or report that addresses all the tasks.
- Use real-world examples or analogies to clarify the distinctions.
- Ensure all statements are factual and supported by credible sources.

#### Priority
- Medium

***
### Answer

A shell and a terminal are two distinct tools and concepts that when combined make up the CLI interface.

The shell is the software that provides a CLI to interact with an Operating System's kernel (the Kernel is the layer that interacts
with the hardware itself). The CLI is an intermediary between the user and operating system. It interprets user commands and executes them. This is all relayed to the kernel as well so you could say that the CLI is the intermediary between the user and the kernel.

The terminal is either a software or hardware device that provides the user with an interface to interact with the shell with. Even though I mentioned that the terminal can be a hardware device this is rarely the case anymore. In the older days people would use hardware terminals (also referred to as dummy terminals) to interact with a Computer, they would send commands through the device and get the output through it as well. These terminals were directly connect to the Computer.

Today people use software terminals or "terminal emulators" to interact with the CLI. The Shell and terminal are all installed on the same device. You can also install different types of terminals. There are many terminals with various customization available, it all comes down to preference. Many OS's come with a default terminal emulator. 

So the shell is the command interpreter that processes and executes commands, the terminal interface is what users use to interact with the shell. The flowchart of commands looks something like this:
           
User <--> Terminal Emulator <--> Shell <--> Kernel

After the command is process by the kernel the output is sent back to the shell shown on the terminal emulator and seen by the user.