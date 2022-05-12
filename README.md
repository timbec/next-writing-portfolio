This is the second iteration of my updated Writing Portfolio, which sources its data from the current site at: https://timbeckett-writing.com. The original site is on Wordpress, and I am converting the WP site into an API, and accessing the data, either through the WP API, or GraphQL. For the moment, it will be the former.

Despite the recent developments in the Gutenberg editor, and the layer of Javascript it allows on top of the Wordpress PHP core, it's still not the optimal solution. I wanted to build a site completely in Javascript, with access to all the attendant components, effects, animations and so on.

I started this site in Nuxt.js (Vue is still a favorite) but 1) I wanted to integrate Typescript and it seemed easier to learn TS and integrate into Next than Nuxt 2) I want people to be able to comment, and while this is still somewhat problematic in Next.js - we have to allow for anonymous comments in Wordpress itself - there seemed to be more ready solutions in Next.js than Nuxt. So Next it is . . . .
