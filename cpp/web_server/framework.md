 1. [an-tao/drogon](https://github.com/an-tao/drogon)
    
    Advantage:
     - Has features just like `flask`
     - Support https
     - Awesome performance
    
    Disadvantage:
     - (IMHO) uses `std::function`
     - Doesn't support fastcgi.
     - Does not support HTTP2

 2. [pistacheio/pistache]
 
    Advantage:
     - Have high level and low level API available.
     - precompiled library available in ubuntu
    
    Disadvantage:
     - Does not support HTTP2
     - Does not have builtin compression support
    
 3. [CrowCpp/crow]
    
    Advantage:
     - Sinlge-header-only library
     - Just depends on boost
     - Extremely easy to use with interfaces
     - Built in JSON support.
     - Mustache based templating library (crow::mustache).
     - Middleware support for extensions.
     - Good performance according to [REST-CPP-benchmark] (better than [pistacheio/pistache])
    
    Disadvantage:
     - Does not support fastcgi
     - HTTP2 not yet supported (in progress)
     - Does not have builtin compression support

 4. [Stiffstream/restinio](https://github.com/Stiffstream/restinio)
    
    Advantage:
     - Single-header-only library
     - Support comparsion
     - Support HTTPS
    
    Disadvantage:
     - much harder to use than [CrowCpp/crow]
     - has a lot dependencies

 5. [emweb/wt](https://github.com/emweb/wt)
    
    GPL2 licensed but has another paid private available.
    
    It depends on boost and optionally depends on openssl and etc.
    
    More complex than [CrowCpp/crow].
    
 6. [eddic/fastcgipp](https://github.com/eddic/fastcgipp)
    
    Have a set of low-level APIs but support fastcgi and SQL connection.
    
    GPL 3.0 licensed, C++ 11 code.
    
    I do not like the API.
    
 7. [treefrogframework/treefrog-framework](https://github.com/treefrogframework/treefrog-framework)
 8. [civetweb/civetweb](https://github.com/civetweb/civetweb)
 9. [artyom-beilis/cppcms](https://github.com/artyom-beilis/cppcms)    
 
 10. [kristapsdz/kcgi](https://github.com/kristapsdz/kcgi)
    
     ISC license, provides a lot of C APIs.
 
## HTML template rendering framework: mustache
 1. Implementation in C++ [no1msd/mstch](https://github.com/no1msd/mstch)

[REST-CPP-benchmark]: https://github.com/guteksan/REST-CPP-benchmark
[pistacheio/pistache]: https://github.com/pistacheio/pistache
[CrowCpp/crow]: https://github.com/CrowCpp/crow
