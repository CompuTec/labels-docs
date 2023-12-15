# HTTPS Configuration

Here, you can find information on configuring CompuTec Labels for HTTPS communication.

---

## Overview

To configure HTTPS, it must import a valid certificate to the Local Machine store on the server where the CompuTec Labels service runs and configure its properties in the CompuTec Labels configuration file.

## Certificate

Import a certificate used in the HTTPS communication to the Local Machine store on the Windows machine where the CompuTec Labels service will run. You can start the Local Machine certificate console with the command: certlm.msc.

The certificate must be placed in the Personal → Certificates store:

