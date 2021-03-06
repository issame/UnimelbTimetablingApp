# Unimelb Timetabling App

http://timetable.ruar.ai

Give this website your list of subjects for a semester and it will generate a list of possible timetables, sorted by quality.

Unlike similar websites for other universities, I've optimised the generator to create timetables
even where billions of possible choices are possible.

## Usage

I've designed the website to be as easy to use as possible. Just add your subjects, select your preferences and generate.
Once the timetables have been generated, you'll be shown the highest ranking timetable, but can browse through alternate
timetables by sliding the selection bar.

### Prefer Later Starts

Sorts the timetables according to the average start time. Unticking this will prefer an earlier average start time.

### Prefer Less days

Sorts the timetables according to number of scheduled days. This choice receives higher preference over 'Prefer Later Starts'. Unticking this will prefer timetables with more days scheduled.

### Clashing

The generator will always prefer to generate timetables that do not clash. If clashing is necessary, the timetables will be sorted so
as to reduce the number of clashes.
