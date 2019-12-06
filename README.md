I love the Windows Terminal and if you haven't tried it out yet I highly recommend it. Its _super_ customizable which is absolutely lovely. Here are the steps to add Anaconda Prompt to Windows Terminal.

## Prerequisites
- [Install Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal-preview/9n0dx20hk701?activetab=pivot:overviewtab)
- [Install Anaconda](https://www.anaconda.com/distribution/)
- Windows 10

## Add Anaconda Prompt
1. Open Windows Terminal and click the arrow and then `settings`. This will open the `profiles.json` file to customize the terminal.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/510dg0xj5jcbgtz5isz8.PNG)
2. Duplicate the `cmd` settings by copying and pasting them below or highlight `CTRL + D` if using visual studio to duplicate the selected text. (I ♥ shortcuts) 
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/m0xac4m0sd28dcfjbx7r.PNG)
3. Update the `guid` to something unique by changing the last number
4. Update the `name` to `Anaconda`
5. Next update the `commandline` to the cmd for `Anaconda Prompt`. The easiest way to do this is to grab the target path from the Anaconda Prompt shortcut.
    - Search for `Anaconda Prompt` in the windows search bar
    - Right click and `open file location`
    - Right click on the `Anaconda Prompt` shortcut
    - Click `properties`
    - Grab the target path
    - Delete the extra text to get the path (shown below)
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/nvn4aujsh70qwuac6plq.gif)
The new terminal `profiles.json` should look something like this:
    ![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/bzx68enxok6pcipsxefu.PNG)
6. Save the changes to the `profiles.json` file
7. Open Windows Terminal
8. Click the down arrow and select `Anaconda`
9. BOOM! Anaconda in Windows Terminal.
![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/7jw6sv870lyedqunta72.PNG)
10. Listen to Sir-Mix-A-Lot and rejoice in your awesomeness
