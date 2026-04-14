# BAOMAILER website

Static site. Deploy to Vercel as-is (no build step).

## Contact form

The form posts to [FormSubmit](https://formsubmit.co) which forwards submissions to `buildassetsonline1@gmail.com`.

**First-time activation:** After the first submission, FormSubmit emails `buildassetsonline1@gmail.com` with a confirmation link. Click it once to activate the endpoint — after that all future submissions flow through automatically.

If you buy a custom domain (e.g. `baomailer.com`), update the `_next` hidden field in `index.html` to your real thank-you URL, or just leave it pointing at `thanks.html` on the deployed domain.

## Deploy

```
vercel --prod
```

Or push to GitHub and import the repo in the Vercel dashboard.
