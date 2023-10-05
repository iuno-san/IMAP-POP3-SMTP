# Open source email, What is (IMAP, POP3, SMTP)⚡️📨 
<img src="https://www.socketlabs.com/wp-content/uploads/2019/05/SMTP-IMAP-1.png">


# Mail Servers (IMAP, POP3, SMTP)

A mail server is a computer that stores email messages. It is essential for users to be able to send and receive email messages.

## IMAP (Internet Message Access Protocol)

IMAP (Internet Message Access Protocol) is a mail access protocol that allows users to access email messages on a mail server. IMAP is a **bidirectional** protocol, which means that the user can synchronize email messages between the mail server and the mail client. This allows users to read, forward, delete, and organize email messages from any device.

**IMAP parameters:**

* IMAP server address: `imap.example.com`
* IMAP port: `143` (or `993` for an SSL connection)
* Username: `your_name@example.com`
* Password: `your_password`

## POP3 (Post Office Protocol 3)

POP3 (Post Office Protocol 3) is a mail access protocol that allows users to download email messages from a mail server. POP3 is a **one-way** protocol, which means that the user downloads email messages from the mail server and stores them on their device. After downloading, the email messages are deleted from the mail server.

**POP3 parameters:**

* POP3 server address: `pop3.example.com`
* POP3 port: `110` (or `995` for an SSL connection)
* Username: `your_name@example.com`
* Password: `your_password`

## SMTP (Simple Mail Transfer Protocol)

SMTP (Simple Mail Transfer Protocol) is a mail transfer protocol that allows users to send email messages. SMTP is a **message-transfer** protocol, which means that it transfers email messages from one mail server to another.

**SMTP parameters:**

* SMTP server address: `smtp.example.com`
* SMTP port: `25` (or `465` for an SSL connection)
* Username: `your_name@example.com`
* Password: `your_password`

## Summary

* IMAP is a mail access protocol that allows users to synchronize email messages between the mail server and the mail client.
* POP3 is a mail access protocol that allows users to download email messages from the mail server.
* SMTP is a mail transfer protocol that allows users to send email messages.

## Which protocol to choose?

The choice of the right protocol depends on the user's needs. IMAP is a good choice for users who want to have access to their email from any device. POP3 is a good choice for users who want to keep their email on their device. SMTP is essential for sending email messages.
