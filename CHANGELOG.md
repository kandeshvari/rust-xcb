 * 0.7.2
 rtbo - 02/04/2016
    - fix #14

 * 0.7.1
 rtbo - 29/03/2016
    - module names closer to ffi
    - fix #13

 * 0.7.0
 rtbo - 28/03/2016
    - fix connection with strings (#9)
    - assign response_type in *Event::new (#10)
    - Connection::connect returns Result (#11)
    - Some documentation (#12)

 * 0.6.2
 rtbo - 04/03/2016
    - fix: correct names for DRI2 and 3 FFI constants

 * 0.6.1
 rtbo - 02/03/2016
    - fix: correct names for 'xtest' extension

 * 0.6.0
 rtbo - 22/02/2016
    - xlib_xcb: Connection owns the xlib::Display and calls XCloseDisplay
    - requests accept template slices
    - POD types distinction

 * 0.5.0
 rtbo - 07/02/2016
    - adding xlib_xcb
    - show how to create an opengl enabled window

 * 0.4.1
 rtbo - 07/02/2016
    - generating union accessors
    - handling of bool parameters in the wrapper API
    - rewrite of wrappers structures (pub type instead of struct with base field)
    - module clean-up and export
    - Travis CI

 * 0.4.0
 rtbo/laumann - 03/02/2016
    - first fully functional wrappers
    - rewritten rs_client.py
    - new examples
    - made ffi very close to C
    - fixed wrappers segfaults

 * 0.3.0
 Aatch - 2013
