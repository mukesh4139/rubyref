# WIN32OLERuntimeError

Raised when OLE processing failed.

EX:

    obj = WIN32OLE.new("NonExistProgID")

raises the exception:

    WIN32OLERuntimeError: unknown OLE server: `NonExistProgID`
        HRESULT error code:0x800401f3
          Invalid class string

[WIN32OLERuntimeError Reference](https://ruby-doc.org/stdlib-2.5.0/libdoc/win32ole/rdoc/WIN32OLERuntimeError.html)