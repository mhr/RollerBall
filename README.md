# RollerBall Demo (Unity + Jupyter Notebook)

## Setup and Dependencies
- [Git-LFS](https://git-lfs.github.com/)
  - Unity has many very large files (>50 MB) that don't play nicely with git, which was originally designed to handle only text files
  - To make Unity play nicely with git, install git-lfs (Git-Large File System)
- [Unity (2019.4.17f1)](https://unity3d.com/unity/qa/lts-releases?version=2019.4.17f1)
- [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
  - In the Unity Editor, make sure to install a version >1.4.0 by going to Window > Package Manager, selecting "Show preview packages", finding "ML Agents", selecting "See all versions", and finally selecting the latest version
  - In this repository, we're using version 1.7.2-preview
- Python 3.6 or 3.7
- Other Python Packages
  ```
  $ python -m venv rollerball-venv
  $ rollerball-venv\Scripts\activate.bat # windows
  $ source rollerball-venv/bin/activate # MacOS or Linux
  $ pip install matplotlib numpy
  ```

## Unity Background
- [Unity Background](https://github.com/Unity-Technologies/ml-agents/blob/release_12_docs/docs/Background-Unity.md)
- [Short, Complete, and Official Unity Tutorial (Roll-a-Ball)](https://learn.unity.com/project/roll-a-ball)
- [Unofficial Unity Tutorials by Catlike Coding](https://catlikecoding.com/unity/tutorials/)
- [Unity Game Loop Order of Execution](https://docs.unity3d.com/Manual/ExecutionOrder.html)
  - Understanding this game loop is critical to understanding how any program in Unity works

## Unity ML-Agents Toolkit
- [UMLA Overview](https://github.com/Unity-Technologies/ml-agents/blob/release_12_docs/docs/ML-Agents-Overview.md)
- [Short, Complete UMLA Tutorial](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Create-New.md)
  - That's this project!
  - I've also gone through the trouble of adding a Jupyter notebook that connects to this project
- [UMLA Agent Documentation](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Design-Agents.md)
  - This is extremely helpful for understanding the nitty-gritty details of the C# Agent class (knowing how to reset things, how to keep track of visual/vector observations, etc.)

## Getting Help
- [Visit the Official Unity Discord](https://discord.com/invite/Unity)
  - For UMLA-specific questions, go to the [#machine-learning channel](https://discord.com/channels/489222168727519232/502171346503991307)
- Post to the [Official Unity ML-Agents Forum](https://forum.unity.com/forums/ml-agents.453/)
