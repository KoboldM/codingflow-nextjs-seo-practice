Video for reference:
https://www.youtube.com/watch?v=wTGVHLyV09M

Notes for SEO Optimization
Use for previewing Metatag: 
1. https://docs.srv.us
2. https://socialsharepreview.com/
3. https://opengraph.xyz/


1. FavIcon
    1.1 Not really needed for SEO Ranking
    1.2 Helps with user experience for tab icon
2. OpenGraph-Image (png)
    2.1 Shown together when pasting link to social media for example
    2.2 Recommended width: 1200x630 pixels
    2.3 Required for overall SEO strategy
    2.4 required filename: opengraph-image
3. Twitter Metadata
    3.1 Recommended card property: summary_image_large
4. Use local fonts
    4.1 In EU, it is illegal to use external fonts because they can extract user's personal IP, which is considered personal data unless there is permission
    4.2 Local fonts will be faster as well, since it is stored in the project instead of fetching
5. NextJS Related Notes
    5.1 Fetching in generateMetadata and Page
        5.1.1 If same url, NextJS only fetches once even if there is a duplicate line, as long as the URL is the same **ONLY WITH FETCH; not with other fetching ways
        5.1.2 Best practice if not fetch, use React Caching
6. You can create images using opengraph-image.tsx
    6.1 Look at docs for more details
7. Use generateStaticParams
    7.1 Pre-fetches everything instantly because all data is fetched at compiled time
8. Sitemap
    8.1 Last Modified - Is important; if every URL has same, Google ignores it
9. Robots
    9.1 You can tell site crawlers what not to look through