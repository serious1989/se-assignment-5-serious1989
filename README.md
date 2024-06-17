[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15268945&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
     
Step 1: Download Visual Studio Code
a.	Open a web browser on your Windows 11 and type the url address https://code.visualstudio.com/ in the address bar and press Enter.
b.	Click the download button on the homepage to download the VS code package.
Step 2: Run the Installer
a.	Locate the downloaded installer file and double-click the installer file (e.g., VSCodeUserSetup-x64-<version>.exe) to run it.
Step 3: Install Visual Studio Code
a.	Read the License Agreement, accept the terms and click Next.
b.	Be sure to check the destination folder where you want to install Visual Studio Code and click Next.
c.	Select additional tasks eg “Add a desktop icon” you would like the installer to perform and click next.
d.	Click Install to begin the installation process.
e.	Wait for the installation to complete, then click Finish.
Step 4: Launch Visual Studio Code
a.	Lunch VS Code and install extensions as needed.

Pre-requisite that might be needed
Hardware Requirements
a.	Processor: 1.6 GHz or faster processor.
b.	Memory: 1 GB of RAM (minimum); 2 GB of RAM or more recommended.
c.	Disk Space: 200 MB to 300 MB of available disk space.

Software Requirements
Windows 7 or better Windows operating system. For the best experience, ensure you are using the latest version of Windows 11.
It is necessary to ensure that .NET Framework installed which is necessary for other languages.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
  
Initial Configurations
Change the theme to suiyr your preference. Popular themes include "Dark+ (default dark)" and "Light+ (default light)".
Sync your settings across devices by enabling Settings Sync. Sign in with your Microsoft or GitHub account.
Set the Font Size and set it to your preferred size. You can also change the font family in the same settings window.
Set the tab size in settings and adjust it to your preferred choice.
Enable Format on Save to ensure your code is formatted each time you save.
Enable auto save to ensure that your updates are automatically saved always.

Extension
Some of the initial extensions to install for a better coding experience include: 
python, 
a. GitLens for enhanced built in Git capabilities, 
b. Prettier for code formatting across various languages,
c. EditorConfiguration to help maintain consistent coding styles between different editors and IDEs,
d. Brackets and Pair Colorizer 2 for colors matching brackets to make code more readable, 
e. Path Intellisense for autocompleting filenames, and  Docker if you will use Docker container for development.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

Visual Studio Code (VS Code) has a well-organized user interface designed to be intuitive and efficient coding. Among the main components of the VS Code nad their purposes are:
a. The Activity Bar:  The vertical bar on the far left side of the window. The Activity Bar provides easy access to various views and functions within VS Code. It contains icons for different activities, such as:  Explorer, Search,  Run and Debug and Extensions.
b. Side Bar:  Directly to the right of the Activity Bar. The Side Bar displays different panels based on the selected activity from the Activity Bar. It provides detailed tools and views, such as: Explorer, Search, Source Control, Run and Debug, and Extensions.
c. Editor Group: The main area in the center of the window. The Editor Group is where you open and edit files. You can have multiple editor groups to view files side-by-side. Key features include: Tabs, Split View and Editor Layout.
d. Status Bar: The horizontal bar at the bottom of the window. The Status Bar displays useful information about the current state of VS Code and the active file. It includes: Language Mode, Encoding, EOL Sequence, Git Branch, Errors and Warnings, Line and Column Numbers and Feedback.

Description
Activity Bar: Quick access to main views and tools. Customize by right-clicking to add or remove icons.
Side Bar: Context-specific panels depending on the selected activity. Toggle visibility with Ctrl+B.
Editor Group: Central workspace for coding, with multiple file tabs and split view support. Use Ctrl+\ to split the editor.
Status Bar: Real-time information about the current file and workspace. Customize by clicking items for more options.
Command Palette:

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

One of Visual Studio Code's most useful features is the Command Palette, which offers instant access to a large number of commands and parameters. It's a fast approach to increase productivity because it lets you do a variety of things without having to go through menus.

Accessing the Command Palette
Keyboard Shortcut: Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Menu Access: You can also access it by clicking on the View menu and selecting Command Palette.

To creat a new file from the Command Palette, Open with Ctrl+Shift+P, type "New File," name it, and press Enter.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

The features of VS Code can be greatly expanded via extensions, creating a development environment that is specifically designed for web development and other uses. The efficient search, installation, and management of these extensions can help developers increase output and optimise workflow.

Users can  find and install Extensions through the view (Ctrl+Shift+X) or the Marketplace.

Click Install in the Extensions view or Marketplace for installation of necessary and preferred extensions..

Managing extensions involves Enabling, disabling, updating, or uninstalling extensions as needed.

Essential Extensions for web development includes Live Server, Prettier, ESLint, JavaScript (ES6) Code Snippets, CSS IntelliSense, Debugger for Chrome, Path Intellisense, GitLens, IntelliSense for CSS class names in HTML, and Bracket Pair Colorizer 2.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

In the VS Code, there are three ways that the integrated terminal can be opened for usage. By the keyboard shortcut : Ctrl+ ` (backtick) on Windows, through the menu bar by going to the top menu bar, selecting Terminal, then choosing New Terminal and through the command pallete through Ctrl+Shift+P to open the command pallete or typing Terminal: Create New Integrated Terminal and then Enter.

Among the advantages of the use of integrated terminal are:
Seamless Workflow

The integrated terminal is built into the IDE, allowing you to code and execute commands in the same environment without switching windows. It also keeps you within the same application, helping to maintain concentration and reducing the cognitive load associated with switching contexts.
Environment Consistency

It enables the sharing of the same environment settings as the IDE, ensuring that paths, environment variables, and configurations are consistent. It also allows the use of the same shell as the external terminal but within the IDE, ensuring compatibility and familiarity.
Ease of Use

It is just a shortcut away, making it very accessible. It also allows allows multiple terminal sessions within tabs or split panels, facilitating multitasking and managing multiple processes.
Integrated Features

It allows for direct interaction with code files, such as running scripts or commands that affect the current project without needing to specify paths. It is directly integrated with the IDE’s error and warning systems, making it easier to see and correct mistakes.
Project Context Awareness

It opens in the context of the current project or file directory, reducing the need to manually navigate to the correct folder and Integrates with build systems and task runners defined within the project, streamlining development processes.

Enhanced Debugging
It works seamlessly with the IDE's debugging tools, making it easier to run and debug applications. It also allows setting breakpoints and watches directly from the terminal while debugging.

Above are some of the advantages of the integration terminal which enables developers to improve their productivity, streamline their workflow, and maintain a more organized and efficient development environment.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

Creating a file can be done on different avenues: Right-click a folder in the Explorer sidebar (Ctrl+Shift+E), select "New File," name it, and press Enter. 

From the Command Palette, Open with Ctrl+Shift+P, type "New File," name it, and press Enter.

For creating a folder, right-click a folder in the Explorer sidebar, select "New Folder," name it, and press Enter.
Opening Files and Folders
Opening a File:

From the Explorer, click the file in the Explorer sidebar.

For Quick Open, Press Ctrl+P, type the file name, select it, and press Enter.

From the Command Palette, Open with Ctrl+Shift+P, type "Open File," navigate, and select.

Opening a Folder:
From the Explorer, click the folder icon in the Explorer sidebar and select the folder.
From the Command Palette, Open with Ctrl+Shift+P, type "Open Folder," navigate, and select.

Managing Files and Folders
Renaming: Right-click the file/folder in Explorer, select "Rename," type the new name, and press Enter.
Deleting: Right-click the file/folder in Explorer, select "Delete," and confirm.
Moving: Drag and drop the file/folder in Explorer or use cut (Ctrl+X) and paste (Ctrl+V).
Navigating Between Files and Directories Efficiently
Quick Open: Use Ctrl+P to quickly open files. Use @, #, or : for specific navigation.
Explorer Sidebar: Use Ctrl+Shift+E to navigate directories.
Breadcrumbs: Enable via View > Appearance > Show Breadcrumbs to navigate directories.
Open Editors: Switch between open files in the "Open Editors" section.
Tabs: Switch between tabs using Ctrl+Tab.
Go to Definition/Declaration: Right-click a symbol, select "Go to Definition" or press F12. Use Alt+F12 for "Peek Definition."
Command Palette: Open with Ctrl+Shift+P to quickly access commands.
Keyboard Shortcuts: Use Ctrl+Shift+O for the file outline and Ctrl+B to toggle the Explorer sidebar.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
  
To assess the setting in VS Code, users can utilize any of the following procedures.
Open the Command Palette (Ctrl+Shift+P) and type "Preferences: Open Settings (UI)" or navigate to File > Preferences > Settings (or Code > Preferences > Settings on macOS

For more advanced configuration, you can edit the settings JSON directly. Open the Command Palette (Ctrl+Shift+P) and type "Preferences: Open Settings (JSON)".

Changing the Theme
Through Settings UI: Open the Settings UI, In the search bar at the top, type "theme", Under "Color Theme," you can select from the list of installed themes.

Through the Command Palette: Open the Command Palette (Ctrl+Shift+P), type "Preferences: Color Theme" and select it, choose a theme from the list that appears.

Changing the Font Size
Through the Settings UI: Open the Settings UI, In the search bar, type "font size", Adjust the "Editor: Font Size" setting to your desired value.

Examples
Change Theme to Dark+:
Through the Settings UI: Search for "theme" and select "Dark+ (default dark)".
Through the Command Palette: Use "Preferences: Color Theme" and select "Dark+ (default dark)".
To Change Font Size to 16: in the Settings UI: Search for "font size" and set "Editor: Font Size" to 16.
To Change Keybinding for New File to Ctrl+Alt+N: Keyboard Shortcuts UI: Search for "New Untitled File," click the pencil icon next to it, and press Ctrl+Alt+N.
    
9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Setting Up and Starting Debugging in VS Code
Download and install VS Code. Install the relevant language extension (e.g., Python, JavaScript).
Create and open a folder for your project in VS Code (File > Open Folder...).
Create a new file and write your code (e.g., app.py for Python).
Open the Run and Debug view (Ctrl+Shift+D). Create a launch.json file and select the appropriate environment.
Click in the gutter next to the line numbers to set breakpoints.
Press F5 or click the green "Start Debugging" button.

Key Debugging Features in VS Code
•	Breakpoints: Set, manage, and conditionally break on specific lines.
•	Step Controls: Step Over (F10), Step Into (F11), Step Out (Shift+F11), and Continue (F5).
•	Watch Expressions: Monitor variables and expressions.
•	Variable Pane: View and inspect local and global variables.
•	Call Stack: See the sequence of function calls.
•	Debug Console: Evaluate expressions and execute commands.
•	Integrated Terminal: Run and debug within the same environment.
•	Exception Handling: Configure breakpoints on exceptions.
 
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   
Integrating Git with Visual Studio Code (VS Code) for version control enhances your development workflow. Here's how to set it up and use it:

Download and install Git from git-scm.com.  Verify installation by running git --version in your terminal.

Open your project folder in VS Code (File > Open Folder...).
Initialize Repository: Go to the Source Control view (Ctrl+Shift+G). Click "Initialize Repository" to create a .git directory.

Open the Command Palette (Ctrl+Shift+P) to clone the repository.

Type Git: Clone, enter the repository URL, and select a folder to clone into.

Basic Git Operations
Stage files by clicking the + icon next to the file or "Changes" in the Source Control view to save changes.

Enter a commit message and click the checkmark icon or press Ctrl+Enter to commit changes.
Push and Pull Changes:
Push: Use the ellipsis (...) in Source Control or Ctrl+Shift+P > Git: Push.
Pull: Use the ellipsis (...) or Ctrl+Shift+P > Git: Pull.
Right-click a file and select View File History to view your history

Integrating Git with VS Code enable the easy management of version control directly within the editor, facilitating easier tracking, collaboration, and codebase maintenance.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

