[Website Link](https://bath-samba.github.io/sls-site/sls.html)

How to edit this site locally:


Option 1) 
1.  Download Quarto from https://quarto.org/docs/get-started/
2.  Pull the repository
3.  Open the "website.Rproj" file in R-Studio. Edit the "sls.qmd" file (this is the SLS schedule) as appropriate. In R-studio this is very easy: it's an intuitive GUI
4.  Render the website, all outputted html and css is shoved into the "/docs" folder. There is a button for this in R-studio: top right window got to the build tab, click "Render Website". Pressing this button will also open a preview of the website.
5.  Push the freshly rendered website to GitHub. Should update within an hour.


Option 2) - No command line Git and all in VSCode!
1. Download Quarto from https://quarto.org/docs/get-started/
2. Install Quarto VSCode extension from https://marketplace.visualstudio.com/items?itemName=quarto.quarto
3. Pull repository (using built in VSCode Git integration if desired)
4. Open & edit sls.qmd as desired (Quarto extension includes a v. good visual editor for minor changes, right click anywhere in file to change editor type).
5. Render the website (Click 'Preview' in top right of tab bar, >Quarto: Preview, or Ctrl + Shift + K), this will open a preview of the site.
6. Push changes to GitHub (again can use integrations).