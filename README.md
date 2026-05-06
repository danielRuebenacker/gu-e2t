# gu-e2t
GU exam timetable to PDF timetable!

# Running the Script
- make executable `chmod +x gu-e2t`
- run `./gu-e2t`

# Usage
```
Usage: gu-e2t [-Ptch] [-n last-name] [files]
	-P              do NOT generate a pdf file with relevant data in a table
	-t              generate a tsv file with relevant data
	-c              generate .ics file (DISCLAIMER: AI GENERATED CODE SEE SCRIPT FOR DETAILS)
	-h              help
	-n last-name    user's last name, used to determine exam room
	files           Glasgow university exam timetable files
```

# Dependencies
- fzf, pdflatex and pdftotext
