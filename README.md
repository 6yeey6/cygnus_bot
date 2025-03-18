Operation Method:
Press F12, select Console: Paste the entire code into the console and press Enter. Then, a control module will appear on the page (which can be dragged with the mouse). Input the interval time you want to set (1 second = 1000ms), and click Start.

Function Description
This is an auto-clicker script (persistent version), primarily used to simulate mouse click operations on web pages. It can automatically click within a specified game area with random offsets and set the click interval and on/off state through a draggable control panel. The script supports the following features:
- Automatic game area positioning: Locates the click area through background images, specific styles, or default center coordinates.
- Click simulation: Randomly clicks within the target area, displaying red dot prompts.
- Persistent settings: Saves click interval, running state, and control panel position via localStorage, automatically restoring them after page refresh.
- Control panel: Provides an input box to set the click interval (in milliseconds) and a "Start/Stop" button, supporting drag-and-drop position adjustment.
- Automatic recovery: Detects page refresh or script removal and automatically reloads and resumes operation.

Operation Method
- Install the script:
  Paste the code into the browser's Developer Tools (F12) under "Console" and press Enter to execute, or load it via a user script manager (e.g., Tampermonkey).
- Use the control panel:
  After execution, a black control panel will appear in the top-right corner of the page.
  - Input box: Enter the click interval time (in milliseconds, minimum 100).
  - Button: Click "Start" to initiate auto-clicking, and click again to "Stop" pausing.
  - Drag: Hold and drag the blank area of the control panel to adjust its position.
- Observe clicks:
  During operation, red dots will randomly appear within the game area, indicating the simulated click positions.
- Persistent effect:
  Settings and running state are automatically saved. After refreshing the page, the script will reload and restore the previous state.
- Stop the script:
  Close the page or manually remove the control panel (by deleting the #auto-clicker-panel element via Developer Tools).

Suitable for web games or task scenarios requiring repeated clicks.


操作方法：
按F12，选择控制台：将代码整段粘贴到控制台回车，然后页面出现的控制模块（可以鼠标拖动），输入你想设定的间隔时间1秒=1000ms，点击开始。

功能描述
这是一个自动点击器脚本（持久化版本），主要用于在网页上模拟鼠标点击操作。它可以在指定游戏区域内以随机偏移的方式自动点击，并通过一个可拖动的控制面板设置点击间隔和开关状态。脚本支持以下功能：
自动定位游戏区域：通过背景图、特定样式或默认中心坐标定位点击区域。

点击模拟：在目标区域内随机点击，显示红点提示。

持久化设置：通过 localStorage 保存点击间隔、运行状态和控制面板位置，页面刷新后自动恢复。

控制面板：提供输入框设置点击间隔（单位：毫秒），以及“开始/停止”按钮，支持拖动调整位置。

自动恢复：检测页面刷新或脚本移除后，自动重新加载并恢复运行。

操作方法
安装脚本：
将代码粘贴到浏览器的开发者工具（F12）中的“控制台”（Console）并回车执行，或通过用户脚本管理器（如 Tampermonkey）加载。

使用控制面板：
执行后，页面右上角会出现一个黑色控制面板。

输入框：输入点击间隔时间（单位：毫秒，最小值 100）。

按钮：点击“开始”启动自动点击，再次点击“停止”暂停。

拖动：按住控制面板空白区域拖动，调整其位置。

观察点击：
运行时，红点会在游戏区域内随机出现，表示模拟点击的位置。

持久化效果：
设置和运行状态会自动保存，刷新页面后脚本会重新加载并恢复之前的状态。

停止脚本：
关闭页面或手动删除控制面板（通过开发者工具移除 #auto-clicker-panel 元素）。

适用于需要重复点击的网页游戏或任务场景。

