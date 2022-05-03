# PyCon US 2022 Feedback - DS booth

## Feature requests
**Notebooks features**
- I almost moved all of my workflow into VS Code, but didn't because I was unble to **copy and paste image outputs** in nb.
- It'll be cool to have **linting in notebooks**! Now that I think about it, it might be pretty complicated...
- It'd be awesome to have **automatic Black formating on save**, like Python does!
- Can I connect to my database and use **SQL / other querying functionalities in the notebook**? Or at least in VS Code so I don't have to have another tool open? I'm having to run my queries in a different tool, and copy and paste it into my notebook all the time.
- The **input box** (from the Python's input() function) normally shows up on the notebook output space in classic Jupyter, but the input box is showing up on the top by the command palette. Is there a way for me to change it?
- There needs to be **more hot keys for [Interactive Window]** python file so I can use with interactive window. # %% [...] is too much for me to write..
- **Data wrangler** looks pretty cool ([video](https://www.youtube.com/watch?v=7dVnCGHJI4c))! I'm loving the ad-hoc auto-updated visualization functionality. Though I'm not sure if the generated Python code will be as readable and understandable as the code I write myself.

**Kernel persistence**
- Would love to have the Interactive Window kernel to be automatically synced to the active kernel in my notebook. For example, I want to pd.read_csv, and then play around with that data frame in the IW.
- It's such a bummer that kernel state doesn't persist between VS Code sessions...

**Remote features**
- Sure, github.dev and vscode.dev are great, but can I have free GPU resource like Colab does? Can I try Codespaces without paying for it?

**Support for extended user scenarios**
- We don't have a lot of engineers, mostly data scientists. We use JupyterLab, and mainly the IPython terminal. https://ploomber.io/ works really well for us, and I'd like to see that integrated with VS Code.

## Bug reports
- "Save image" button saves my image with transparent background so I can barely see my axes and title.
- Formatting is slow both on notebooks and python files
- I primarily use Poetry, but notebooks in VS Code seems to have a hard time finding my interpreter at times, especially when I create a new notebook first (vs. opening a python file first).

## General feedback (also speaks to the type of devs at PyCon)
- Can you tell me why I would use this instead of JupyterLab? Can you put that up on the docs somewhere?
- I never have to context switch, so it's great. I have my notebook files next to my code files.
- Now that I know VS Code has **Interactive Window**, I'll come back to try out VS Code again.
- I love seeing active **Discord community** for products. I trust them more and it makes me feel more confident about using the tool and more approachable.
- **Remote experience** (containers & SSH) are excellent! I'm especially delighted by automatic port forwarding!
