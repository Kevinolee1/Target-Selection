# Target-Selection
Lab 2 — Target Selection  Selected **Calibre-Web NextGen** as the authorized open-source research target. Reviewed its security policy, local deployment options, and responsible-disclosure process before testing.  **Outcome:** Established a legitimate target and defined the research scope and testing boundaries.

**Create our Lab 2 documentation**

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/f41378505c9964fdb215a0993f7e3708a00bd46f/Target-Selection/Screenshot%202026-09-01%20230859.png)

From PowerShell run: notepad notes\target-selection.md

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/40d4a69596cff35d830af2269f34876926ae4fcd/Target-Selection/Screenshot%202026-09-01%20230932.png)

select Yes when prompt

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/ba1bd99fadd27caad38ebb33e02d0102e6999b5e/Target-Selection/Screenshot%202026-09-01%20231240.png)

Now paste the following into the Notepad file:

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/b60f81a79acdea95af2c501e50cea373b6731a91/Target-Selection/Screenshot%202026-09-01%20231338.png)

Press Ctrl+S to save 

**Final Policy Verification & Target Acquisition.**
Local research is appropriate.

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/2831ff1212755a4b0c9a92156570b321f258923d/Target-Selection/Screenshot%202026-09-01%20232453.png)

in PowerShell run: git --version

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/154b68cf94aaa309db32addfc9b2ba2ea90820e6/Target-Selection/Screenshot%202026-09-01%20232603.png)

Go into the targets folder Run: cd targets

Your prompt should change similar to: (.venv) PS C:\Users\eelve\Vulnerability-Research-Lab\targets>

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/003b98aaecbef694a8afe36a457041413a0450fc/Target-Selection/Screenshot%202026-09-01%20233420.png)

Clone the official target run: git clone https://github.com/new-usemame/Calibre-Web-NextGen.git 

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/0dda3def3769cac781d04170c80632e08e996d5e/Target-Selection/Screenshot%202026-09-01%20233603.png)

This downloads the source code into our local research environment. We are not scanning or attacking anything by cloning it.

![Image alt](![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/d93a2d6da5764b12f6ef328606052dbc55a792bc/Target-Selection/Screenshot%202026-09-01%20233817.png)

When it finishes, run:Get-ChildItem

You should see: Calibre-Web-NextGen

**Enter the target**

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/2ef993daed33c4a094003691cb01bbaade160697/Target-Selection/Screenshot%202026-09-01%20234024.png)

Run: cd Calibre-Web-NextGen

![Image alt](https://github.com/Kevinolee1/Target-Selection/blob/31b1a584e9d6a89427d61ee06d249685a586fd46/Target-Selection/Screenshot%202026-09-01%20234130.png)

Get the exact commit Run: git rev-parse HEAD

You'll get a long value similar to: a1b2c3d4e5f6789012345678901234567890abcd

Check the branch run: git branch --show-current

Run these three commands:
git rev-parse HEAD

git branch --show-current

Go back to the main project directory run: cd C:\Users\eelve\Vulnerability-Research-Lab

Open your Lab 2 notes run: notepad notes\target-selection.md

At the bottom, add: Save with Ctrl + S and close Notepad.


