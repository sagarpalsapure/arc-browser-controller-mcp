Arc Browser Controller DTX Extension

A comprehensive Arc Browser automation extension that provides AppleScript-powered tools to control Arc Browser programmatically through Claude Desktop.

Features

Core Browser Control
- Open URLs: Open any URL in specified Arc spaces
- Tab Management: Create, close, and switch between tabs
- Space Navigation: Switch between different Arc spaces
- Window Control: Manage Arc browser windows

Advanced Automation
- JavaScript Execution: Run custom JavaScript in active tabs
- Tab Information: Get detailed info about current and all tabs
- Search Integration: Perform searches using different search engines
- Navigation Controls: Back, forward, and reload functionality

Smart Features
- Auto-launch: Automatically starts Arc if not running
- Space-aware: Operates within specific Arc spaces
- Error Handling: Robust error handling and logging
- Configurable: User-configurable default spaces and logging

Requirements

- macOS only (AppleScript dependency)
- Arc Browser installed and accessible
- Node.js 16+ (bundled with Claude Desktop)
- Claude Desktop with DTX support


Install in Claude Desktop
- Double-click the generated .dxt file
- Configure your preferences (default space, logging)

Available Tools

1. open_url_in_arc
Open a URL in Arc Browser in a specific space.

Example: "Open https://github.com in my Work space"

2. get_current_tab_info
Get information about the current active tab in Arc.

Example: "What's the current tab information?"

3. switch_arc_space
Switch to a specific space in Arc Browser.

Example: "Switch to my Personal space in Arc"

4. create_new_tab
Create a new tab in Arc Browser.

Example: "Create a new tab and open Wikipedia"

5. close_current_tab
Close the current active tab in Arc.

Example: "Close the current tab"

6. execute_javascript
Execute JavaScript in the current Arc tab.

Example: "Execute JavaScript to scroll to the top of the page"

7. get_all_tabs
Get information about all open tabs in Arc.

Example: "Show me all open tabs in Arc"

8. search_in_arc
Perform a search in Arc Browser.

Example: "Search for 'AppleScript tutorials' using DuckDuckGo"

9. navigate_tab
Navigate current tab back, forward, or reload.

Example: "Go back to the previous page"

10. focus_tab_by_index
Focus a specific tab by its index in the current space.

Example: "Focus on the third tab in my Work space"

Configuration

The extension supports the following user configuration options:

- Default Space: The Arc space to use by default (e.g., "Personal", "Work", "General")
- Enable Logging: Enable detailed logging for debugging purposes
