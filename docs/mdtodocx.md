# How to convert a Markdown file into a Word document

You can convert a Markdown file into a Word document easily. After following these specific steps you will be able to successfully generate a Word document from Markdown using Pandoc.

## Tools needed

- [Pandoc](download.html)
- Markdown file
- Command Line Program
  - *This program can be the default command line, Powershell, or Windows Terminal.*
- File Explorer
- Microsoft Word

## Steps

1. Open File Explorer to the directory where your Markdown document is saved.
   - *Optional:* Move the Markdown document into a new, empty folder.
2. Type in the following command into the file path depending on the command line program you chose:
   - `cmd`
   - `wt`
   - `powershell`

    <figure>
    <img src="media/fileExplorerPreview.png" alt="File explorer with wt being entered into the path.">
    <figcaption> Figure 1: The file explorer in the current directory of the Markdown document with <code>wt</code> being entered into its path.
    </figure>

3. Type the following into the command line program, replacing the `<>`'s:

   ```bat
   pandoc -s <Markdown file name>.md -o <Word document filename>.docx
   ```

4. Check the directory where you ran the command, there should be a Word file created.
5. Open the newly created Word file in Microsoft Word.
6. Clean up the file according to the design you want.
7. Save your edited document.

{% include footer.md %}
