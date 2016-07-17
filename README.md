# SXencGUI
Zenity-driven Mount / Unmount of encrypted directories

<img alt="SXencGUI Logo" src="http://ideaware.xyz/wp-content/uploads/2016/07/SXencGUI.png" width="48px" height="48px" />

## SXencGUI – { Mount / Unmount Encrypted Directories }
SXencGUI is a simple Zenity front-end to encfs, useful for handling the mounting / unmounting of encrypted directories previously set up with encfs. The interface is simple and self explanatory.

### { Program Options }

This is the interface of SXencGUI:

<img alt="SXencGUI Interface" src="http://ideaware.xyz/wp-content/uploads/2016/07/SXencGUI-SShot.png" />

The “Mount/Unmount Action” is a drop-down that contains the **Mount**, **Unmount** and **Refresh** options.

To mount an encrypted directory, select **Mount** from the **Action** menu, then follow the **File Selection Dialog** to choose an encrypted directory, then the next **File Selection Dialog** to choose the **mount point** then enter your **passphrase** and click **OK**

The “Mounted Directories” displays a list of encrypted directories currently mounted.

To unmount an encrypted directory, select **Unmount** from the **Action** menu, then select the directory from the “Mounted Directories” List and click on the “Mount/Unmount/Refresh” button.

Lastly, there is a help drop-down menu, labelled “Click drop-down Help”, summarizing the program’s operation.

### { Program Setup }
This program is going to be installed by default in your **$HOME/bin** directory. If you have not set your **$HOME/bin** in the **$PATH**, see [this](http://istos.xyz/linux/include-homebin-in-any-desktop-environment/ "Include $HOME/bin in any Desktop Environment") or [this snippet](http://istos.xyz/linux/include-homebin-in-the-path-for-bash-shell "Setup your $HOME/bin in the $PATH") for details.

To run this program, you need to have the following packages installed in your system (Check with your package manager):

- _**zenity**_
- _**encfs**_

#### Once the above packages are installed
- Download SXencGUI
- Move the downloaded tarball into your **$HOME**, as all extracted files and directories will be relative to your **$HOME**
- Expand the tar file in a terminal by issuing:  
<code>**tar xf SXencGUI\_&lt;version&gt;.tar**</code>
- Invoke the program from the terminal, running:  
<code>**SXencGUI &**</code>  
to ensure that it loads properly and no error messages are shown.

If everything has gone ok, you should be able to find the program in the _**Accessories**_ program group on your desktop manager.

### { File List }
The tarball contains these files (relative to the user's $HOME):
<pre>
bin/SXencGUI
.local/share/icons/SXencGUI.png
.local/share/applications/SXencGUI.desktop
</pre>

