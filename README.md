# Windows mouse coursor move
Move mouse coursor in certain period of time to keep user session alive

- Clone the repo
```
git clone https://github.com/alvelchev/windows_move_mouse_coursor_automatically.git
```
- Go to the directory where repo was downloaded
- Execute the Powershell script to move the mouse automatically.
```
PowerShell.exe -NoExit -ExecutionPolicy Bypass -File C:\mousemove.ps1
```
- In our example, the mouse will move 10 pixels every 5 seconds.
- Close the Powershell window to stop moving the mouse automatically.
