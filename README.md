# cstdstring
Why specifically the MSVC 32 bit std::string implementation? Originally started with the intent of generating header files for Geometry Dash 1.92 (which is 32 bit and compiled with MSVC) Geode bindings which requires reading the broma file line by line, if I was writing this in C++, it would've been simple but I wasn't and I sure as hell wasn't going to deal with C strings. <br>
<br>
As close as of a implementation I could make, you can pass the struct to c++ functions expecting a std::string.
