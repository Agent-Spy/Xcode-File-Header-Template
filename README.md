# File-Header-Template

This repository contains a file header template for Xcode projects under the Agent Spy organization. This template helps maintain consistent file headers across all projects and improve code documentation.

## Installation

### 1. Clone Repository
```zsh
git clone https://github.com/Agent-Spy/File-Header-Template.git
```

### 2. Copy Template File
If your project has a workspace, use the workspace level path; otherwise, use the project level path:

#### Project Level
```zsh
cp Sources/IDETemplateMacros.plist <ProjectName>.xcodeproj/xcshareddata/IDETemplateMacros.plist
```

#### Workspace Level
```zsh
cp Sources/IDETemplateMacros.plist <WorkspaceName>.xcworkspace/xcshareddata/IDETemplateMacros.plist
```

#### Note
You may need to create the `xcshareddata` folder if it doesn't exist. You can do this through Finder by right-clicking on the `.xcodeproj` or `.xcworkspace` file and selecting "Show Package Contents", or via command line.

## Usage

1. Choose the appropriate installation location from above based on your needs:
   - Use workspace level if your project has a workspace
   - Use project level for standalone projects
2. Copy the template file to your chosen location

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE.md) file for details.

## Contributors

See [CONTRIBUTORS](CONTRIBUTORS.md) for a list of the project contributors.