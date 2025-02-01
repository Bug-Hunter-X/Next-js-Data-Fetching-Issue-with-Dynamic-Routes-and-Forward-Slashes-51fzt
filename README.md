# Next.js Data Fetching Issue with Dynamic Routes and Forward Slashes

This repository demonstrates an uncommon bug in Next.js related to data fetching in dynamic routes that contain forward slashes in their segments.  The `bug.js` file showcases the problematic code, while `bugSolution.js` presents the corrected implementation.

The issue arises when Next.js attempts to parse dynamic route segments containing `/`, leading to unexpected behavior in `getServerSideProps` or `getStaticProps`.

**To reproduce:**

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior when accessing specific routes.