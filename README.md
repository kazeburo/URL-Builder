# NAME

URL::Builder - Tiny URL builder

# SYNOPSIS

    use URL::Builder;

    say build_url(
        base_uri => 'http://api.example.com/',
        path => '/v1/entries',
        query => [
            id => 3
        ]
    );
    # http://api.example.com/v1/entries?id=3

# DESCRIPTION

URL::Builder is really simple URL string building library.

# FUNCTIONS

- build\_url(%args)

    Build URL from the hash.

    Arguments:

    - base\_uri: Str
    - path: Str
    - query: ArrayRef\[Str\]|HashRef\[Str\]

# LICENSE

Copyright (C) Tokuhiro Matsuno.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

Tokuhiro Matsuno <tokuhirom@gmail.com>
