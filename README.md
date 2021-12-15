# Background

I used to resume.io to create my resume, and it was also where I kept track of my job applications. This became a bit problematic since the board can't be shared.

Solution: this script that extracts the company name, job title, job posting link, and date. The resulting dataset can be saved as a CSV and later imported to Notion. Notion will automatically display it as a table, but the view can be changed to a Kablan board just like in Trello or resume.io.

# Instructions

1. Save each section of the board as separate HTML files
  1. Right click on the title of a section of the board (eg: 'Offer'), click `inspect`
  2. Select and right click on a `div class="sc-eyVSUm kCyuzY"`, select Copy -> Outer HTML
  3. Paste into notepad, save as an HTML file
2. Open jupyter notebook, put in filename, run all cells
3. Import CSV file to Notion

