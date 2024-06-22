[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15266888&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   ----Ensure your device has enough space and conveniently connected to internet.
   ----Then visit the Visual Studio Code download page i.e. https://code.visualstudio.com from your browser e.g chrome, Firefox e.t.c.
   ----Navigate through and find the windows section and click on the download button to get the installer. select the drive where you want the setup file to be stored and then save it.i.e. VSCodeUserSetup-x64-1.90.1
   ----Once downloaded, locate the installer in your system from the previous selected drive and double click it to run it.
   ----Follow the on screen-instructions to install VS Code 
   ----After installing you can find your VS Code icon on your desktop. 
   ----Then double click on it to launch the application.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   ---- modify the layout, theme and font basising on your conveniency in File > preferences > settings or you can use the shortcut Ctrl + ,
   ---- Setup your preferred terminal by navigating to Terminal > select Default Shell. In my case i chose git bash.
   ---- Install essential extensions like better comments, bookmarks, Code Spell Checker, CodeSnap, CodiumAI, Error Lens, GitLens, GitHub Copilot, Icon Themes e.t.c for enhanced functionatlity and productivity.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   ----Bar: Contains file, edit, selection, view, go, debug, terminal, help e.t.c
   ---Side Bar: It displays the icons for explorer, search, source control, debug and extensions
   ----Editor Group: This is the main area where your code files are openned and edited.
   ----Status Bar: It is located at the bottom, it displays the current status of the workspace, file path, line, and column numbers, notifications etc
   **Other components include
   ----Title Bar: It displays the name of the file, name of the application and the minimise, maximize and close buttons
   ----Activity Bar: It is located at the left side which provides access to views like the explorer, search, source control, debug and extensions
   ----Tabs: Located above the editor group, they allow you switch between open files easily.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
---- A command palette is where all commands are found. It is therefore incumbent that your command names are labelled appropiately so as to access them with ease.
---- It can be accessed through Ctrl+shift+P (for windows and linux operating systems) and Cmd+shift+P (for unix operating system).
---- Tasks that can be performed using Command palette include;
    --Open a terminal and run a command in the terminal
    --Debugging
    --Switch the language mode for the active editor
    --Navigate to specific symbol or function in the current file.
    --Observe problems in the current file.
    --Access code actions like refactoring or formatting code
    --Quick open of files, and 
    --Navigate to the settings to modify your code editor e.t.c
    --Enables you search for and execute any command provided by VsCode.
5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   ---- The extensions enables you to add languages, debuggers and tools to your installation to support your development work flow. It also provides setting for tunning its behaviour which you can find the settings Editor.

   ---- Once you open the VS Code, to find the extensions you can press a shortcut Ctrl + shift + x, then type in the search box for the extension of your choice. To install an extension, select the install button and once installation is complete, the install button will change to the manage gear button. To manage the extensions, you can install, disable, update, unistall extensions through the extensions view, the command palette or command-line switches

   ---- The essential extensions include:- Dart, flutter, python, GitLens, Intellicode, Roslynator, CodeMaid, visual Assit. etc

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
----From the menu, use the Terminal > New Terminal or View > Terminal menu commands.
----From the Command Palette (Ctrl+Shift+P), use the View: Toggle Terminal command.
----In the Explorer, you can use the Open in Integrated Terminal context menu command to open a new terminal from a folder.
----To toggle the terminal panel, use the Ctrl+` keyboard shortcut.
----To create a new terminal, use the Ctrl+Shift+` keyboard shortcut.

The advantages of using the integrated terminal compared to an external terminal
----The integrated terminal, provides integration with the editor to support features links abd error detection.
---- It can run commands such as mkdir (to make a directory) and git.
---- It has additional functionality called shell integration which tracks where commands are run with decorations on the left of a command and in the scroll bar.
---- It can use various shells installed on the machine with the default being pulled from your system defaults.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
---- To create, open, and manage files and folders in Visual Studio Code (VS Code):
   --Create a new file: Click File > New File or press Ctrl + N.
   --Open an existing file: Click File > Open File or press Ctrl + O.
   --Create a new folder: In the Explorer view, right-click and select New Folder, or press Ctrl + Shift + N.
   --Open a folder: Click File > Open Folder or press Ctrl + K followed by Ctrl + O.
   --Manage files/folders: Use drag-and-drop, F2 for renaming, Delete for deleting, and right-click for additional options.
   --Remember to save your work regularly by clicking File > Save or pressing Ctrl + S.

----Users can efficiently navigate between different files and directories in VS Code using the following features:
   --Explorer view: Access the Explorer view (left sidebar) to see the file structure and navigate to different files and directories.
   --Go to File: Press Ctrl + P to open the Go to File dialog, where you can quickly type the file name to navigate.
   --Go to Symbol in File: Press Ctrl + Shift + O to navigate quickly within the currently active file.
   --Go to Line: Press Ctrl + G to navigate to a specific line in the currently active file.
   File navigation history: Use Ctrl + Tab to cycle through recently opened files.
   --Workspaces: Create and manage workspaces to group related files and directories together for easy navigation.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   ---- Users can find and customize settings in VS Code from the settings editor.

   ---- OPen your VS Code using the icon on your desktop, navigate to the command palette using a shortcut ctrl + shift + P.
   ---- once your search bar pops up, type either themes, font size and keybindings of your choice then you can execute the changes appropiately.
   ---- Then enter to apply the changes made.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   ---- To run or debug a simple prgram in VS Code, select Run and Debug on the Debug start view or press F5 and VS Code will try to run your currently active file. However, for most debugging scenarios, creating a launch configuration file is beneficial because it allows you to configure and save debugging setup details. VS Code keeps debugging configuration information in a launch.json file located in a .vscode folder in your workspace (project root folder) or in your user settings or workspace settings.
   ---- To create a launch.json file, select create a launch.json file in the Run start view.
   ---- VS Code will try to automatically detect your debug environment, but if this fails, you will have to choose it manually.
   ---- If you go back to the File Explorer view (Ctrl+Shift+E), you'll see that VS Code has created a .vscode folder and added the launch.json file to your workspace.

   ---- Debugging features include:- python debugger, PHP Debug, Debugger for Java, Debugger for FireFox. And many others

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    ---- To integrate Git with VS Code for version control
--First, install Git on your system if you haven't already. You can download it from the official Git website.
--Open Visual Studio Code (VS Code).
--Install the Git extension from the VS Code marketplace. You can find it by searching "Git" in the search bar.
--After installing the extension, open your terminal in VS Code (View > Terminal).
--In the terminal, run git init to initialize a new Git repository in your project folder.

    ---- To initialize :
--Pick an existing or new folder on your computer and open it in VS Code.
--In the Source Control view, select the Initialize Repository button.
--This creates a new Git repository in the current folder, allowing you to start tracking code changes.
--This action is equivalent to running git init on the command-line.
    ---- To make commits, and pushing changes to GitHub.
--Access the Source Control view from the Activity Bar to list all changed files in your workspace. 
--Select a file in the Source Control view, the editor shows a diff view that highlights the file changes, compared to the previously committed file.
--To stage a file, select the + (plus) icon next to the file in the Source Control view. This adds the file to the Staged Changes section, indicating that it will be included in the next commit.
--To commit your staged changes, type a commit message in the upper text box, and then select the Commit button. This saves your changes to the local Git repository, allowing you to revert to previous versions of your code if needed.
--Once you have made commits to your local Git repository, you can push them to the remote repository.
--You can push individually by using the respective commands. You can access these commands from the Source Control menu.
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

