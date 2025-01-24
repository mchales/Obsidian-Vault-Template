# Obsidian Vault Template

This is the folder structure of my Obsidian Vault (inspired by [CyanVoxel](https://www.youtube.com/watch?v=rAkerV8rlow)). The focus of this vault is on knowledge organization, management, and retrieval.

Be sure to review all plugins before using this template.

## How to Use

1. Follow the instructions in **`00 - Maps of Content > Methodology`**.
2. Modify the structure and content to suit your personal workflow.

## Folder Highlights

### **`00 - Maps of Content`**

This folder contains the core methodology and organizational structure for your vault. Start here to understand the system.

### **`09 - Reference > Obsidian`**

Includes references and simple guides to help you modify and customize this vault effectively.

### **`99 - META > 00 - Templates`**

This folder contains templates designed for the [Templater](https://github.com/SilentVoid13/Templater) plugin. Basic templates are included for quick setup.

## Sidebar Customization

To modify the sidebar appearance:

1. Navigate to **Settings > Appearance > CSS Snippets > Colored Sidebar Items**.
2. Within the CSS file:
   - `:root` contains the dark mode color options.
   - `.theme-light` contains the light mode color options.
3. Edit the file directly and ensure the snippet is enabled.

## Enabling Git

To enable Git for this vault, activate the **Obsidian Git** plugin. This allows you to version-control your notes and maintain backups.

Here is an example `.gitignore` file you can use:

```
.DS_Store
.obsidian/appearance.json
.obsidian/workspace.json
daily notes/
.trash/
.obsidian/plugins/recent-files-obsidian/data.json
```
