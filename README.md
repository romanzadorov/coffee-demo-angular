# ShoesDemo

The goal of this project was to create a fully-responsive web-page with fancy elements positioning, creating an overlap effect.

- Different techniques applied to backgroung images, like:
  - background-blend-mode: multiply;
  - background-attachment: fixed;
  - background-repeat: no-repeat;
  - background-position: center center;
  - background-size: cover;
- feature query @Supports to specify declarations that depend on a browser's support for one or more specific CSS features.
- worked with pseudo-elements, like;

  - :hover
  - :focus
  - :after

- Applied CSS Custom Properties, like --clr-inner or --clr-outer to use it as a variable in a product's background: radial-gradient(var(--clr-inner, limegreen), var(--clr-outer, purple));

- To provide responsiveness, I used mobile-first approach with media-queries, so that the page would be compatible on all screen resolutions and all layouts.
