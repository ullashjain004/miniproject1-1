# VI(Visual Editor) Walkthrough

VI is a screen-oriented text editor originally created for the Unix operating system. Following are the commands for vi to get started.

## Open a file using vi

Open **Terminal** app & type `vi filename` file that you want to edit

![Image of opening a file in vi](https://github.com/ds997/miniproject1-601-ds/blob/master/resources/Enable-vi-mode.png)


## Operating Modes

There are two modes in **vi**, `command mode` & `Insert mode`

**1. Command mode**

In this mode commands are used to **move** around and edit text objects

| Key | Description |
| ------ | ----------- |
| <kbd>ESC</kbd> | returns you to `command mode` |

**2. Insert mode**

This is the mode you use to type or **insert** text.


| Key | Description | Reverse | Description |
| ------ | ----------- | ----------- | ----------- |
| <kbd>i</kbd> | insert text **before** the cursor. | <kbd>I</kbd> | insert text at the **start** of the line. |
| <kbd>a</kbd> | insert text **after** the cursor. | <kbd>A</kbd> | insert text at the **end** of the line. |
| <kbd>o</kbd> | new line **below** the current line. | <kbd>O</kbd> | new line **above** the current line. |

