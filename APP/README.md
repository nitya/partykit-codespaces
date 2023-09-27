# PartyKit Exploration

Created an "APP" directory to try out the Nextjs-PartyKit template. Scaffolded it using:

```bash
$  npx create-next-app@latest partykit-nextjs-chat --example "https://github.com/partykit/partykit-nextjs-chat-template"
```

Ran the dev server using:

```bash
$ npm run dev

> partykit-nextjs-chat-template@0.1.0 dev
> concurrently "npm run dev:partykit" "npm run dev:next" --kill-others

[1] 
[1] > partykit-nextjs-chat-template@0.1.0 dev:next
[1] > next dev
[1] 
[0] 
[0] > partykit-nextjs-chat-template@0.1.0 dev:partykit
[0] > partykit dev
[0] 
[1] - ready started server on 0.0.0.0:3000, url: http://localhost:3000
[0] 🎈 PartyKit v0.0.0-9d532f8
[0] ---------------------------
[0] Build succeeded, starting server...
[pk:dbg] Updated `Request.cf` object cache!
[pk:inf] Ready on http://127.0.0.1:1999 
[0] 
[1] Attention: Next.js now collects completely anonymous telemetry regarding usage.
[1] This information is used to shape Next.js' roadmap and prioritize features.
[1] You can learn more, including how to opt-out if you'd not like to participate in this anonymous program, by visiting the following URL:
[1] https://nextjs.org/telemetry
```

Stopped in this issue: `Error: GITHUB_CLIENT_ID not defined in environment` 

🚧 | **TODO**: [Follow env setup instructions in](https://github.com/partykit/partykit-nextjs-chat-template) to fix the missing env and then run again.