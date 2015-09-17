#Resume Builder!

#Background
This "Resume Builder" program allows users to:

1. Create ONE file that contains everything that they may want to include on a resume. 
2. Give each line item in that file a special tag, so that if you want to create multiple different resumes from the same file (e.g. one resume that highlights your front-end development experience and a different resume that highlights your back-end development experience), you can later use those tags to select a particular resume.
3. View the resume that you selected (content is displayed in the terminal), and save it to a PDF.


#Using the program
1. Download the "BulkResume.json" and "resumeprogram.rb" files from this repo. None of the other files in the repo are needed for the program, but you can download the entire repo if desired (it will not negatively effect the program).
2. Create a folder on your local machine (computer) and save the two files to that folder.
3. Select the "BulkResume.json" file, and replace the existing content with your content. See the comments in the file for more detailed instructions about how to update the file with your own content.
4. Open your terminal, and cd (i.e. use the "cd" change directory command) to navigate to the folder created in step #2.
5. Enter the following command via your command line (note the spaces): <b>ruby resumeprogram.rb bulkresume.json</b>
6. Follow the prompts to view, and/or print, the resume of your choice.
