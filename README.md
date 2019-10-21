# Gmail OAuth 2.0 Auto HTML Mail Sender

An auto mail sender for GMail which supports mail customizing with name.

  - Supports mail customizing with one area
  - Uses OAuth 2.0
  - Enjoy with more secure auth.
### Using

    MAIL_TITLE = "mail title"
    MAIL_MESSAGE = "html accepted message"

- Fill the blanks.
- Use {0} for CSV's first column and {1} for second column. Mail adress have to be in second column.
- First column for names and second column for mail adresses.
- You can use html for message.
 ### Example
     MAIL_TITLE = "Hi! {0}"
     MAIL_MESSAGE = "<b>Hi! Dear {0}</b> </br> Your name is {0} and your mail is {1}. "
