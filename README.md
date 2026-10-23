# Loop invite page

One static page: `i/index.html`. An invite link `https://rc-8055.github.io/i/?c=<code>` opens it; its
button goes to `streaks://invite/<code>`, which the Loop app handles. It holds no keys and calls no
backend. The app's source is in a separate, private repository.

The page shows the inviter's first name and the circle's name when the link carries them (`&from=…&circle=…`), as
plain text only. The store badges are Apple's and Google's official artwork, unaltered (`i/app-store-badge.svg`,
`i/google-play-badge.png`). While Loop is in beta, the App Store badge opens Loop's public TestFlight link and the Google
Play badge opens the internal testing link; swap them for the store listings when Loop is public.
