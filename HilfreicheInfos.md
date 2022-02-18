# Hilfreiche Infos über verschiedene Themen

Zum berechtigen des Anwendungspools **blog1** im FileSystem muss der Namespace **IIS AppPool** explizit angegeben werden da sonst der UserKontext des Anwendungspools nicht gefunden werden kann.
>IIS AppPool\blog1