# KBOS

a language extention for Perl 5

- object orientation
    - inside out style data encapsulation
    - with 3 layer object model
        1. outer API (public methods)
        2. internal, middle API (private methods)
        3. inner, attribute API (accessors)
    - incorporate classes from other OO systems by usage
    - autogenerated $self, $args and $return (optional)
- complex type system
    - symbolic type names
    - composable types
    - only checked in signatures (args and return values)
        - all arguments are positional and named
        - autogenerated error messages
- separate data flow channel for error messages
- data life cycle system (serialisation)


