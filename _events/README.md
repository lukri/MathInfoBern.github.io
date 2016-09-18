# Events
Jekyll lookup directory for Events.

To add an event, create here a new file eventname.yml of the following form.
All fields except **date** are required.
But if you do **not** specify a date you must add a field `nodate: True` instead.

    ---
    title: some title
    text: |
     some text
     that keeps the linebreaks
    link: link to facebook event
    image: flyer or other image
    date: YYYY-MM-DD
    ---

To make **multiline text**, you can use `>` for ignoring linebreaks and `|`
to keep them. In both cases, the text must be intendet by on space and start on the line below.
