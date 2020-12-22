# PantserWriter Beta (current beta version is beta5.4) [(see current version notes in the Wiki)](https://github.com/Salami-Sam/PantserWriterBeta/wiki/Current-Version-Notes-and-New-Features)

**Just download and extract the .zip file.**

[Download from Google Drive](https://drive.google.com/drive/folders/1ul75QMuAp1fzLnTpkSqRNpRF9McdFF1A?usp=sharing)

[Facebook](https://m.facebook.com/PantserWriter-101401631866185/)

Supported platform(s): **Windows 10**

(Note that you will have to give the application permission to run.)

# Why use this software?

**Here are some of PantserWriter's unique features that you may like:**
  1. The [**integrated note-taking companion with an intuitive and unobtrusive design**] allows you to manage and edit notes on the fly without disrupting your workflow.
  2. Ctrl+Right click any word or phrase in your manuscript and a context menu will appear with a list of all of your notes whose names closely resembles the word/phrase so that you can **[open and edit your notes without having to search for them]**.
  3. **[Any note that you create can easily be used as a template]** for other notes. Do you have a preferred format for character profiles? Just create an empty character profile once, then use it as a template for all of your characters! You can use these templates in all of your PantserWriter projects as well; just copy the folder containing your templates into the "notes" folder of the desired project. (see unavailable feature #8 for details during beta)
  4. PantserWriter **[projects use your computer's default directory/file system, and every file is simply a .rtf file]**, so you can open and edit them in most word processors. This also means that if you decide you don't like PantserWriter, it will take virtually no work to move to another word processor.
  5. **[Blazing fast workflow]** using mostly-common hotkeys. You won't ever have to take your hands off the keyboard while inside the application. Feel the freedom and stay in the zone of writing! (Some hotkeys may not be implemented during beta.)
  6. It's **[completely free]**.

# **[About this project](https://github.com/Salami-Sam/PantserWriter/wiki/About-This-Project)**

**Some features that are currently unavailable but are planned for the full version:**
  1. Backup a project to another directory/folder from within the application **Update 12/09/2020:** This feature is now fully available
  2. Open another project after already opening one; you will have to exit the program to open a different project
  3. Keyword search within the body of a file (chapter and notes) **Update 11/27/2020:** This feature is now fully available
  4. Combining the chapters within the manuscript folder in order to create one manuscript document (you could just use a single file if this is an issue)
  5. Creating a sequel project that automatically imports all of your notes from the original project within the application
  6. Spellcheck **AVAILABLE as of 12/14/2020**
  7. Numbered lists **AVAILABLE as of 12/14/2020**
  8. Manual file syncing with the application's user interface (if you added a folder or file to your project while the application was running, you will have to restart the application to see them in the user interface) **Update 12/09/2020:** This feature is now fully available
  9. Underline text **AVAILABLE as of 12/14/2020**

# **Known Bugs**
  1. Word count is off by +/- 1 word. 
  2. Project doesn't backup properly after the first time.

# **Fixed Bugs**
  1. **FIXED (11/25/2020):** When switching files, the file that you are switching from will occasionally overwrite the file you are switching to (happens with note files and chapter files).
  2. **FIXED (11/25/2020):** Current note's content would not update when deleting a note.
  3. **FIXED (11/27/2020):** Undo no longer just deletes everything you have written.
  4. **FIXED (11/27/2020):** Ctrl + Z still deletes everything in the bare bones note companion editor.
  5. **FIXED (12/09/2020):** Undo changes the zoom percentage when holding down Ctrl + Z.
  6. **FIXED (12/14/2020):** When holding Ctrl + Z to undo, the cursor gets out of place and not everything is able to be undone that should be. **UPDATE (12/09/2020)** The cursor position is usually accurate, especially when tapping Ctrl + Z rather than holding. I am continuing to find a better solution using .NET Framework and Windows Forms.
  7. **FIXED (12/10/2020)** Copy and Paste was not working in version beta 4.

# **Updates**
  1. **11/25/2020:** Changed how zooming works. You can now use Ctrl + scrollwheel to zoom in and out freely and the application will remember your zoom settings. No manual typing option exists right now for zooming.  Overall workflow/usability improvements have been made.
  2. **11/27/2020** You can now right click on a word to see if it matches the name of your notes. A context menu will appear with every note whose name is closely matched so that you can click on one to open in a new (bare bones) note companion to edit. For example, say you are writting about a man named John. You reveal something new about his character and now you want to add that new info to his character sheet in your notes. Just right click on his name and you can directly access it from the context menu, no searching needed.
  3. **11/27/2020** Implemented bare bones note editor for note companion, cleaned glitches when closing bare bones editor. Also, you can now switch the note in the bare bones editor via the right click context menu. Notes are saved automatically before switching. 
  4. **12/09/2020** Bare bones editor is now stable to use. It will no longer open notes that are open in the note companion, ensuring that your edits will be saved. UI color is more uniform (though maybe not particularly anything to write home about). If you changed the window layout and want to reset it to default, there is a button for that now. You can now backup your projects to other folders. You can copy/past or drag/drop .rtf files into your project's notes and/or manuscript folders then press 'Refresh Project' for the UI to see them. Overall UI layout changed.
  5. **12/14/2020** You can now toggle autosave.
  
