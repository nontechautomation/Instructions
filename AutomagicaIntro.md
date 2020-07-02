## Robotoc Process Automation (RPA)
Robotic process automation has gained a lot of populaity in recent years. With recent advancement in artificial intelligence and machine learning, RPA tools/frameworks are becoming more sofisticated. There are many commercial and open-source tools available for RPA. We are going to look for one such tool/library automagica in this article.   

___

### Prerequisites
1. Python must be installed on the machine.
2. IDE like jupyter, nteract, pycharm should be installed on the machine. Any editor should work ideally. 
___

### Introduction
Automagica is an open source automation library which allows users to develop scripts to boost their productivity and eficiency. Automagica uses some of the most popular automation libraries like [selenium, pyautogui etc](https://github.com/automagica/automagica/wiki/Documentation). 

Automagica is a python based library so having some basic programming knowledge will be useful. 

### Automagica vs. Other commercial tools

|                                                                                                    |                                 Automagica                                |                                                                                                                                    UiPath                                                                                                                                    |                                                                                                             BluePrism                                                                                                             |   |
|----------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|---|
|                                        Programming language                                        |                      Python (rank #3 in TIOBE index)                      |                                                                                                                 C# .Net (Microsoft) (rank #5 in TIOBE index)                                                                                                                 |                                                                                            C# .Net (Microsoft) (rank #5 in TIOBE index)                                                                                           |   |
|                                              Platforms                                             |                           Windows, MacOSX, Linux                          |                                                                                                                                 Windows only                                                                                                                                 |                                                                                                            Windows only                                                                                                           |   |
|                                             Open-source                                            |                                     ✔️                                     |                                                                                                                                       ❌                                                                                                                                      |                                                                                                                 ❌                                                                                                                 |   |
|                                           Easy deployment                                          |                                     ✔️                                     |                                                                                                                                       ❌                                                                                                                                      |                                                                                                                 ❌                                                                                                                 |   |
| Out-of-the-box compatibility with popular machine learning libraries (TensorFLow, Torch, Keras, …) |                                     ✔️                                     |                                                                                                                                       ❌                                                                                                                                      |                                                                                                                 ❌                                                                                                                 |   |
|                                          Cloud deployment                                          |                                     ✔️                                     |                                                                                                                                       ✔️                                                                                                                                      |                                                                                                                 ❓                                                                                                                 |   |
|                                        On-premise deployment                                       |                                     ✔️                                     |                                                                                                                                       ✔️                                                                                                                                      |                                                                                                                 ✔️                                                                                                                 |   |
|                                       Automation file format                                       |                            Open standards (.py)                           |                                                                                                                          Proprietary UiPath XML-like                                                                                                                         |                                                                                                         Proprietary format                                                                                                        |   |
|                                          Choice of editor                                          |                      Any editor of choice can be used                     |                                                                                                                           Proprietary UiPath Studio                                                                                                                          |                                                                                                   Proprietary BluePrism Desktop                                                                                                   |   |
|                                          Training material                                         |                                    Free                                   |                                                                                                                   Free (limited) and paid training program                                                                                                                   |                                                                                           Free (very limited) and paid training program                                                                                           |   |
|                                      Required developer skills                                     |                       Python scripting acquaintance                       |                                                                                                     Proprietary knowledge of UiPath tooling and C# programming knowledge.                                                                                                    |                                                                             Proprietary knowledge of BluePrism tooling  and C# programming knowledge.                                                                             |   |
|                                     Robot hardware requirements                                    | 1 core CPU and 1 GB RAM (or depending on the application to be automated) |                                                                                                4 core 2.4Ghz CPU and 8GB RAM (or depending on the application to be automated)                                                                                               |                                                                          4 core 2.4Ghz CPU and 8GB RAM (or depending on the application to be automated)                                                                          |   |
|                                  On-premise hardware requirements                                  |      1 single machine for the robot (see robot hardware requirements)     | For UiPath Orchestrator (4×2,4Ghz CPU and 8GB RAM), Microsoft SQL Server (4×2,4Ghz and 8GB RAM and 100GB storage), ElasticSearch (4×2,4Ghz and 4GB RAM and applicable storage) and Kibana. For Uipath Robot (4×2.4Ghz CPU and 6GB RAM) For Studio (2×2.4Ghz CPU and 6GB RAM) | Microsoft SQL Server 2012 R2 (4×2,4Ghz and 8GB RAM and 100GB storage) Interactive Client (4GB RAM) Runtime resource (4GB RAM) Application server: 4 core 2.4Ghz CPU and 8GB RAM (or depending on the application to be automated) |   |
|                                            Pricing model                                           |   Free for non-commercial use. Commercial: per robot (fixed monthly fee)  |                                                                                                                                       ❓                                                                                                                                      |                                                                                                                 ❓                                                                                                                 |   |
|                 Additional commercial software licenses needed other than the robot                |                                    None                                   |                                                                                                    For UiPath Orchestrator: Microsoft SQL Server, ElasticSearch and Kibana                                                                                                   |                                                                                                        Microsoft SQL Server                                                                                                       |   |

___
## Installing automagica
**Autoagica** is similar to any other python packge. So automagica can be installed using ```pip install automagica```. More information around installation can be found on this [link](https://pypi.org/project/Automagica/).

___

## Common tasks which can be automated using automagica

1. Webbrowser
2. Excel
3. Data Analysis
4. Power point
5. Email
6. Folder operation

There are many other operations supported by the automagica library.Those functionalities can be explored based on the requirements. Other functionalities includes ```OCR(Optical character recognition), image processing, terminal, outlook etc```. More details can be dound [here](https://automagica.readthedocs.io/).In the tutorial series, I am going to cover the functionalities listed above. 

___

## References
1. [Documentation](https://automagica.readthedocs.io/)
2. [Github Documentation Page](https://github.com/automagica/automagica/wiki/Documentation)