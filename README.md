# Night-Friendly Visual Studio Code Theme

### **Overview**
This custom theme is designed for developers working in low-light environments, offering a dark bluish-gray base and muted accent colors. It reduces eye strain and ensures readability while maintaining a cohesive and aesthetic design.

---

### **Features**
- **Night-Friendly Design**: Ideal for extended work hours.
- **Custom UI Elements**: Includes editor, tab bar, sidebar, activity bar, status bar, and title bar.
- **Cohesive Styling**: Muted tones and bluish accents for a balanced visual experience.

---

### **Installation Instructions**

#### **Method: Copy-Paste (Quick and Simple)**

1. **Open the Settings JSON File**:
   - Open Visual Studio Code.
   - Navigate to `File > Preferences > Settings`.
   - In the settings window, click the small **file icon** in the top-right corner to open `settings.json`.

2. **Copy and Paste**:
   - Copy the code below and paste it into the `settings.json` file:
   ```json
   {
       "workbench.colorCustomizations": {
           "editor.background": "#10161F",
           "editor.foreground": "#C8C8C8",
           "editorCursor.foreground": "#B0C4DE",
           "editor.lineHighlightBackground": "#1A212A",
           "editor.selectionBackground": "#222C36",
           "editorIndentGuide.activeBackground": "#374455",
           "editorBracketHighlight.foreground1": "#4E5D6A",
           "editorBracketHighlight.foreground2": "#6B8099",
           "editorBracketHighlight.foreground3": "#8FA5B8",
           "editor.tag.foreground": "#C08170",
           "editor.attribute.foreground": "#A1B8E3",
           "editorGroupHeader.tabsBackground": "#10161F",
           "tab.activeBackground": "#10161F",
           "tab.activeForeground": "#D4D4D4",
           "tab.inactiveBackground": "#0E141A",
           "tab.inactiveForeground": "#6D6D6D",
           "tab.hoverBackground": "#192530",
           "tab.border": "#243845",
           "sideBar.background": "#0E141A",
           "sideBar.foreground": "#C8C8C8",
           "activityBar.background": "#10161F",
           "activityBar.foreground": "#D4D4D4",
           "statusBar.background": "#10161F",
           "statusBar.foreground": "#C8C8C8",
           "titleBar.activeBackground": "#10161F",
           "titleBar.activeForeground": "#C8C8C8"
       }
   }
