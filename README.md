# Background

I used resume.io to create my resume, and it was also where I kept track of my job applications. This became a bit problematic since the board can't be shared.

Solution: this script that extracts the company name, job title, job posting link, and date. The resulting dataset can be saved as a CSV and later imported to Notion. Notion will automatically display it as a table, but the view can be changed to a Kablan board just like in Trello or resume.io.

# Instructions

1. `git clone` repo
2. Save each section of the board as separate HTML files
  1. Right click on the title of a section of the board (eg: 'Offer'), click `inspect`
  2. Select and right click on a `div class="sc-eyVSUm kCyuzY"`, select Copy -> Outer HTML
  3. Paste into notepad, save as an HTML file in `/path/to/resume_to_notion/`
  4. Repeat with all sections
3. Open jupyter notebook, put in filename, run all cells
4. Import CSV file to Notion

## Step 2.1

<img src = "https://github.com/pomkos/resume_to_notion/blob/main/Screen%20Shot%202021-12-14%20at%2019.32.38.png?raw=true" width=420 >

## Step 2.2

<img src = "https://github.com/pomkos/resume_to_notion/blob/main/Screen%20Shot%202021-12-14%20at%2019.22.23.png?raw=true" width=420>

## Step 2.3

<img src = "https://github.com/pomkos/resume_to_notion/blob/main/Screen%20Shot%202021-12-14%20at%2019.22.45.png?raw=true" width=420>
