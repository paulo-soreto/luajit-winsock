luajit-winsock
=

luajit-winsock is an pure lua **winsock implementation**, written using ffi binding.
The code is under MIT license and must be updated.

---

Socket class
-
I've written a simple socket class that contains the below methods:

    new(addr, type, protocol)
    accept()
    bind(host)
    close()
    connect(host, port)
    listen(backlog)
    available()
    recv(len, flags)
    send(message, flags)
    shutdown(how)
