Test concatenation with sourcemaps and how browsers responsd.

    npm run babel
    npm run concat

OR

    npm run babel-external
    npm run concat-external

    python -m SimpleHTTPServer


Visit localhost:8080

Through this I conclude the last sourcemap comment, be be it inline external file, is used. All others s are ignore

Chrome - shows sourcemap for foo.js both inline and external
Firefox - shows sourcemap for foo.js both inline and external
Edge - doesn't parse concatted sourcemap when inline or external, but passes simple.html (1 file with inline map, no concatting)