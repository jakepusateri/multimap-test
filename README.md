Test concatenation with sourcemaps and how browsers responsd.

    npm run dev

    python -m SimpleHTTPServer


Visit localhost:8080

Through this I conclude the last sourcemap comment, be be it inline external file, is used. All others are ignored

Chrome - shows only sourcemap for foo.js both inline and external
Firefox - shows only sourcemap for foo.js both inline and external
Edge - doesn't parse concatted sourcemap when inline or external, but show sourcemap in non-concatted cases