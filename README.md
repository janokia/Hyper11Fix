# Hyper 11 Fix
"Hyper11Fix" fixes the missing "Drag &amp; Drop to the Taskbar" support in Windows 11. It works with the new Windows 11 taskbar and does not require nasty changes like UndockingDisabled or restoration of the classic taskbar. It is based on the ["Windows11DragAndDropToTaskbarFix"](https://github.com/HerMajestyDrMona/Windows11DragAndDropToTaskbarFix) by [HerMajestyDrMona](https://github.com/HerMajestyDrMona).

## **How Does It Work?**

The program detects if you're currently pressing the Left or the Right Mouse Button and determines which icon on the taskbar you hover the mouse pointer on. If the cursor stays in the same area for definied number of milliseconds - it simulates the `Win+T` hotkey and arrow keys in order to restore the intended window, using a quite complicated method. It also supports dropping files to the "Show desktop" button (bottom-right of the screen). The program supports multiple screens, auto startup, and has many configuration options (please read below). Windows11DragAndDropToTaskbarFix has no auto-update function and never connects to the Internet, so you don't need to worry about your privacy.

## **How to Start or Quit the Program?**

To use the fix, please simply download the binary file above (or compile it yourself) and **start it as any other program**. It works as an independent C++ process.

To quit this program, please click on the Mona Lisa Megan Fox Tray icon, and select "Quit..." from the menu. You can also **kill** `Hyper11Fix.exe` or `Hyper 11 Fix` **by the Task Manager**.

### "VCRUNTIME140_1.dll" was not found error
If you get an error saying that "VCRUNTIME140_1.dll" is missing, please install [Microsoft Visual C++ 2015 - 2019 Redistributable x64](https://aka.ms/vs/16/release/vc_redist.x64.exe). Normally, these runtime libraries are installed by default on Windows 11. If you get this error then you most likely manually removed them before, using "Add or remove programs".

## **Limitations**
- The program does not support pinning apps to the taskbar using the drag and drop gesture, and this feature is currently not planned. However, you still can pin apps to the taskbar by clicking on their icons with the right mouse button, and then "Pin to taskbar" from the list.

