# azure-archive
This project uses azure search and azure document db in the backend along with a azure data blob to implement an archiving solution using azure.

The flow starts with data being copied from on premise / external FTP sources to azure using azure data factory and then make it available for archiving.

The data could be pdf's / text files / word documents / emails / scanned documents

The next step would involve data extraction and later we use azure search to index the data and store them.

