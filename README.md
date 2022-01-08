# Self Hosted and OpenSource emails archiving solution

This project is written in PHP and has been written as an alternative to Piler and MailArchiva.

## Features
* archive Emails from multiple sources
* search archives emails using modern Bootstrap 5 interface
* permission management allowing users to access more emails addresses/aliases than their own
* retention policies to automatically purge very old archives
* deduplication to optimize disk space use
* high performance imports (> 100 emails/seconds depending on your hardware/network)
* lightweight software (2Mb of code with very little dependencies)
* open source
* self hosted

## Supported email sources

* IMAP mailboxes, 
* local folder, accessible to the application, 
* folder upload from your browser (uploading any emails of your choice)

## Requirements

* PHP8+,
* Nginx,
* SQLite3 extension, 
* IMAP extension,

---

The project is still being written and will be uploaded to this repository soon.
