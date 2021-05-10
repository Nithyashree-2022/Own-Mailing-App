# Own-Mailing-App
Why use GMail when you can create your own mailing app using SMTP in Python!!!

I have created my own mail application named MyMail using Streamlit web app as follows:

The project uses Streamlit front-end which inputs the recipient's address(es),subject-line ,body of the mail and image attachments(if any) and mails just perfectly to the recipient(s).

Functionalities:

Mail both:

1.Text

2.Attachments(IMAGE FILES,PDF FILES AND A COMBO OF BOTH!)

Test cases:

->1 recipient with no attachment(s) 

->1 recipient with attachment(s)

->multiple recipients without any attachment

->multiple recipients with attachments

and/or HTML mail with all of the above four test cases.

The above can be successfully achieved with the given code-"Implementation of SMTP...."

Further,the "Extended MyMail" file has the supports mailing pdfs and HTML mails too along with images and plain-text.

It again supports both single and multiple recipients with an option to include the HTML mail.

EmailMessage() is used to mail pdfs and HTML mails.

MIMEMultipart was used in the first file to mail plain-text and image attachments.

NOTE:

While executing Extended MyMail on colab,the value error in streamlit can be ignored for we still get the desired mail just perfectly!!!


