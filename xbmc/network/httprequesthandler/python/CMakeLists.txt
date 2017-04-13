<<<<<<< HEAD
if(MICROHTTPD_FOUND AND PYTHON_FOUND)
=======
if(MICROHTTPD_FOUND)
>>>>>>> xbmc/Krypton
  set(SOURCES HTTPPythonInvoker.cpp
              HTTPPythonWsgiInvoker.cpp)

  set(HEADERS HTTPPythonInvoker.h
              HTTPPythonRequest.h
              HTTPPythonWsgiInvoker.h)

  core_add_library(network_httprequesthandlers_python)
endif()
