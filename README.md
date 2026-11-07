# Muhammad Taha — Portfolio

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000). Create a production build with
`npm run build`, then serve it locally with `npm start`.

The site uses Next.js 15 App Router, TypeScript, Tailwind CSS v4, and lucide-react.
The resume portrait is stored at `public/headshot.png`.

## Deploy free on Vercel

1. Push this project to a GitHub repository.
2. Sign in to [Vercel](https://vercel.com) and import that repository.
3. Keep the detected Next.js settings and select the free Hobby plan.
4. Deploy. Vercel builds the app and provides a hosted URL; future pushes to the
   connected branch trigger new deployments.

No environment variables are required.

## Animation controls

- `P` pauses or resumes the build animation.
- `A` turns the robot cursors on or off; the preference is saved locally.
- `T` reloads the page and starts the scroll tour after the hero builds.
- `Escape` or manual scrolling stops the tour.
- `?agents=on` forces cursors on; `?agents=off` turns them off.
