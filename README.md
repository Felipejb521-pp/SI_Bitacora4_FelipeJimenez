# SI_Bitacora4_FelipeJimenez 
ERRORES
    1.Al poner localhost en vez de 127.0.0.1 me salía:
    PS C:\Users\DAM1\Documents\felipe\SI_Bitacora4_FelipeJimenez> ssh alumno@localhost -p 2222
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    @    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!
    Someone could be eavesdropping on you right now (man-in-the-middle attack)!
    It is also possible that a host key has just been changed.
    The fingerprint for the ED25519 key sent by the remote host is
    SHA256:XQTxbLoAf5ZV0aNP1LUciQNBR4eRUlBGcQ/CnrrM0DI.
    Please contact your system administrator.
    Add correct host key in C:\\Users\\DAM1/.ssh/known_hosts to get rid of this message.
    Offending ECDSA key in C:\\Users\\DAM1/.ssh/known_hosts:3
    Host key for [localhost]:2222 has changed and you have requested strict checking.
    Host key verification failed.
