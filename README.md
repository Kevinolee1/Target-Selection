# Target-Selection
Lab 2 — Target Selection  Selected **Calibre-Web NextGen** as the authorized open-source research target. Reviewed its security policy, local deployment options, and responsible-disclosure process before testing.  **Outcome:** Established a legitimate target and defined the research scope and testing boundaries.

**Create our Lab 2 documentation**

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/f41378505c9964fdb215a0993f7e3708a00bd46f/Target-Selection/Screenshot%202026-09-01%20230859.png)

From PowerShell run: notepad notes\target-selection.md

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/40d4a69596cff35d830af2269f34876926ae4fcd/Target-Selection/Screenshot%202026-09-01%20230932.png)

select Yes when prompt

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/ba1bd99fadd27caad38ebb33e02d0102e6999b5e/Target-Selection/Screenshot%202026-09-01%20231240.png)

Now paste the following into the Notepad file:

Press Ctrl+S to save 

**Final Policy Verification & Target Acquisition.**
Local research is appropriate.

in PowerShell run: git --version

Go into the targets folder Run: cd targets

Your prompt should change similar to: (.venv) PS C:\Users\eelve\Vulnerability-Research-Lab\targets>

When it finishes, run: Get-ChildItem

Clone the official target Run: Get-ChildItem

You should see: Calibre-Web-NextGen

Enter the target

Run: cd Calibre-Web-NextGen

Get the exact commit Run: git rev-parse HEAD

You'll get a long value similar to: a1b2c3d4e5f6789012345678901234567890abcd

Check the branch run: git branch --show-current

Run these three commands:
git rev-parse HEAD

git branch --show-current

Go back to the main project directory run: cd C:\Users\eelve\Vulnerability-Research-Lab

Open your Lab 2 notes run: notepad notes\target-selection.md

At the bottom, add: Save with Ctrl + S and close Notepad.


