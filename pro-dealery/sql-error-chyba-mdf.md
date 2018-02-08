# SQL Server detected a logical consistency

Pokud Vám pokladna ANetCa nelze spustit a v souboru "log.txt" je zapsána následující hláška, jedná se o poškozenou databázi. Toto může například způsobit vadný pevný disk. V tomto případě se doporučuje obnova ze starší zálohy, aby zákazníkovi zůstala alespoň část dat, položky a většina účtenek. Druhým řešením je pak oprava databáze, způsobem popsaným níže.

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

#### ÚPRAVA DATABÁZE MŮŽE ZPŮSOBIT NEVRATNOU ZTRÁTU DAT A DOPORUČUJE SE PROVÁDĚT POUZE PROŠKOLENÝM PERSONÁLEM!!!

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*



#### Chybové hlášení:

**Error:  
**

SQL Server detected a logical consistency-based I/O error: incorrect pageid \(expected 1:370; actual 0:0\). It occurred during a read of page \(1:370\) in database ID 5 at offset 0x000000002e4000 in file 'E:\arrowsys\anetca\anetcadbloc.mdf'.  Additional messages in the SQL Server error log or system event log may provide more detail. This is a severe error condition that threatens database integrity and must be corrected immediately. Complete a full database consistency check \(DBCC CHECKDB\). This error can be caused by many factors; for more information, see SQL Server Books Online.

HResult: -2146232060

Data:

#### Řešení:

USE \[corruptedb\]

ALTER DATABASE \[corruptedb\] SET EMERGENCY;

GO

ALTER DATABASE \[corruptedb\] SET SINGLE\_USER;

DBCC CHECKDB \(\[corruptedb\], REPAIR\_REBUILD\) WITH NO\_INFOMSGS, ALL\_ERRORMSGS

