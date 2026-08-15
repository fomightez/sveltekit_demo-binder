# sveltekit_demo-binder
Binderized SvelteKit Demo Playground.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/sveltekit_demo-binder/HEAD)

-------------------

### How to use

Click the '`launch binder`' badge above to start a MyBinder-served Jupyter session with the SvelteKit Demo already installed and running.   



Once the session launches, do the steps below...

1. Prepare your preview URL. Copy the URL from your browser's address bar. It will look something like this:
   `https://hub.gesis.mybinder.org/user/fomightez-sveltekit_demo-binder-5uzrk280/lab`
   
   Paste it in a text editor and replace the `/lab` part at the end with `/proxy/absolute/5173/`. Keep this modified URL ready.

2. Start the development server:
   ```bash
   npm run dev -- --host
   ```

3. Open a new browser window or tab, paste your modified URL, and hit Enter. Give it about a minute to spin up, and reload if necessary to see your live SvelteKit app!


