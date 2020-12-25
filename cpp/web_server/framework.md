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
    
 3. [CrowCpp/crow](https://github.com/CrowCpp/crow)
    
    Advantage:
     - Sinlge-header-only library
     - Extremely easy to use with interfaces
     - Good performance according to [REST-CPP-benchmark] (better than [pistacheio/pistache])
    
    Disadvantage:
     - Does not support fastcgi
     - HTTP2 not yet supported (in progress)
     - Does not have builtin compression support

## HTML template rendering framework: mustache
 1. Implementation in C++ [no1msd/mstch](https://github.com/no1msd/mstch)

[REST-CPP-benchmark]: https://github.com/guteksan/REST-CPP-benchmark
[pistacheio/pistache]: https://github.com/pistacheio/pistache