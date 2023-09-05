# rofi-firefox-bookmark
A simple shell plugin for rofi to search from your bookmarks and open them either in a new tab or a new window. 

## install notes:
Make sure to have the some forms of the following lines for the plugin to work. 
```css
configuration {
  modi: "bookmark:/path/to/file.sh";
  kb-custom-1: "Shift+Return";
  kb-accept-alt: "Alt+1";        
}
```
bookmark.sh's UI states "Shift+Return" will open a new window, but this is bound to a keybinding unaccessable in shell plugins. the simple workaround is to just bind it to something else and use that instead.
