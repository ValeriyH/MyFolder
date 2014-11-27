MyFolder
========
The main idea of this project is encrypt any type of CloudStorage like DropBox, Mega, GoogleDrive, ownCloud ant etc.

The application will use minifilter to monitor cloud sync folder and encrypt all data in it (excep special files requires to cloud sync application). If any application open file from cloud sync folder (except the cloud sync application) the MyFolder decrypt this file on the fly and give decrypted content to the application. The MyCloud gives access to files for cloud sync application without restrictions. So cloud sync application receives encrypted files to be synced with cloud. These files are also stays encrypted if MyFolder shutting down.
