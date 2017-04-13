if(MICROHTTPD_FOUND)
  set(SOURCES HTTPFileHandler.cpp
              HTTPImageHandler.cpp
              HTTPImageTransformationHandler.cpp
              HTTPJsonRpcHandler.cpp
<<<<<<< HEAD
=======
              HTTPPythonHandler.cpp
>>>>>>> xbmc/Krypton
              HTTPRequestHandlerUtils.cpp
              HTTPVfsHandler.cpp
              HTTPWebinterfaceAddonsHandler.cpp
              HTTPWebinterfaceHandler.cpp
              IHTTPRequestHandler.cpp)

<<<<<<< HEAD
  if(PYTHON_FOUND)
    list(APPEND SOURCES HTTPPythonHandler.cpp)
  endif()

  set(HEADERS HTTPFileHandler.h
              HTTPImageHandler.h
              HTTPImageTransformationHandler.h
              HTTPJsonRpcHandler.h
              HTTPRequestHandlerUtils.h
              HTTPVfsHandler.h
              HTTPWebinterfaceAddonsHandler.h
              HTTPWebinterfaceHandler.h
              IHTTPRequestHandler.h)
  if(PYTHON_FOUND)
    list(APPEND HEADERS HTTPPythonHandler.h)
  endif()

=======
  set(HEADERS HTTPFileHandler.h
              HTTPImageHandler.h
              HTTPImageTransformationHandler.h
              HTTPJsonRpcHandler.h
              HTTPPythonHandler.h
              HTTPRequestHandlerUtils.h
              HTTPVfsHandler.h
              HTTPWebinterfaceAddonsHandler.h
              HTTPWebinterfaceHandler.h
              IHTTPRequestHandler.h)

>>>>>>> xbmc/Krypton
  core_add_library(network_httprequesthandlers)
endif()
