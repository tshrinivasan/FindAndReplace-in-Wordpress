Traceback (most recent call last):
  File "C:\Users\Rksha\AppData\Local\Programs\Python\Python310\lib\site-packages\wordpress_xmlrpc\base.py", line 24, in __init__
    self.supported_methods = self.server.mt.supportedMethods()
  File "C:\Users\Rksha\AppData\Local\Programs\Python\Python310\lib\xmlrpc\client.py", line 1122, in __call__
    return self.__send(self.__name, args)
  File "C:\Users\Rksha\AppData\Local\Programs\Python\Python310\lib\xmlrpc\client.py", line 1464, in __request
    response = self.__transport.request(
  File "C:\Users\Rksha\AppData\Local\Programs\Python\Python310\lib\xmlrpc\client.py", line 1166, in request
    return self.single_request(host, handler, request_body, verbose)
  File "C:\Users\Rksha\AppData\Local\Programs\Python\Python310\lib\xmlrpc\client.py", line 1196, in single_request
    raise ProtocolError(
xmlrpc.client.ProtocolError: <ProtocolError for www.wordpress.com/home/python.sport.blog: 301 Moved Permanently>

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "C:\Users\Rksha\AppData\Local\Programs\Python\Python310\lib\site-packages\wordpress_xmlrpc\base.py", line 27, in __init__
    raise ServerConnectionError(repr(e))
wordpress_xmlrpc.exceptions.ServerConnectionError: <ProtocolError for www.wordpress.com/home/python.sport.blog: 301 Moved Permanently>
