# gu-e2t
Convert a Glasgow University exam timetable to a PDF containing only your exams or create a `.ics` file to import to your calendar! 
Use at your own risk!

# Running the Script
- make executable `chmod +x gu-e2t`
- run `./gu-e2t` or add to path

# Usage
- takes a collection of PDF files (GU exam timetables) and can produce PDF, TSV or ics files
```
Usage: gu-e2t [-Ptch] [-n last-name] [files]
	-P              do NOT generate a pdf file with relevant data in a table
	-t              generate a tsv file with relevant data
	-c              generate .ics file (DISCLAIMER: AI GENERATED CODE SEE SCRIPT FOR DETAILS)
	-h              help
	-n last-name    user's last name, used to determine exam room
	files           Glasgow university exam timetable files
```
- note: you can multi-select in fzf with tab :)

# Dependencies
- fzf, pdflatex and pdftotext
- a posix compliant shell

# Disclaimer
This tool is a personal project I made for fun and is not affiliated with or endorsed by the University of Glasgow.
While I've done my best to ensure correctness for parsing/room allocation logic, I cannot guarantee accuracy. Always double check the
allocated rooms, dates and times are correct with the university exam timetable. I am not responsible for any missed exams or incorrect
locations resulting from the use of this script.
