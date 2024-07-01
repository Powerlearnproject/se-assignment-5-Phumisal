[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15297244&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Step 1
   I went to the official VS Code download page by following the link https://code.visualstudio.com/download

   Step 2
   Once I landed on the VS Code official site, I clicked on the download button for Windows.

   This started the download of the installer executable file.

   Step 3
   To run the downloaded installer, I first located the downloaded file in my Downloads folder of my local machine, the I double-clicked the installer executable to run it.

   Step 4. 
   I accepted the Terms and Conditions by following the installation prompts and accepting the license terms and privacy statement,

   Step 5. 
   I clicked "Next" and the clicked on "Install" and VS Code was evidently installed on my machine. 

   Step 6. 
   Upon successful download and installation of VSCOde on my sytem, I the clicked the "Launch" button to open the VSCode Application on my machine. 

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   i. Upon installing VSCode I adjusted the initial   configurations and settings by installing useful extensions based on the programming language and workflow I was going to use in this case Python, Dart SDK, Flutter, MYSQL and Git environments.

   ii. Adjusted some important settings including Files, Editors, Font and Workbench

   iii. I then set up my preferred shell, in this case it being Git Bash and Command Prompt in the integrated terminal.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Activity Bar:
Located on the side (usually on the left), the Activity Bar provides quick access to different functionalities:
Explorer: Navigates your project files and folders.
Search: Allows you to search across files.
Source Control: Integrates with Git for version control.
Extensions: Manages VS Code extensions.
Run and Debug: Helps you run and debug your code.

   Side Bar:
Adjacent to the Activity Bar, the Side Bar contains panels:
Explorer: Displays your project’s file structure.
Source Control: Shows Git-related information.
Extensions: Lists installed extensions.
Outline: Provides an overview of symbols in the current file.
Debug: Helps with debugging tasks.

   Editor Group:
The central area where you write and edit code.
You can split it into multiple columns (editor groups) for side-by-side editing.
Each editor group can have different files open.

   Status Bar:
Located at the bottom, the Status Bar provides essential information:
Line and Column Numbers: Shows your cursor position.
Language Mode: Indicates the programming language of the current file.
Git Branch: Displays the active Git branch.
Errors and Warnings: Alerts you to issues in your code.
Extensions: Shows installed extensions’ status.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows you to access various features, commands, and settings directly via keyboard shortcuts or a menu. To open it:

   - Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
   - Alternatively, use the F1 key.
   - You can also access it from the Application Menu by clicking View > Command Palette.

   Examples of common tasks that can be performed using the command pallette include the following :

      o  Changing Themes: Search for “Color Theme” to switch between different themes.

      o  Running Tasks: Type “Run Task” to execute predefined build or test tasks.

      o  Installing Extensions: Search for “Extensions: Install Extensions” to add new functionality.

      o  Formatting Code: Use “Format Document” to automatically format your code.

      o  Changing Language Mode: Search for the language you’re working with (e.g., “Change Language Mode to Python”).

      o Customizing Keybindings: Type “Preferences: Open Keyboard Shortcuts” to modify shortcuts.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   VSCode extensions personalize the User's workflow and play a crucial role in enhancing the development environment. They allow the user to add languages, debuggers and tools, extending VSCode beyond it's default capabilities. 

   A. Finding Extensions:
   
   The User can find extensions by following these steps:

   i. Open VSCode and click on the Extensions icon in the Activity Bar OR by using the shortcut Ctrl+Shift+X

   ii. Browse the VSCode Marketplace to discover extensions.

   iii. The User can also search for specific extensions by name or functionality on the internet.

   B. Installing Extensions:

   Once you find an extension, click the “Install” button. After installation, the button changes to “Manage. Some popular extensions include:

      o JavaScript (ES6) Code Snippets:
         Provides code snippets for JavaScript, TypeScript, Vue, React and HTML5.

      o CSS Peek: 
         This allows the User to jump to CSS code using classes and IDs.

      o Auto Close Tag:
         This automatically adds closing tags for HTML and XML.

      o REST Client: 
         Used to test API's directly within VSCode.

      o ESLint:
         A linting utility for JavaScript.

   C. Managing Extensions:

      o The User can use the Extensions view to enable, disable, update or uninstall extensions.

      o The User can explore other useful extensions like Live Server, GitLens, and Intellisense for CSS class names in HTML.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   a) For Windows OS, the User can Open the Integrated Terminal by either 

   i. Pressing Ctrl+ to toggle the terminal panel

   OR 

   ii. Using the dropdown menu (View > Terminal) 

   b) Running Commands:

      - Once the terminal is open, User can execute commands just like in a standalone terminal and Run common tasks (e.g., mkdir, git, etc.) directly from the integrated terminal.

   c) Advantages of the Integrated Terminal:

      o Seamless workflow: VS Code provides a Seamless Workflow, the User does not need to switch between VS Code and any other external terminal; everything is in one place.

      o Context Awareness: The integrated terminal starts at the root of your workspace, making it context-aware.

      o Links and Error Detection: VS Code integrates with the editor, thus supporting features like clickable links and error highlighting.

      o Shell Integration: With Shell Integration VS Code tracks where commands are run, providing additional information and decorations.

   d) External Terminal:
      Should the user want to use an external terminal, they can open it using Ctrl+Shift+C for users of Windows OS.
   

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   a) In creating Files and Folders:

      o Use the Explorer View (accessible via the sidebar) to manage files and folders.

      o Click the New File button (envelope icon with a + sign) to create a new file.

      o Click the New Folder button (folder icon with a + sign) to create a new folder. 

   b) Opening Files and Folders:

      o To open an existing folder, use the File > Open Folder command.
      
      o You can also use the File > Add Folder to Workspace command to add multiple folders to your workspace2.

      o Double-click a file in the Explorer to open it.

   c) Navigating Efficiency:

      o Use Explorer to browse files and folders.

      o For Windows 11 OS, the User can quickly switch between open files using Ctrl+Tab.

      o The User can use Breadcrumbs at the top of the file editor to navigate within a file.

      o To open the Quick Open dialogue and search for files by name, the User can Press Ctrl+P.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   The User can customize and VS Code settings through the Settings Editor by following the steps below:

   i. Open the Settings Editor:
      
      -  Navigate to File > Preferences > Settings.
      - Alternatively, use the Command Palette (Ctrl+Shift+P) and search for Preferences: Open Settings

   ii. User Settings:

      - Apply globally to all projects.
      - Change the Color Theme to personalize the appearance.
      - Adjust the Font Size under “Editor: Font Size” setting.
      - Modify Keybindings by searching for “Keybindings” in the settings

   iii. Workspace Settings:

      - Apply only to the current project.
      - Customize settings specific to your workspace.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   The following steps must be followed in debugging a simple program in VS Code.

   Step 1.

   The User must create a Sample Application e.g. 

      o First, create a simple application (e.g., a Node.js app) in your workspace. You can follow the Node.js walkthrough to set up a basic “Hello World” JavaScript application (e.g., app.js)

   Step 2.

   Open the Run and Debug View:

      o User to Open the Run and Debug icon in the Activity Bar on side of VS Code.

      o Alternatively, User can use the keyboard shortcut Ctrl+Shift+D on Windows 11 OS.

   Step 3.
   
   Configure Launch Settings:

      o If the file, "launch.json", which stores the debugging configuration doesn't exist, VS Code will show the Run start view.

      o To create a "launch.json" file, select “create a launch.json file” in the Run start view.

      o VS Code will try to detect your debug environment automatically, but you can choose it manually if needed.

      example :

      {
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "skipFiles": ["<node_internals/**>"],
      "program": "${workspaceFolder}/app.js"
    }
  ]
}

Source : AI-generated code

   Step 4.

   Run and Debug

      o User can Press F5 or click the Run button to start debugging.

      o VS Code will run your currently active file (or the one specified in launch.json).

   Step 5. 

   Breakpoints and Inspecting Variables: 

      o Set breakpoints by clicking the gutter next to a line of code.

      o While debugging, inspect variables, view call stacks, and evaluate expressions.

      o Use the Watch panel to monitor specific variables.

   Step 6. 

   Other Debugging Features:

      o Conditional Breakpoints: Set breakpoints based on conditions.
      
      o Logpoints: Add log messages without stopping execution.

      o Step Over, Step Into, and Step Out: Navigate through code during debugging.

      o Exception Handling: Configure how exceptions are handled.
NB : VS Code’s built-in debugger accelerates your edit-compile-debug loop, making it easier to find and fix issues!

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   The process of integrating Git with VS Code for version control, including initializing a repository, making commits, and pushing changes to GitHub is as follows:

   Step 1.
   Install Git and Set Up GitHub Account:

   o Ensure you have Git installed on your machine.

   o Create a GitHub account if you haven’t already.

   Step 2.
   Open Your Project in VS Code:

   o Open your project folder in VS Code.

   Step 3. 
   Initialize a Local Git Repository:

   o Go to the Source Control view (click the icon on the left or use Ctrl+Shift+G).
   
   o Click the “Initialize Repository” button to create a new Git repository in your project folder.

   Step 4. 
   Stage and Commit Changes:

   o In the Source Control view, you’ll see any changes you’ve made.

   o Select the files you want to include in the commit.

   o Enter a descriptive commit message.

   o Click the checkmark icon to commit your changes.

   Step 5. 
   Create a GitHub Repository:

   o Go to GitHub.com and create a new repository.

   o Copy the repository’s URL.

   Step 6.
   Push Changes to GitHub:

   o Back in VS Code, click the ellipsis (…) in the Source Control view.

   o Select “Pull/Push” and then choose “Push to…”

   o Click “Add Remote” and paste the GitHub repository URL.

   o Push your code to GitHub by clicking “Publish Branch.”

   Step 7. 
   Verify on GitHub:

   o Refresh your GitHub repository page in the browser to see your code there.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

