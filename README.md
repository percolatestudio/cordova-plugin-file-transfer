Percolate Studio's fork of cordova-plugin-file-transfer
-------------------------------------------------------
We haved removed the multipart form section of the requestForUploadCommand method. 
This allows the FileTransfer plugin to be used when uploading to an endpoint that expects
only the raw file to be included in the body of the request.

Install like `cordova plugin add https://github.com/percolatestudio/cordova-plugin-file-transfer.git`.

Usage is the same as the standard File Transfer plugin. Currently only ios is modified.
