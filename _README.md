# Workflow for Managing Pub.dev Packages

This workflow simplifies the management of your pub.dev packages. It automatically updates the CHANGELOG.md, formats the Dart code, and applies Dart fixes with each commit. Additionally, it automates the publication of your package to pub.dev whenever a GitHub release is created.

## Setup Instructions

**1. Navigate to your project:**

```zsh
cd your_project
```

**2. Clone this repo into a `.github/` folder:**

```zsh
git clone https://github.com/robmllze/pub.dev_package_workflow.git .github
```

**3. Remove the `/.git` folder to include it to your project:**
   
*On macOS and Linux:*
```zsh
rm -rf .github/.git/
```

*On Windows:*
```cmd
rmdir /s /q .github/.git/
```


