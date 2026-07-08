# Getting your site live with a login portal

Everything is built. This is a one-time, ~15 minute setup. After this, you'll have:
- A live URL you can put on Pinterest, Instagram, anywhere
- A private page at `yoursite.com/admin` where you log in and add/edit work — no code

## Step 1 — Put the files on GitHub (free account)

1. Go to github.com, sign up if you don't have an account.
2. Click "New repository." Name it something like `gurashish-portfolio`. Keep it **Public**. Create it.
3. On the new repo page, click "uploading an existing file."
4. Drag in ALL the files and folders I gave you (`index.html`, the `images` folder, the `data` folder, the `admin` folder) — keep the folder structure exactly as-is.
5. Click "Commit changes."

## Step 2 — Connect it to Netlify (free hosting + your URL)

1. Go to netlify.com, sign up (you can use your GitHub account to sign up — easiest).
2. Click "Add new site" → "Import an existing project" → "Deploy with GitHub."
3. Pick the repo you just created.
4. Leave all the build settings blank/default. Click "Deploy site."
5. In under a minute you'll get a live URL like `random-name-123.netlify.app`. That already works — this is your shareable link.
6. Optional: in Site settings → Domain management, you can change that random name to something like `gurashishkaur.netlify.app`, or connect a real custom domain later.

## Step 3 — Turn on the login portal (Identity + Git Gateway)

1. In your Netlify site dashboard, go to **Site configuration → Identity** → click "Enable Identity."
2. Under Identity settings, set **Registration** to "Invite only" (so random people can't sign up).
3. Scroll to **Services → Git Gateway** → click "Enable Git Gateway." This is what lets the login portal actually save your changes back to the site.
4. Go to the **Identity** tab (top of the dashboard, not settings) → "Invite users" → enter your own email.
5. Check your email, click the invite link, set a password.

## Step 4 — Start posting

Go to `yoursite.netlify.app/admin` (swap in your real URL), log in with the email/password you just set. You'll see:
- **Portfolio Work** — add a piece, upload the image, write the title/category/year, check the box if you want it in the big homepage grid.
- **Before / After** — upload a before and after image as a pair.
- **Site Text** — edit your bio, hero headline, contact links, all without touching code.

Hit "Publish" on anything you add — the live site rebuilds itself automatically, usually within a minute.

---

**If any step trips you up, send me a screenshot of where you're stuck and I'll walk you through it.**
