这是草稿。请随时帮助复查本教程

---

这篇简短的教程将指导您使用NVDA屏幕阅读器在MuseScore中输入音符的过程。如果你是一个刚接触MuseScore的屏幕阅读器用户，而且你还没有读过关于[用NVDA在MuseScore中创建新乐谱](https://musescore.org/en/node/113581)的教程，建议你先读一下这个教程。

本教程假设你有MuseScore 3.5.0或以上版本，并安装了[NVDA 2016.1](http://www.nvaccess.org/download/) 或以上版本。如果你有盲文显示器，建议你也使用这个。

### 准备输入音符

在MuseScore中打开一个新的乐谱，确保将重点放在您希望开始输入音符的地方。如果你想从乐谱的开头开始，请按 <kbd><kbd>Ctrl</kbd>+<kbd>Home</kbd></kbd>。或者用 <kbd><kbd>Ctrl</kbd>+<kbd>F</kbd></kbd> 调出一个对话框，在那里你可以输入小节数。

为了在乐谱中输入音符，你必须首先切换到音符输入模式。你可以通过按 <kbd><kbd>N</kbd></kbd>键来实现。这是一个切换功能，因此再次按 <kbd><kbd>N</kbd></kbd> 键或按 <kbd><kbd>Esc</kbd></kbd> 键将退出音符输入模式。 

注意，NVDA目前不会确认进入或退出音符输入模式。你可以用 <kbd><kbd>Alt</kbd>+<kbd>N</kbd></kbd> 进入音符菜单，其中第一项是音符输入，来检查这一点。如果这是活动的，NVDA将宣布 "已检查"，如果不是，则不宣布。有视力的用户会看到在音符输入模式下，一个闪烁的光标出现在谱表的左边。

### 选择音符/休止符的持续时间

在输入音符和休止符之前，MuseScore需要知道它们的持续时间。这可以通过使用数字行或数字键盘来选择。1给出了最短的半音符（64分音符）的长度，每一个数字都会使其长度增加一倍，最多8个数字为双音符。5给出一个四分音符（crotchet）。按句号（点）可以在一个音符上增加一个持续时间点。再按一次就会去掉持续时间点。所有随后输入的音符和休止符的长度都是一样的，直到你改变它。

请注意，NVDA仅在不处于音符输入模式时才会宣布所选的持续时间。

如果您选择的持续时间长于当前小节中的剩余空间，MuseScore将用可能的最长持续时间填充该小节。

### 选择音高

打开音符输入模式后，C、D、E、F、G、A、B这些音符可以用qwerty键盘上相对应的键输入。MuseScore会输入与前一个音符的音高最接近的音符。输入后，你可以：

*   通过按 <kbd><kbd>Up</kbd></kbd> and <kbd><kbd>Down</kbd></kbd> 箭头，将音符上下移动一个半音。
*   通过按 <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Up</kbd></kbd> 和 <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Down</kbd></kbd>键仅使用调号中的音符上下移动移动音符。
*   通过按 <kbd><kbd>Ctrl</kbd>+<kbd>Up</kbd></kbd> and <kbd><kbd>Ctrl</kbd>+<kbd>Down</kbd></kbd>移动音符一个八度。

要选择和声等音，请使用字母 <kbd>J</kbd>。这将改变选定的音符，例如，升C和降D之间。

按 <kbd><kbd>0</kbd></kbd>，输入当前选择的休止符。

要重复输入的最后一个音符或休止符，请按 <kbd><kbd>R</kbd></kbd>。

如果您犯了错误，最好通过按 <kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd></kbd> 使用**撤销**，或者简单地将箭头指向错误的音符并更正它。

### 乐谱导航

一旦你在乐谱中输入了音符，你可以使用 <kbd>Left</kbd> 和 <kbd>Right</kbd> 方向键在音符或休止符间移动。使用 <kbd><kbd>Ctrl</kbd>+<kbd>Right</kbd></kbd> 和 <kbd><kbd>Ctrl</kbd>+<kbd>Left</kbd></kbd> 向前和向后移动一小节的时间。 

要在不同的声部和谱表之间移动，按 <kbd><kbd>Alt</kbd>+<kbd>Up</kbd></kbd> 和 <kbd><kbd>Alt</kbd>+<kbd>Down</kbd></kbd>。

当你移动你的分数时，屏幕阅读器会给出你所导航到的音符或休止符的详细信息。

### 乐谱播放

要演奏你的乐曲，请按 <kbd>Space</kbd>键。再次按 <kbd>Space</kbd> 键停止。

### 更改已输入的音符/休止符的持续时间

在关闭音符输入模式的情况下，箭头指向要改变的音符或休止符。然后用数字行选择持续时间。如果你选择一个较长的音符或休止符，这将覆盖小节中已有的音符/休止符。如果你选择一个较短的音符/休止符，将增加额外的休止符来完成该小节。

### 输入和弦

要输入一个和弦(两个或更多的音符，相同的持续时间)，输入第一个音符，然后在按下 <kbd><kbd>Shift</kbd></kbd> 键的同时输入和弦中剩余的音符。你输入的第一个音符将是和弦中最低的音符。

### 在声部中工作

两个或更多独立的部分被印在一个谱表上，这些被称为“声部”。当工作在一个有两个或更多声部的乐谱，输入第一个声部为一个完整的小节。按 <kbd><kbd>Esc</kbd></kbd> 键退出音符输入模式。将焦点放在声音1的第一个音符上，按 <kbd><kbd>N</kbd></kbd> 进入音符输入模式，然后按 <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>2</kbd></kbd> 选择声部2并输入声部2的音符。你可以使用 <kbd><kbd>Alt</kbd>+<kbd>1</kbd></kbd>, <kbd><kbd>Alt</kbd>+<kbd>2</kbd></kbd> 等在声部之间循环。

### 删除音符/休止符

有几种方法可以删除不再需要的笔记。 在Musescore中， <kbd><kbd>Backspace</kbd></kbd>, <kbd><kbd>Del</kbd></kbd> 和 <kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd></kbd> 保留其标准Windows功能。

### 补充资料

MuseScore帮助菜单中的在线手册提供了在MuseScore中工作的全面细节。