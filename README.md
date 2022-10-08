# Windows mouse coursor move
Move mouse coursor in certain period of time to keep user session alive

- 1.Clone the repo
```
git clone https://github.com/alvelchev/windows_move_mouse_coursor_automatically.git
```
- 2.Go to the directory where repo was downloaded
- 3.Execute the Powershell script to move the mouse automatically.
```
PowerShell.exe -NoExit -ExecutionPolicy Bypass -File C:\mousemove.ps1
```
- 4.In our example, the mouse will move 10 pixels every 5 seconds.
- 5.Close the Powershell window to stop moving the mouse automatically.
