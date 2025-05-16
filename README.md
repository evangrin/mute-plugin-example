# How to run on Windows Machine #

Follow [this](https://sathira10.medium.com/juce-on-windows-daaacabcf091) tutorial. Some parts may be confusing, so we will give a deeper explanation below.

You following steps have already been done for you, so you may skip them as long as you download the files in this repository and keep them in a convenient folder (maybe C:Projects/mute-plugin-example)
- Set up a new project
- Configure CMake
- Edit the source code
### Explanation for the following warning in the article ###
"Note that the installation doesn’t add the compiler to the global system path. To use MSVC from a command line or VS Code, you must run from the Developer Command Prompt for Visual Studio. It’s installed with the compiler and can be accessed from the Start menu. To verify the installation, type ‘cl’ inside the Developer Command Prompt. You should see a copyright message with the version and basic usage description."

This means that when using VS Code, we should always open it by doing the following:
To launch VSCode
- Go to visual studio installer, and select the 'launch' button next to Visual Studio Build Tools 2022. This will launch a terminal that contains the correct paths for C++ compiler and CMake jazz.
- Once in this terminal, type the following commands
-  'cd ../../Projects/<project_you_are_working_on>' (this takes me to C:Projects/myProject/. It may be a different path for you)
  - 'code .'


