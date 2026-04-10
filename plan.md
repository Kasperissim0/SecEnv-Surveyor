add details

0.  add credentials for request                | credentials.hpp

1. fetch raw html                              | fetch.hpp
2. find & extract table + convert to json      | process.hpp
3. update internal state                       | main.cpp
4. notify if changes detected                  | notifications.hpp
5. wait alloted time                           | main.cpp
6. back to step 1                              | main.cpp