# Apex Technologies: website design demos

Static site, no build step. Deploy the whole folder as-is.

    /            one-page index linking the three designs
    /cinematic/  design 1, dark cinematic (three.js, GSAP, Alpine from CDN)
    /cyan/       design 2, navy and cyan
    /mint/       design 3, mint editorial (31 pages in one file, hash routing)

## Cloudflare Pages

Direct upload: Workers & Pages -> Create -> Pages -> Upload assets -> drag this folder (or the zip).

Git: push this folder to a repo, connect it in Pages, leave the build command empty and set the
output directory to `/` (or the folder name if it sits inside a larger repo).

Everything is relative, so it also works from any subpath or a plain web server.
