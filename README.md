# europarlmin
Corpus of European Parliament debates organized as a corpus for meeting summarization, i.e. matching full transcripts and minutes from the sessions. Used in the shared task of AutoMin 2023.

This repository contains the train and dev sets. Each set contains directories labeled by date of the session in yyyy-mm-dd format. Each directory contains the transcripts and minutes of one or more chapters. Chapters are split further into parts.

The filenames follow this scheme:
- ep-yyyy-mm-dd-ch\<chapter_no\>-\<part_no\>.txt
  - the transcript files
- min-yyyy-mm-dd-ch\<chapter_no\>-\<part_no\>.txt
  - the minutes file
Each part is identified by date, chapter number and part number. Chapter number is three digits, part number is two digits. Chapters are numbered from one. Chapters which originally only had a single part are labeled with part number zero. Chapters with more parts have their parts numbered from one. This data has been filtered, therefore the chapter and part numbers do not necessarily follow in sequence.
