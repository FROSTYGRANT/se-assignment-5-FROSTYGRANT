[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275862&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   ANSWERS:
   a. Open your web browser and go to the Visual Studio Code website.
   b. Click on the "Download for Windows" button. This should automatically detect your system architecture (32-bit or 64-bit) and start downloading the installer.
   c. Once the download is complete, locate the downloaded installer file in your Downloads folder or the location where you saved it.
   d. Double-click the installer file to start the installation process. The installer will launch. You may see a Windows Security warning; click "Yes" to proceed.
   e. The Visual Studio Code Setup wizard will appear. Click on "Next" to continue.
   f. Read and accept the license agreement by checking the box next to "I accept the agreement" then click on "Next".
   g. Choose the destination folder where you want to install Visual Studio Code and click on "Next".
   h. Choose the Start Menu folder where the VS Code shortcuts will be created the click on "Next"
   i. Click on "Install" to begin the installation process. This might take a few moments depending on your system speed.
   j. Once the installation is complete, click on "Finish" to exit the setup wizard.
   k. After installation, you can launch Visual Studio Code from the Start Menu or desktop shortcut.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   ANSWERS:
   a. Install Essential Extensions such as programming language extension specific such as python, flutter, pylance and debuggers.
   b. User preffered settings such as changing the theme, font, git settings and Autosave settings.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   ANSWERS:
   a. Activity bar is located vertically on the far left side of the VS Code window. By default it consists of icons that include items such as Explorer, Search, Source Control, Debug, and Extensions. The Explorer shows the file tree and allows navigation through project files and folders, the search icon provides tools for searching within the current workspace or project, source control integrates Git functionality for managing version control operations, debug facilitates debugging sessions for running and debugging applications and the extensions icon manages extensions, allowing installation, updating, and configuring of additional features for VS Code.
   b. Side Bar is located adjacent to the editor area. It contains additional panels and views that provide context-specific information and tools related to the current activity or file being edited.
   c. Editor Group refers to multiple editor tabs within a single window. This feature allows for users to work on multiple files simultaneously by switching between tabs or splitting the editor into multiple columns. 
   d. Status Bar is located at the bottom of the VS Code window and provides information about the current state of the editor and the project being worked on.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   ANSWERS
   The Command Palette is a tool in VS Code that allows users to quickly access various functionalities without needing to memorize all the keyboard shortcuts or navigate through menus.
   To access it;
   a. Click on View in the menu bar.
   b. Select Command Palette from the dropdown menu.

   Alternatively;
   a. Press Ctrl+Shift+P in Windows and Linux or Cmd+Shift+P in Mac.

   Tasks that can be performed using the command palette
   a. Execute Commands - You can type the name of a command, for example, Format Document, and select it from the list to execute the corresponding action.
   b. Toggle Settings.
   c. Installing Extensions.
   d. Change Theme Color.
   d. Open specific files from your workspace by typing its name.
   e. Navigate Between Files.
   f. Version Control Operations such as Git Pull, Git Commit, Git Push directly from the Command Palette if you have Git integration enabled.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   ANSWERS
   The role of extensions is to extend and customize the functionality of the editor to cater to specific programming languages such as pyrhone, development workflows such as task runners, and personal preferences such as theme and color schemes extensions.

   To find, install and manage the extensions, the user can follow the following procedure;
   a. Open Visual Studio Code.
   b. Click on the Extensions view icon in the Activity Bar on the side.
   c. Search for extensions in the Extensions view on search bar at the top by typing keywords related to the functionality or language support you need, for example, Python.
   d. Once the user finds an extension they want to install in the Extensions view they can click on the extension to open its details page.
   f. Click the "Install" button next to the extension description VS Code will download and install the extension.
   g. To manage an extension, the user can click on the gear icon near the top-right corner in the Extensions view within VS Code, to access extension settings and options. Here the user can disable or uninstall extensions, enable/disable specific features of an extension, update extensions to their latest versions if updates are available and configure settings for each extension.

   Examples of essential extenions for web development;
   a. GitLens - Enhances Git integration within VS Code.
   b. Path Intellisense - Auto-completes file paths in import statements and HTML link/image source attributes.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   ANSWERS
   To open and use the intergrated terminal;
   a. Click on Terminal in the top menu bar.
   b. Select New Terminal

   Advantages of using the integrated terminal compared to an external terminal;
   a. Direct Access - You can easily navigate to files and directories opened in VS Code directly from the terminal, leveraging VS Code's file management features.
   b. Efficiency - Eliminates the need to switch between separate applications for coding and command-line tasks, reducing context switching time.
   c. Quick Access - Opens instantly within VS Code, saving time compared to launching an external terminal window.
   d. Shell Selection - VS Code allows you to choose the shell environment that best suits your needs (e.g., PowerShell, Command Prompt, Git Bash), which can be set globally or per workspace.
   e. Visual Customization - You can customize terminal settings such as font size, color schemes, and cursor styles directly through VS Code's settings.
   f. Task Running - Integrate task runners like npm scripts, gulp tasks, or custom scripts directly within the editor, facilitating build, test, and deployment workflows.
   g. Execute Git commands (e.g., git add, git commit, git push) seamlessly alongside coding tasks without switching contexts.
   h. Debugging Support - Easily run and debug applications or scripts from the integrated terminal using VS Code’s built-in debugging tools.
   i. Live Server Integration - Launch development servers (e.g., npm start, ng serve) with live reload capabilities directly from the integrated terminal.
   j. Consistent Environment - Ensures consistent behavior and environment setup across different development machines, especially useful in team environments where developers share project configurations.
   k. Workspace Specificity - Terminal settings and configurations can be scoped to specific VS Code workspaces, providing flexibility for different projects.
   l. Cross-Platform Compatibility - VS Code and its integrated terminal work seamlessly across Windows, macOS, and Linux platforms, providing a consistent experience regardless of the operating system.
   m. Extension Ecosystem - Leverage VS Code’s extension marketplace to further enhance terminal capabilities with extensions for additional tools, themes, and integrations.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   ANSWERS
   Creating and openiing a New File:
   a. Open VS Code.
   b. Navigate to the Explorer view in the Activity Bar on the side.
   c. Right-click on the parent directory or workspace where you want to create the new file.
   d. Select New File from the context menu.
   e. In the Explorer view, navigate to the directory where your file is located.
   f. Double-click on the file to open it.

   Creating and opening a New Folder:
   a. Right-click on the parent directory or workspace in the Explorer view.
   b. Select New Folder from the context menu.
   c. Give the folder a name when prompted, and press Enter.
   d. Click on File in the top menu bar.
   e. Select Open Folder....
   f. Navigate to the folder, select it, and click Open to open it.

   Managing Files and Folders:
   1. Renaming Files and Folders:
   a. Right-click on the file or folder in the Explorer view.
   b. Select Rename from the context menu (or simply click once on the file/folder name and then click again to edit).
   c. Enter the new name and press Enter.
   
   2. Deleting Files and Folders:
   a. Right-click on the file or folder in the Explorer view.
   b. Select Delete from the context menu.
   c. Confirm the deletion when prompted.

   3. Moving/Copying Files and Folders:
   a. To move or copy files or folders within the Explorer view:
   b. Drag and drop the file or folder to the desired location within the same Explorer view.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   ANSWERS
   To find and customize settings in VS Code:
   Click on the gear icon in the Activity Bar on the side of the VS Code window this icon to open the Settings view.

   To change the Font Size:
   a. Navigate to Editor then Font Size.
   b. Adjust the slider or enter a numeric value to set the desired font size.

   To Change the Keybindings:
   a. Navigate to Keyboard Shortcuts.
   b. Click on the Open Keyboard Shortcuts button at the top-right corner to open the keybindings editor.
   c. Search for and modify existing keybindings or add new ones by clicking on the + button next to a keybinding.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   ANSWERS:
   a. Ensure you have the necessary programming language support and debugger extensions installed in VS Code. For example, if you're debugging JavaScript, ensure you have the Node.js runtime and Debugger for Chrome extension installed.
   b. Create or Open Your Project.
   c. Create or open an Existing Project.
   d. Create a launch.json Configuration.
   e. Open the Command Palette.
   f. Type and select Debug: Open launch.json.
   g. Choose the environment for your program (e.g., Node.js, Chrome, Python), VS Code will generate a basic launch.json configuration file in a .vscode folder in your project.
   h. Modify the launch.json file to specify details such as program entry points, arguments, environment variables, etc., depending on your debugging needs.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    To intergrate Git with VS Code for version control;
    a. Open your project folder in VS Code
    b. Open the integrated terminal in VS Code (`Ctrl+``) and navigate to your project directory.
    c. Run git init to initialize a new Git repository.
    d. 

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

