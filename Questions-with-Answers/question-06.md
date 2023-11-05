### Ticket: Write a Summary on Different Shell Types (Bash, Zsh, Fish, Dash)

---

#### Summary

Compose a comprehensive summary that explores the characteristics, functionalities, and distinctions among four different shell types: Bash, Zsh, Fish, and Dash.

---

#### Description

- **Objective**: To inform and educate about the differences among these shell types, highlighting their unique features, advantages, and use cases.
  
- **Scope**: 
  - Core functionalities
  - Features that make each shell unique
  - Advantages and disadvantages
  - Popular use cases for each

---

#### Tasks

1. **Research Bash**: 
  - Identify core functionalities and unique features.
  - Note any advantages or disadvantages.
  
2. **Research Zsh**: 
  - Identify core functionalities and unique features.
  - Note any advantages or disadvantages.

3. **Research Fish**: 
  - Identify core functionalities and unique features.
  - Note any advantages or disadvantages.

4. **Research Dash**: 
  - Identify core functionalities and unique features.
  - Note any advantages or disadvantages.

5. **Compile Information**: 
  - Summarize the findings in a concise but informative document.

---

#### Acceptance Criteria

- A document that covers all the tasks mentioned, providing a well-rounded view of each shell type.
- Factual accuracy is necessary, and citations or references should be included where applicable.

---

#### Priority

- Medium

***
### Answer


Different shells and their core characteristics:

**Bash (Bourne-Again Shell)**:
One of the most widely used shells and comes pre-installed on almost every modern Unix system. It was the improved replacement of the original Bourne Shell (sh) and offers compatibility with sh scripts. 

Bash was one of the first shells to provide a robust scripting environment and offer customization through config files like ".bashrc" & ".bash_profile", command history, tab-comepletion, and scripting capabilities like conditionals, loops, and functions.

Bash is the standard even today however it may feel a bit dated compared to newer shells that offer more extensive features and plugins. Still, it's extensive presence makes it a good choice to use in any environment. Most scripts are still written in Bash to ensure compatibility with as many systems as possible. 

**Zsh (Z Shell)**:
If Bash was considered the improved Bourn Shell than Zsh may be considered the improved Bash. Zsh has powerful and interactive features which make it highly extensible and user-friendly. It still retains compatibility with Bash and other shells.

Zsh has advanced auto-completion, spelling correction, and a huge set of plugins and themes. It supports interactive prompt customization, shared command history among terminal sessions, and a flexible configuration system with the ".zshrc" file.

Probably the biggest feature of Zsh is its huge ecosystem of plugins and themes. Most important is the framework "oh-my-zsh" which is a rework for Zsh and combines all the customization options into a simple and easy to manage framework. This is probably the most popular reason to use Zsh. Chances are if you using Zsh you are also using the "oh-my-zsh" framework. It is insanely popular among developers.

The only possible weakness is 

**Fish (Friendly Interactive Shell)**
Fish is designed with a focus on simplicity and ease of use. It prioritizes a user-friendly interface over strict compatibility with other shells.

As a user friendly shell Fish provides syntax highlighting, autosuggestion, and a config file known as "config.fish". Fish focuses on making the command line experience as user friendly as possible and thus is recommending for beginners as a way to ease into a CLI environment. 

The one disadvantage of Fish is that it doesn't use standard syntax and this limits its scripting capabilities a little bit. Unfortunately Fish is not recommended if you're trying to write scripts that are compatible with POSIX shell scripts.

**Dash**
If Fish is designed for beginners than Dash is designed for the professional. Dash is a minimalist shell designed for scripting and system maintenance tasks. It is known for its speed and adherence to POSIX standards.

Dash isn't as customizable as some other shells (such as Zsh) but that's the point. It emphasizes fast script execution. Dash adheres closely to the POSIX standard, making it a good choice for writing portable shell scripts.

Dash lacks some of the more advanced features like interactive prompt customization and tab-completion. It is designed to be lightweight, POSIX-compliant shell for scripting tasks and bootstrapping system scripts. 
