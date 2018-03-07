# About WinMerge Help


This is Help for WinMerge 2.16.0

## 1. Audience and scope

WinMerge Help is intended for both new and experienced users.  It explains how to use WinMerge, and documents its capabilities and limitations.

## 2. How to access Help

WinMerge Help topics are provided in two forms:

- Microsoft HTML Help (`WinMerge.chm`), located in your WinMerge/Docs installation directory.
        
- HTML manual on the WinMerge Web site.

You can access WinMerge Help in several ways:

- **WinMerge Help menu:** While using WinMerge, click *Help &rarr; WinMerge Help*.  HTML Help opens at the beginning (this topic).

- **Context-sensitive help:** While using any WinMerge window, press `F1`. If a specific topic is available for your current window, Help opens at that topic. If not, Help opens at the beginning.

- **WinMerge command line:** Use the `/?` or `-?` switch when running WinMerge from the command line. HTML Help opens at the beginning.
          
- **WinMerge Web site:** Open your Web browser to [winmerge.org](http://winmerge.org/). Under [Documentation](http://winmerge.org/docs/), follow the [Manual](http://manual.winmerge.org/) link to the latest Help version.
          

## 3. How to use Help  

Please read the following topics to learn essential WinMerge basics,

- **[Quick Start](./Quick_start.md)** - Gets you quickly started with WinMerge and shows its basic usage.
          
- **[Comparing and merging folders]()** - Explains the folder comparison window, available operations, and customizing the results display.
          
- **[Comparing and merging text files]()** - Explains the file comparison/merge window, available operations, methods of navigation, and modes.
          
- **[Options and Configuration]()** - Explains how to customize WinMerge, including handling whitespace, colours, and text encoding.
          
          
To learn about WinMerge in more detail, read these topics:

- **[Opening Files and Folders]()** - Introduces several ways to open files and folders in WinMerge - there are many! For example, do you know how to use the Shell Extension context menu in advanced mode?
          
- **[Plugins]()** - Describes the optional, extra features that you can add to WinMerge using its plugin mechanism.

- **[Using Filters]()** - Explains how to control what is compared in the folder or file comparison window.

- **[Command Line]()** - Lists command-line parameters for using WinMerge with other tools or from a script.

- **[Faq]()**   - Contains answers to many common questions asked of developers.

Before submitting questions to [SourceForge.net](http://sourceforge.net/projects/winmerge/), please check the [Faq]()  topic first to see if your question is answered there.
          

## 4. Documentation conventions


| Example | Indicates |
|---------------------------|----------------------------------------------|
| Enter **UTF-8** in the field<br/><br/>Click the **Browse** button to navigate to the path<br/> <br/>Press **F5** once to refresh the window. | **Bold** font in descriptive text can indicate:<br/><ul><li>A value or string that you are instructed to enter</li><li>The name of a GUI button or keycap.</li></ul> |
|Press **Ctrl+O** |*Press* indicates a keyboard action. In this example, press the **Ctrl** and **O** keys in combination.| 
|Click **OK**| *Click* indicates a left mouse click on an object, such as a menu item or button.|
|Click *File &rarr; Open*.|The arrow indicates menu navigation. In the example, you choose the *Open* item in the WinMerge *File* menu.|
|Right-click the row and choose the *Compare* shortcut.|Click the right mouse button on an object to open its context menu, and then either left-click or right-click the indicated item in the context menu.|
|Enter *options file*.ini<br/><br/>Use the *Filter* field to eliminate files from the             operation<br/><br/>One or more consecutive different lines form one difference (or *diff*).|*Italicized* text can represent: <br/><ul><li>A replaceable value or string. In the first example, you would substitute a real file name for the italicized term, but enter the `ini` file extension, which is not italicized, as written</li><li>The name of a field, menu, or control in a WinMerge window</li><li>A significant word or phrase that is introduced.</li></ul>|
|The path `%WORKDIR%\project1` is expanded to `C:\workfiles\project1`<br/></br> `TwoWords` | `Monospaced` text can indicate:<br><ul><li> A path or the name of a file or other system item</li><li>Sample code fragments</li><li> Sample output</li><li>Information that you enter in a form or on the command line</li></ul>|
|`command inputpath [outputpath]`|In syntax lines, brackets indicate optional elements. In this example, you must enter an input path with the command; you can also enter an output path, but the command is valid without it.