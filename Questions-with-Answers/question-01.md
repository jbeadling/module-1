### Ticket: Research the History of the Command Line Interface (CLI)

#### Summary
Research the historical development, key milestones, and notable figures in the Command Line Interface (CLI) evolution.

#### Description
- Objective: Gain a comprehensive understanding of the CLI's history to inform future development and educational content.
- Scope: Cover from its inception to current iterations and identify key events, technological advancements, and individuals who have been instrumental in its development.

#### Tasks
1. Trace back to the initial concept of the CLI: Identify the first systems that used command-line interfaces.
2. Identify key milestones:
    - Development of early shells like Bourne Shell, C Shell, etc.
    - Introduction of scripting capabilities
    - Open-source contributions
    - CLI-based utilities and tools (e.g., grep, awk, sed)
3. Note important figures:
    - Who were the pioneers?
    - What organizations were pivotal?
4. Highlight major shifts:
    - Transition from text-based to graphical interfaces and how CLI maintained relevance.
    - Evolution with cloud computing and DevOps culture.
5. Examine current state:
    - Modern CLI tools and frameworks (e.g., PowerShell, Zsh)
    - CLI in cloud computing and microservices
6. Compile information into a coherent report or presentation.

#### Acceptance Criteria
- A detailed report or presentation that covers all the tasks.
- Cite credible sources for all information gathered.
- Provide a timeline that illustrates key events and milestones.
- Identify at least 3-5 notable figures and their contributions.
  
#### Priority
- Medium

***
### Answer


The CLI goes back to first days when computers were operated using punch cards and paper tape. Users entered commands 
and data through these methods. In the 1950s & 1960s computers systems employed batch processing, where users submitted jobs to be processed. Command and input were usually provided via punch cards.

The first terminals were teletypewriters which used a telegraph-style communication device. Users could input commands and
receive output from remote computers via serial bus.

In the 1960s MIT made a breakthrough with the CTSS (Compatible Time-Sharing System) that allowed multiple users to interact
with the computer simultaneously. Text-based commands were used. This is where video terminals came in, using CRT displays they allowed for more interactivity. 

Probably the most pivotal institution is Bell Labs (AT&T today) which saw the development of Unix and the first command-line shells. The first shell was made by Ken Thompson known as the Thompson shell or V6 shell. Thompson also develop the grep utility along with with it to search text files for patterns or regular expressions. Ken Thompson also developed sed in the early days of unix allowing users to perform search and replace, text deletion, and more. 

Awk is another command line utility developed by Alfred Aho, Peter Weinberger, and Brian Kernighan who developed it at Bell Labs in the late 70s. The name awk is derived from their initials. 

These tools: grep, sed, and awk would become the building blocks of unix based systems and are frequently used even today.

As time went on it became clear that the V6 shell was inadequate for more serious programming tasks. This would eventually lead to the Bourne Shell created by Steven Bourne and became the standard shell for Unix-like systems. 

C Shell came later and was made by Bill Joy at the University of California. The C Shell introduces things like history and job control.

Unix soon spread like wild fire and played a pivotal role in popularizing the CLI. The adoption of Unix throughout academia and industry cementing CLI's importance. 

Microsoft would follow suite with its own CLI through MS-DOS would put the CLI into residential homes. This would later be replaced with Microsoft Windows and with it came the Windows command prompt. A CLI that is still used in many enterprise environments (though PowerShell is becoming the standard). 

In the 1980s Richard Stallman would initiate the GNU Project. It's aim was to create a free Unix-like operating system. Combining the GNU utilities with Linus Torvalds Linux kernel. It would be known as GNU/Linux or Linux for short. Part of this project was the development of the GNU Bash shell, which is the standard shell on most Linux distributions even today. 

Today there are many shells available for Linux distributions (zsh, fish shell, korn shell, ash, dash, etc) though the vast majority of them are compatible with bash while offering additional features since bash is still the standard in the industry. Windows continues to develop PowerShell for more advance capabilities.

Interacting with CLI used to involve a terminal that was connected to the PC but these days terminals are emulated via software called Terminal Emulators. Most PCs are all GUIs now but there are terminal emulators preinstalled, usually for developers or power users who want to do things quicker. 

Not only can you choose which shell you want to use in most cases but there are now dozens of terminal emulators you can choose to customize your work environment how you like (Tabby, iTerm, kitty, GNOME, just to name a few). Today you can install several different shells to your liking and you can customize your terminal emulator from the font & colors, to what type of info you want display, and much more. Today is probably the best time to be a CLI user. 
