# What's new in Nav8

## 19.59
_2026-10-29_

### Fixed
- Fixed a crash that happened when sending a chat message.
- Fixed sign-in during setup failing repeatedly when a leftover, unreadable saved token from an earlier install was present.

## 19.58
_2026-10-29_

### New
- **Cross View 2.0:** organize panes into named screens (up to six panes each), with an edit mode to drag tabs in from the strip and dock, swap or move panes between screens.
- **Incognito tabs in any chat**, each with its own login, and the agent can see and open them.
- **Nav8 for Chrome:** your tabs and pinned sites open in Chrome, with a chat that looks like Nav8's, a New chat button in the header and support for glass themes.
- **iMessage in the Inbox**, just like WhatsApp: incoming texts show up as Inbox items with a full conversation page and gated replies.
- **iPhone and big screens:** a flat chat list with New chat first, an Inbox that opens as a page, your built mini apps in the Pinned grid, and a split view with chat and live tab side by side on iPad and foldables.
- **Chat agents get GitHub tools** through your Mac's gh login, with an approval card for anything that writes.
- **Sort All Chats** by recent activity, name or date created.
### Improved
- Tasks now outlive their chat, and held tasks tell you why they're waiting.
- Approvals are clearer: cards show a short summary with "View all", expiring ones send a reminder, and decisions appear in Approvals › Recent.
- Reset asks first, can forget what the agent learned in the chat, and can be undone for 10 seconds.
### Fixed
- Launch no longer freezes, and "Organize Tabs with AI" no longer erases chats.

## 19.57
_2026-10-25_

### Fixed
- Signing in with Google during setup now works with whichever Google account you choose.

## 19.56
_2026-10-24_

### New
- **Home page in the Inbox:** A daily view with your day's timeline across all your Google calendars, top priorities with the reason for each, decisions waiting on you, what's due today or overdue from ClickUp, and who you need to get back to. You can reset the day and undo the reset.
- **Inbox on iPhone:** Your full Inbox now appears on your iPhone, with filters, threads, replies, approvals, and done, read and snooze. A Today board is included.
- **Nav8 for Chrome:** A side-panel companion for Chrome that pairs with Nav8. Install it from Connect Chrome › Install….
- **Inbox opens in tabs:** "Open in <App>" opens the original item (the exact Gmail email, or a WhatsApp-style chat) in a tab inside the Inbox. Notifications from agents open their chat as an Inbox tab.
- **Auto-done:** Inbox items close on their own once you've handled them, for example by replying to the email or WhatsApp message or after a meeting ends. Approvals are never closed this way, and undo brings the item back as unread.
- **WhatsApp tab upgrades:** Quoted replies, reactions, and hover reply and react controls. Bubbles are lighter and scroll more smoothly.
- **Two ways to handle every item:** Have the agent do it, or do it yourself.
- **Hiding pages in Arrange:** Uncheck pages in Arrange to hide them, and use Show all to bring them back, for each chat.
### Improved
- Task reports and monday notifications open the exact email, chat, or item they refer to. Banners are limited to three, followed by "+N more".
- Inbox items are titled with the task, such as "Inbox cleanup", instead of the app name.
- The Inbox is quieter. Tasks keep their own card, and runs where nothing happened no longer show up as items.
- Agent replies now need only one approval. The send card shows the draft and is the approval.
- The Inbox sidebar badge is a small round count and is part of the button's click area. Tabs split the strip equally, and a lone page tab stays a normal tab size.
### Fixed
- WhatsApp sends no longer guess a recipient. If a name fits several chats, you'll be asked "Which X?" and shown each chat's number.
- A long WhatsApp line no longer shrinks the browser window.
- Meeting prep skips events with no other guest.
- Sign-in windows for Google, Slack, and Dropbox no longer open blank or invisible.
- A typed reply now settles a waiting question or approval card.
- Failed connect attempts in Settings now show the reason.
- Chat read-aloud uses the neural voice again.

## 19.55
_2026-10-22_

### New
- Connect your Base44 Superagent: ask it from Nav8 chat, let it use Nav8 as a tool, and publish a mini app to Base44.
- "Analyze this page" in the page menu gives you the result as a single chat card, remembered for each page.
- File > Archived Tabs lists auto-archived tabs so you can restore them, and a restored tab goes back to its original group when it still exists.
- Upload a file or folder from your Mac to Google Drive and file docs into folders by asking the agent.
- Right-click a pinned app to Open in Folder or Share it.
- Answer agent questions from your iPhone, and see the whole turn on your phone, including a chat's terminal tabs.
### Improved
- One Google sign-in during setup now creates your Nav8 account and gives the agent access. "Not loading?" reopens the consent already in progress.
- Meeting prep appears as one row per meeting in Proactive and only refreshes when your meetings change.
- Proactive plays now work on WhatsApp, ClickUp and monday, and keep running when there are many findings.
- Setup wording is simpler for non-coders, and Veezee moves out of the chat into the apps list.
### Fixed
- Find on Page in the page menu opens the same find bar as Cmd+F, and its Zoom In/Out/Actual Size now work.
- Saved per-site zoom is reapplied when you navigate back to a site.
- Removed the floating Claude Code pill that covered the chat composer.
- New users are no longer asked for the Chrome keychain on every launch.
- Slack unread dots clear when you disconnect, and Slack stops checking for unread messages.

## 19.54
_2026-10-21_

### New
- Nav8 can now prepare several pieces of work ahead of time and show them together, so you can review everything and approve it all with a single "Approve all" button.
- Nav8 keeps following up on email items it has prepared until you've answered them.

## 19.53
_2026-10-20_

### New
- Organized projects, available behind a switch in Settings.
- Mini apps on iOS: a new Apps tab runs the apps you've built on your Mac.
- Inbox cleanup suggestions: the agent proposes what to tidy but never acts on its own.
- Daily digest email sent to yourself.
- Reply directly to an agent message.
### Improved
- Proactive alerts now ping only for a new important item, up to 3 times a day.
- The Control Center panel is now the home for proactive task updates.
- Remote watch keeps watched hidden tabs visible and streams a sharper Mac-to-Mac picture.
- iOS chat tabs show one landscape tile per row so Mac thumbnails are no longer cropped.
- Question cards now fit the pane and can be closed with ✕.
### Fixed
- Fixed a freeze that could happen at launch.
- The chat toggle pill now appears above the sidebar overlay.
- After a restore, Backup & Move points you to Connections instead of listing every secret.
- Group notes now land in the group that created them, and Google tries the owning account.

## 19.52
_2026-10-19_

### Improved
- Removed the red scheduled-agents badge from the chat header for a cleaner look.
### Fixed
- Fixed an issue where some Google actions run by the agent could ignore the options you gave them.
- Fixed a brief visual glitch when pressing the pill button in the chat pane.

## 19.51
_2026-10-19_

### New
- Use Nav8 from other AI apps like Claude Desktop, Cursor, and Codex with one click in Settings. Those apps can read your chats, inbox, and downloads, open terminal tabs, run coding agents, and work with connected apps like ClickUp, monday.com, and Dropbox. Sends and deletes always ask for your approval first.
- Approve once up front: the agent lists the steps that need your OK in a single card, and skips any step your own typed words already approved. Money steps are always excluded.
- You can reply to an approval card by typing in Telegram, and you're told if a card expires.
- The agent can sign in to sites with your own login and fill one-time codes from your Gmail or Messages, without the AI ever seeing your password or code.
- Cross View now works in Simple Browsing: add, drop, and pop out panes, flip between pages with dots, and swap panes with the new Arrange button. Your Cross View survives a relaunch.
- Chat tables now show as a real grid, and reply text matches the iPhone app.
- When the agent is working, your page gets a sweeping ring of light around its edge.
- The Remote section can be resized, and remote pages are sharper, show the whole page, and can wake sleeping tabs with mouse and keyboard control.
- Crashed coding agents offer Resume, Start fresh, or Drop, and a terminal you open yourself gets its own agent card.
### Improved
- Restarting Nav8 opens your top chat under Favorites instead of General.
### Fixed
- Fixed a crash when connecting Google and a window that could grow off-screen.
- Fixed a startup freeze on launch.
- Links opened with Cmd-click or middle-click now open in the background, and popups no longer close unexpectedly.
- Background tabs now sleep to save resources.
- Approval cards now show every recipient, including cc, along with the full message.
- Sidebar fixes: new groups appear at the top, "New chat" and "See all" stay pinned at the bottom, and hover and selected rows look right.
- Toolbar icons keep your theme's tint, and chat question cards follow your theme.

## 19.50
_2026-10-14_

### New
- Each coding agent Nav8 starts now gets one live card that shows its progress in your chat.
- If you point Nav8 at a folder it can't use yet, it asks you once on a card instead of repeatedly.
### Improved
- Each chat now keeps its own record of its coding agents, so they stay organized per conversation.
### Fixed
- Terminal tabs no longer freeze when idle while the shell is still running.
- Nav8 can drive the coding agents it starts again.
- Fixed agents getting stuck waiting for approval, stray text appearing after an agent stopped, and empty agent cards.

## 19.49
_2026-10-14_

### New
- Chat pane minimize and expand: a redesigned pill sits on the seam between the sidebar and the page. It brings the chat back when it's hidden, and the X on the chat pane now minimizes it.
- Minimizing a chat shows a live reply popup. Hovering a chat in the icon rail also shows it.
- Collapsing the sidebar now brings back the icon rail instead of showing nothing.
- Control another Mac now lives in the utility bar. Pinned + now lets you build an app or add a chat.
- Remote control of another Mac now shows the chat in the chat pane with the live screen on the right. Chat bubbles, the composer and tabs look like the real thing. Video quality is higher for Mac-to-Mac sessions.
- A pinned app on your Mac now opens its chat on your phone too.
- Back with no page history now stays on the current tab. You can switch to jumping tabs in Settings.
### Improved
- Redesigned chat look: a new status spinner, selected rows that blend into the chat panel, and a restyled header.
- The address bar now centers over the page itself.
- Windows resize more smoothly, and pages learn their new size as you drag.
- Signing in with Google now asks for the same permissions from every place you start it.
### Fixed
- Fixed a crash on launch, and a crash when using the chat expand button.
- A pasted Claude API key now counts as Claude connected during setup.
- Fixed hover highlights that lagged or stuck in the chat sidebar, a stray colored bar in the chat header, and a duplicate tab bar when the sidebar peeks open.
- If Messages on your Mac fails to connect, Nav8 now points you to the Full Disk Access fix.

## 19.48
_2026-10-09_

### Fixed
- Pairing a Mac with Nav8 Remote no longer makes the window grow off-screen.
- Pressed buttons and controls now return to full size, even if Reduce Motion is switched mid-press.
- Tab colour matching (chameleon theme) is smoother. It no longer overlaps transitions or picks up colours from a tab you've left, and it's less likely to cause stutters.
- Tabs that were unloaded to save memory are now recognised correctly when you switch back to them.
- Memory cleanup is less aggressive on idle tabs unless your Mac is under critical memory pressure.
- The toolbar overflow popup now closes reliably.
- Onboarding now offers to connect apps, skips only the questions you've already answered, and ends the group step cleanly.
### Improved
- The installer window now tells you to drag Nav8 onto Applications, with a straighter arrow.

## 19.47
_2026-10-08_

### Fixed
- A Google account saved only in your keychain now shows up in Settings and can be reconnected.
- Connectors that run through uvx now start reliably.
### Improved
- Updated the built-in AI agent components (Claude Code, Codex, OpenCode) to their latest versions.
- Updated WhatsApp connection support to the latest version.
- Updated speech transcription and browser automation components to their latest versions.

## 19.46
_2026-10-07_

### New
- Control one Nav8 desktop from another with remote control mode.
- The phone companion can now handle sign-ins, codes and captchas, and it has an Active view, encrypted push alerts and one-tap favorites.
- Agents can now read YouTube video transcripts.
- Agents read web pages more cleanly, so feeds keep every post.
- Delete a task straight from its row in the Tasks panel.
### Improved
- Opening a chat shows the newest messages first.
- Sends, shares and moving email to Trash always ask for your approval first, and the result shows in the chat afterward.
- Replies stream as they are written, and Hebrew replies read right to left.
- Connected Telegram, Mac Messages, WhatsApp, Slack and Notion now reach your agents reliably.
### Fixed
- Opening a long Hebrew chat no longer freezes the app.
- Removing a Google account now revokes its access and deletes its token, and it can't affect another account.
- Auto appearance now follows macOS, and sidebar pills recolour correctly when you switch themes.
- Scheduled tasks run reliably, reminders stay in the chat that made them, and a reminder is never set for a time you didn't give.
- Quitting saves your cookies and no longer reports a crash.

## 19.45
_2026-09-28_

### New
- Connect X (Twitter) natively, with support for multiple accounts.
- Connect GitHub through the GitHub command-line tool.
- Twilio is back as a second phone option, available for every profile.
- Use several Macs with one iPhone companion; switch between them without mixing up chats or tabs.
- Quick 5-step walkthrough of the sidebar and toolbar when you first get started.
- On iPhone, start chat tasks, open tabs in place, and view live views full screen in landscape.
### Improved
- The iPhone chats "All" view now looks like the Mac sidebar.
- The iPhone tabs button is always available, and notification and tab grid taps behave more predictably.
- New chats on iPhone now start with the task first.
- Google accounts can always be added.
- iMessage setup now checks for Full Disk Access and tells you if it's missing.
### Fixed
- WhatsApp connection now finishes as soon as pairing completes instead of up to 5 minutes later.
- The New Tab toggle in 360 views no longer hangs.
- Pages wider than the iPhone screen no longer scroll sideways into empty space.

## 19.44
_2026-09-28_

### New
- **360 view:** Get the full picture on a topic, with sources chosen to show disagreement and every side laid out on a designed page. Each side has its own colour, and there's a perspective dial.
- **iPhone companion:** A new Activity tab shows live agent work, items that need you, and your Mac's notifications.
- **iPhone browser:** Real phone tabs, a tab switcher, back and forward buttons, and a clear button. The tabs grid is available from the app root.
- **Phone chats on your Mac:** Chats you start on your iPhone now show up on the Mac. Unnamed chats take the name of their first tab.
- **360 on New Tab:** There's now a 360 toggle on the New Tab page.
- **Delete built apps:** You can delete an app you built right from its pin.
### Improved
- **Tell me about:** Results now appear on Nav8's own results page, laid out like a news homepage.
- **iPhone chats:** Replies show Markdown and tappable links. Links in a reply open on your Mac. Agent notifications now include the chat name.
- **Setup:** Onboarding now works with a single AI, and the setup chat works with every AI.
### Fixed
- **Editing built apps:** Editing an app now shows its preview.
- **Approvals:** The approvals panel shows what Nav8 did, however it was approved.
- **Closing tabs:** ⌘W now closes tabs the same way as the close button.
- **Favorites:** Clicking a context-menu item on a favorite now works.

## 19.43
_2026-09-27_

### New
- **iPhone companion app:** Pair your iPhone with your Mac to follow your chats live, send messages from your phone, approve actions, and get push notifications and Live Activity updates.
- Start a new chat from your phone. It's created on your Mac.
- Watch the agent's live page on your phone and stop it from there.
- See your Mac's tabs on your phone, with real thumbnails for sleeping tabs and live tiles for active ones. Phone browsing is tied to the chat.
- Browse on the iPhone app without pairing. Pair later from Settings, unpair, or switch Macs.
- Hover over a chat in the list to archive or delete it. There's also a See all page and an auto-archive setting.
- **Erase All Nav8 Data** in Settings works as a factory reset. Cancel is the safe default.
- Advanced setting to run OpenAI models through OpenCode instead of Codex.
### Improved
- The bell now shows one card per chat for agent notifications, and notifications show the chat group's name.
- The iPhone app has a refreshed look with glass effects, theme colors that match your Mac, and clearer text.
### Fixed
- Starting a second build now asks before it stops the first.

## 19.42
_2026-09-25_

### New
- Coding agents now have a card while they run, so you can act on them directly from the chat.
- Connected coding agent sessions are pinned to the chat header.
- Conversations with coding agents now go both ways, and you can steer an agent mid-task.
- With two AIs signed in, Setup asks which one runs new chats.
### Improved
- When your chosen AI can't answer, Nav8 tells you why and offers another AI or a retry.
- Coding agents now say what they're waiting to do instead of just saying they're waiting.
- Closing a terminal that's running a coding agent now asks first.
- Claude sign-in opens a single browser tab, the one that connects Nav8.
- Setup's Continue button lights up only once the step is done, and Screen Recording is now optional.
- Setup now returns if you quit it before finishing, and it only finishes once every step is done.
### Fixed
- Long steering messages to coding agents are no longer cut off, and they now send properly.
- Signing in to ChatGPT no longer switches Claude off.
- Failed page loads no longer crash the tab.

## 19.41
_2026-09-24_

### New
- Added Claude Opus 5.5, now the default model wherever Opus 5 was before.
- The agent can now open a terminal for you on request.
- Added a tool for creating Paper docs in Dropbox.
### Improved
- Nav8 now warns you with a clear message when an app's access is denied, and it recovers on its own after a connection problem.
- Telegram messages that don't belong to a specific group now go to General instead of being blocked.
- The agent's Claude Code tools repair themselves automatically if they break.
- Error messages from connected tools now name the real problem instead of showing a blank failure.
### Fixed
- Fixed crashes that could close Nav8 unexpectedly, including one triggered by database schema lookups.
- Quitting Nav8 no longer disconnects your WhatsApp Web session.
- Follow-up messages you send while the agent is working in a group chat are no longer dropped.
- Scheduled-task cards now show up in the right chat, and editing a task now updates it instead of creating a duplicate.
- Fixed several App Builder problems: Go Live after a restart, preview crashes mid-build, and drafts left unfinished when Nav8 quits.
- Fixed Gmail panes that lost your account or opened the wrong view when reloaded.

## 19.40
_2026-09-22_

### New
- Back up your Nav8 setup and restore it later, even without the app installed.
- The agent can now take actions on web pages on its own, and hands control back to you instead of making purchases.
- The agent can answer questions from what it has learned about your email and documents, such as your car details and policy PDFs, instead of searching your mailbox each time.
- Nav8 can notice when a regular routine of yours stops happening.
- Fast automation is now an optional setup step you choose to turn on.
### Improved
- Calendar's unified view now covers the full day, midnight to midnight, instead of 7am to 9pm.
- Automated page actions are much faster, dropping from over 10 seconds to under 1 second.
- Ambiguous dates in your records are now worked out from context instead of being rejected.
- Cross View now has its own row in side tabs.
- Settings are simpler, with the agent's inner workings kept out of sight.
### Fixed
- Terminal tabs are named after their branch again.
- Fixed terminal display problems caused by missing terminal information.
- Starting a fresh chat now properly ends the previous Builder session.
- A plan limit message is no longer mistaken for a rate limit.

## 19.39
_2026-09-20_

### New
- Coding agents: Nav8 can start a coding agent for you in a terminal tab you can see. It works in its own workspace rather than your repo, and it reports back in the chat with a sound when it finishes.
- Terminal sessions now keep running after you close Nav8, and the tab comes back when you reopen the app. Terminal tabs can also live in Cross View and open directly in a folder.
- Choose your AI engine during setup. The Setup window asks what you already pay for and guides you from there. OpenCode now ships with Nav8, including support for your own local model.
- Approve up front. Nav8 asks once for everything it needs, so you can approve and walk away. Approvals now last 72 hours and show what you're approving.
- Messages and GitHub integrations. Sending a message always gives you a chance to refuse it.
- Nav8 can learn what a site can do from a single demonstration and reuse it later, and it tells the agent what a site offers before it picks a tool.
### Improved
- Settings are reorganized into nine panes with search. Connections now list MCP servers, and you can see which engine each setting applies to.
- Pinned app tiles and the new-tab dock show each site's real icon. Messages has its own pane.
- A new chat opens at the top of the sidebar. Deleting a chat lands you on the one next to it.
- Sidebar groups show when approvals are waiting.
### Fixed
- Terminal resizing works reliably again, and a disconnected tab keeps trying to reconnect. A shell that can't start now tells you why instead of leaving a blank tab.
- A Google account you just added now shows up in Connections.
- Fixed a crash caused by file writes.
- Approval cards now appear in the chat they belong to, not whichever chat is on screen.
- The chat composer's lane pill no longer overlaps the buttons beside it.
- Fixed a case where clearing empty tabs deleted a chat's Cross View home.

## 19.38
_2026-09-14_

### New
- Your agent can now make phone calls for you. It shows who is being called and why before dialing, tells you the cost up front, buys a number only once, and never repeats a call. Phone tools appear only after you've set up your line.
- Phone setup can now be left partway through and picked up later.
- Custom connectors can now hold their own credentials, not just the built-in ones.
- Messages that mention someone your agent already knows about now bring that background into the conversation, including in group chats.
### Improved
- Telegram updates are shorter and marked with icons, and you can reply to direct messages and mentions from Buzz.
- Connectors are more reliable: they start up independently, restart automatically if they stop, and are checked before use.
### Fixed
- The agent no longer decides a site "can't be automated" after a single bad attempt.
- Fixed agents getting stuck in loops after being told a page reference was out of date when it had simply not been issued yet.
- Fixed a case where a failed lookup of a helper tool was remembered and kept the agent from using it.

## 19.37
_2026-09-10_

### New
- Cards (Kerdas) are now the single card system: the agent's highlights, Monday board cards and the ClickUp confirmation card all appear as cards you can click, tell what to change, and watch update.
- Cards can show pictures (even offline), have buttons that carry an instruction for the agent, and can be moved to another Mac (buttons arrive switched off).
- Ask the agent right on the page instead of in a grey box; press Esc to take back a card that is still being written.
- Choose Codex as the agent runtime per chat, with sign-in in a new Settings pane that gathers all agent sign-ins in one place.
- Fleet now lists your chats with name, live status and last activity; a chat row opens that chat.
- First launch now has clear privacy switches on the Welcome screen and in Settings → Privacy.
### Improved
- The agent asks for confirmation once per task, then stops asking, and respects your own consent settings.
- Nav8 Community has its own branding, rules, opt-in direct messages with a directory of who opted in, and a support bot. Switching channels is instant, DMs arrive live, and clicking a person opens the conversation.
- Email, Slack and calendar watchers now check for new items before starting the agent, so nothing runs when nothing has changed.
### Fixed
- Fixed an issue where messages sent to a busy chat appeared twice.
- Fixed approvals in different chats interfering with each other.

## 19.36
_2026-09-03_

### Improved
- Faster startup: fixed a CPU spike that could happen right after launching Nav8.
- Attachments you add are now stored more privately on your Mac, and old ones are cleaned up automatically after 24 hours.
- Password manager and autofill are more secure and reliable.
### Fixed
- Fixed a crash that could occur when windows were closed.
- Actions the agent performs on a page are no longer repeated by mistake.
- Fixed the agent sometimes responding to an outdated request.

## 19.35
_2026-09-02_

### New
- Built apps now live in the chat that created them instead of getting a group of their own, and Go Live keeps the app in that chat.
- Cmd-K has an "Open in this chat" option for built apps, taking you straight to the app full-size.
- New installs default to the Monday + Prism theme.
### Improved
- Switching between chats and groups feels faster: pages stay warm, the grid no longer redraws while resizing, and the switch shows where you're going.
- Nav8 keeps more pages loaded on machines that can handle it, so tabs reload less often.
- Clicking Gmail or Calendar opens instantly instead of waiting on the network.
- Cmd-K shows one row per app and no longer lists empty app groups, and each result says what it is.
- Nav8 now quits cleanly when asked to shut down, and leftover background processes from a crash are cleaned up at launch.
### Fixed
- Starting a build no longer pulls you out of your chat, and the finished app is shown once it's ready. The Go Live button appears whenever the app offers it.
- Saying "yes do that" to the builder now starts the build, and the composer stays in builder mode.
- "Show me inbox" now opens Gmail instead of a random website.
- A reminder that can't be saved now tells you instead of silently disappearing.

## 19.34
_2026-08-31_

- Behind-the-scenes improvements and fixes.

## 19.33
_2026-08-30_

### New
- Each chat now has its own tasks. The chat pane has a task strip, a slide-in detail view and a built-in "New task" wizard. A task belongs to the chat that created it.
- The agent can propose a task, and it's saved only after you confirm.
- Spotlight-style ⌘K palette with an Apps grid. ⌘N opens a Quick Chat.
- Group knowledge: Nav8 remembers useful context from Slack, WhatsApp and your group chats, and uses it to answer later.
- The sidebar shows activity dots: red when waiting on you, yellow when working, green when done.
- You can drag the sidebar wider, and its contents resize with it.
- Typing in a new tab now tells URLs, searches and AI prompts apart. "Open <site>" requests are instant.
- ClickUp and Dropbox integrations. The Apps grid now needs sign-in.
- Chats you haven't used in 5 days are tucked out of the sidebar.
- New Welcome chat group for new users.
### Improved
- Switching between chats and Cross View is smoother, with a cleaner crossfade and fewer flashes.
- Chats now run at the same time without mixing up their live status.
- Chat text is easier to read, with a larger body size and tighter headings.
- Nav8 always asks before an irreversible action. You now see one approval card per action instead of two.
### Fixed
- Approving an action from Telegram now actually runs it.
- Answers are no longer lost when a turn ends with a question.
- Uninstalling an extension now works.
- Fixed two Cross View crashes. A corrupted saved chat board is rebuilt instead of crashing.

## 19.32
_2026-08-13_

- Behind-the-scenes improvements and fixes.

## 19.31
_2026-08-12_

### New
- Password Manager: autofill saved logins right in the field, open a site and sign in in one step, and a new toggle in Settings to turn it on or off.
- Gmail replies now stay in the same thread.
- The Nav8 bot now shows up as a person you can message in Buzz.
### Improved
- Faster tab switching, thumbnails, and chat history loading, with less lag when many conversations are saved.
- The minimized sidebar now shows all your groups (not just 20) and updates properly when groups change.
- Typing `localhost:3000` in the address bar now opens the page instead of searching Google.
- The inbox auto-refresh now actually refreshes every minute.
### Fixed
- Fixed a crash when pressing Done on an empty recording.
- Fixed a crash that could happen when a browser tab was being closed.
- Fixed Disabling a mini-app permanently deleting it and its data.
- Fixed scheduled tasks and reminders not running with their own instructions, and notifications now open the right agent thread.
- Fixed agent automation deleting your open tabs or leaving large numbers of stray tabs behind.
- Fixed bookmarks being lost if they failed to load, and groups you named losing their names after a restart.
- Fixed share links not adding the group to your sidebar.
- Fixed direct messages in Buzz showing "pending" after sending, and channels going permanently dead after long histories.

## 19.30
_2026-08-05_

### New
- Group chats can now be owned by a group (beta), and deleting a group cleans up its chats.
### Improved
- Home email now loads faster and works with Google accounts that are set up only on your Mac.
### Fixed
- Custom connected servers that were working are no longer wrongly shown as needing sign-in.
- Google accounts with expired or broken credentials now show "Reconnect" instead of looking connected.
- During setup, the second Google sign-in is no longer skipped for the account you sign in with.
- Inbox emails that couldn't be read at first are no longer lost; they're retried automatically.
- On-page pills and cards now appear only after the page has finished loading.

## 19.28
_2026-08-03_

### New
- Onboarding now has separate steps for setting up Veezee and Screen Recording, making each easier to follow.
### Improved
- Ad and tracker blocking is now off by default, and you'll see a warning before you turn it on.
- Onboarding no longer includes Notion for now.
### Fixed
- Signing in to Google accounts works again after a bug broke sign-in across Google services.
- Your second Google account now shows its own mailbox instead of your primary account's.
- The integrations card in onboarding now shows all 11 options, and WhatsApp can be opened from it again.
- WhatsApp no longer shows as "connected" when only the agent link is set up.
- The General group can no longer be closed or deleted.
- Fixed an issue with cookies and redirects that could cause some pages to load incorrectly.

## 19.27
_2026-08-03_

### New
- Buzz now supports in-app direct message threads, with participant search and pending conversations.
- The password manager can import from a file (including 1Password .1pux exports) and has a field for one-time-code (TOTP) entries.
- The password manager now offers to save passwords when you sign in to a site.
- The agent can delete Google Drive files, add or delete Slides, and update or delete Google Tasks.
### Improved
- Buzz channel homes and the team roster have been polished.
- When tracker blocking causes a blank page, Nav8 now explains why and offers to load the page anyway.
- Screenshot failures are now reported to you and the agent instead of silently failing.
- Follow-ups opened from the app now stay in the same tab group.
### Fixed
- Fixed a crash affecting Gmail users.
- Fixed Google sign-in sending non-primary accounts to the wrong account slot, and a Gmail issue that could cause a login mismatch.
- The agent can now access the Gmail of the account you signed in to Nav8 with.
- Passwords are no longer written to a diagnostic log.
- The agent no longer takes over your own tab when it isn't assigned to it.

## 19.26
_2026-08-01_

### New
- Buzz channels get a native, redesigned look with one-click connect, a workspace app view, and a built-in thread panel.
- Type @ in Buzz message boxes to mention people with autocomplete.
- Opt in to the Personal Knowledge Graph, with a one-time deep import of your full mailbox.
- The Knowledge panel now has separate Map and Lists modes, and it remembers your choice.
- Approve requests directly from Telegram with actionable messages.
- Agents can now work together with Buzz, and conversations keep their own scope.
### Improved
- Messages in Buzz appear instantly when you send them.
- Better detail captured from email, Slack, calendar and receipts, with a longer 36-month history window.
- Google sign-in now asks for fewer permissions.
### Fixed
- Fixed a crash when launching the app.
- The password manager popover no longer collapses to a thin sliver.
- The browser tab now closes on its own after you connect a Google account.
- Setup no longer claims Gmail is connected when you've only signed in to Nav8.

## 19.25
_2026-07-30_

### New
- A built-in password keyring with a toolbar button, plus import and export, replaces the old password manager.
- Connect Buzz using the key from your Buzz.app, with clearer error messages if something goes wrong.
- Opt in to the Personal Knowledge Graph during onboarding or from the Knowledge tab.
- Import your whole mailbox in one pass to build your knowledge graph from past email.
- The Knowledge panel now has separate Map and Lists views, and it remembers which one you last used.
### Improved
- Better extraction of people, events and receipts from email, Slack and calendar, with a fallback when Gmail isn't connected directly.
- Deeper email history, covering the last 36 months, with better company grouping and cleaner names.
- Chat approval cards now appear and can be answered directly in the conversation.
### Fixed
- "Install Update and Relaunch" now works, and crash recovery is working again.
- Fixed a crash that happened when onboarding finished.
- The ✕ on chat approvals now dismisses them.
- Pages without their own styling no longer show a darkened background.

## 19.24
_2026-07-27_

### New
- Monday boards now open as focused views: the Monday left pane is hidden, and board insights appear as in-page cards on the page.
- Monday groups now map to boards and folders, with quick navigation and folder icons.
- Added a presence indicator that shows when the agent is working on the page without blocking your clicks.
- Approving in your own words (such as "I approve" or asking to make a phone call) now counts as approval for that turn.
- The agent can now learn how to use a site and reuse that knowledge. Ordering on Wolt is faster and more reliable.
### Improved
- Switching tabs is now an instant cut with no blank flash.
- Approval prompts are simpler: you now see a single approval card, and routine tools no longer ask every time.
- The agent handles consent and cookie banners automatically after loading a page.
- The agent uses far less context on large pages, so long tasks run more smoothly.
- Contact and people syncing is faster and more accurate, with real per-person interaction counts and richer name and title details.
### Fixed
- Fixed Monday syncing using up the whole daily API budget.
- Fixed Monday boards sometimes landing on the login page or the wrong tab.
- Fixed checkboxes and radio buttons in pop-ups that the agent couldn't click.
- Fixed sign-in sessions being lost after restarting the app.
- Fixed contact syncing getting stuck for hours.
- Fixed Google Workspace tabs for multiple accounts not showing the right account.

## 19.23
_2026-07-22_

- Behind-the-scenes improvements and fixes.

## 19.22
_2026-07-22_

### Fixed
- Fixed Claude subscription sign-in so it correctly saves your login token, rejects invalid ones, and shows a clear message when authorization fails.
- Fixed pins on boards with repetitive layouts (like Monday boards) so they now land on the correct item.
- Improved account setup so the agent's business profile and owner details work the same way for every user.

## 19.21
_2026-07-22_

### Improved
- The browser agent is more reliable at completing multi-step tasks like filling a cart: it now prioritizes finishing the job correctly over finishing quickly.
- The agent finds buttons, fields, and links on a page more accurately, and handles dropdowns and waiting for page content better.
- The agent recovers more smoothly when a step is rejected or a page changes mid-task, and rejected steps no longer use up its action allowance.
### Fixed
- Fixed Monday boards where the page toolbar could hide the entire board view.
- Fixed an issue where the agent could fail to read a page that was still loading or had changed.
- Fixed a problem where related contacts or accounts were not being merged correctly.

## 19.20
_2026-07-21_

### New
- Automation can now plan a task first, then run it, and it can save successful flows so it handles the same site faster next time.
- Monday boards now show board insights as cards right on the page, replacing the old floating pill.
- Monday board groups open in a focused view with Monday's left pane hidden.
- Sign in with your Claude Code subscription during onboarding, with a fallback to your system browser if "Sign in with Claude" doesn't open.
- Onboarding now includes a Monday connection step. It also has smarter name and company detection and a skip option on every step.
### Improved
- Settings now split into Profile (your editable details) and Accounts & Connections. Profile fields are grouped into aligned sections.
- Automation works faster on its first run after launch and handles page loads and page changes more reliably.
- Your contact and relationship map now understands who you are and how close each person is to you. It labels people by role and cleans up duplicate and sender names.
### Fixed
- "New Chat" now reliably starts a fresh conversation.
- Renaming your agent no longer makes it refuse requests.
- Monday groups stay tied to their board, and stray home and login tabs are cleaned up.
- Fixed WhatsApp status and typing-jump issues during onboarding.

## 19.19
_2026-07-21_

### New
- Sign in with your Claude subscription is now available to everyone by default.
- Nav8 can now learn from your Monday.com, Slack, and WhatsApp content, so the agent knows more about your work and contacts.
- Long-running automations stay on track better, and the agent's task progress now shows up in the native progress display.
- Pressing Setup in onboarding now shows a quick recap of your choices instead of asking everything again.
- Diagnostics now explain why the Claude subscription card is hidden.
### Improved
- Monday.com boards and folders now appear as groups, with matching quick navigation, routing, and folder icons.
- Onboarding questions are personalized to your answers.
- Failed page loads during agent automation are now reported clearly, and page navigation allows more time before timing out.
- Sync results are now clearly visible, and your knowledge graph is built once after all new content is imported.
### Fixed
- Existing users are no longer asked onboarding questions again after updating.
- Question cards in chat now clear properly when you answer by typing.
- Monday.com groups keep their deep links instead of resetting to the monday.com home page.
- The agent's clicking, typing, and key presses are more reliable, and fewer actions are lost or fail on a fresh session.
- Agent automation now stays in its own tab group instead of acting on the tab you have selected.
- The agent no longer wrongly refuses a task as a duplicate based only on earlier chat.
- Claude subscription sign-in is more reliable and gives clearer explanations when it's rejected.

## 19.18
_2026-07-20_

### New
- Monday.com integration: connect your account to get monday boards and apps pinned in workspace groups, a monday theme, a guided Walk Through tour, notifications and mentions in chat, and a helper that appears on monday boards.
- Focus & Anchor now shows a corner-anchored card with a generated title. The agent can also circle things on the page and explain them with that card.
- Sync now button in the Knowledge panel runs knowledge-building on demand.
- The Knowledge panel now has an interactive graph of your topics and connections. Agents can also query it.
- A new on-screen click specialist handles clicking tasks. It replaces the standalone New Automation.
### Improved
- On-screen automation is faster, down from about 363 seconds to about 200 seconds in testing.
- Automations now use real, trusted clicks and highlight page elements more accurately. They have clearer Stop and Interact controls, and the page is locked while the agent works.
- Background tabs use less power and CPU, and memory management now covers all your tabs.
- Settings has a fixed-size window and a consistent layout across all panes.
- The @-mention autocomplete panel has a cleaner look and sizes to match the composer.
- Screenshots now give a clear message when they can't be taken, instead of a blank image.
### Fixed
- Fixed a crash loop caused by an invalid group selection.
- Fixed flickering when switching tabs and groups.
- Scheduled system jobs now save and run properly, and missed wake-up deliveries are fixed.
- Fixed Gmail fetching and the connection of multiple Gmail accounts.
- Fixed Calendar, Apps Script and Slides tools that weren't working.
- Fixed unwanted popups from background helpers.

## 19.17
_2026-07-14_

### New
- Pinned cards now adapt to page changes: Nav8 can re-find the section you anchored even when the site's layout shifts.
- The browser theme now matches the site you're on, with seamless chrome and the site's brand accent color.
- Added a Stop button so you can halt the agent mid-task.
- Picking an element to pin now shows an in-page highlight ring, and card buttons give hover feedback.
### Improved
- The agent completes web tasks much faster, with shorter waits after page loads and less time spent on extra thinking.
- Clicking on web pages is more reliable, since the agent now performs a full, realistic click sequence.
- Every pinned card now stays visible, with no limit on how many show.
- When the agent runs out of steps, it now continues automatically or tells you honestly that it couldn't finish.
- The agent can no longer take over tabs you opened yourself.
### Fixed
- Fixed a crash on launch.
- Fixed checkboxes toggling twice when the agent clicked them.
- Fixed pinned cards disappearing after dismissing the HUD, and deleted cards coming back.
- Fixed Nav8 pulling you back to its Space every time you switched apps.

## 19.16
_2026-07-13_

### New
- Connect WhatsApp during onboarding, with a new pairing step in the integrations screen.
- Redesigned onboarding chat with a fresh look, including an animated background, a glowing logo, and assistant cards.
### Improved
- Slack now connects through sign-in only, which makes setup simpler.
- Signing in with Google once now carries over to your other Google services more reliably.
### Fixed
- WhatsApp contacts and active chats can be found again by name or number after WhatsApp's recent account-ID changes.
- Fixed an issue where the assistant's work was sometimes cut off mid-task because it was wrongly treated as stalled.
- Onboarding now resumes correctly if you leave and come back.
- Fixed an issue where the code from a Claude subscription setup wasn't being submitted.

## 19.15
_2026-07-12_

### Fixed
- Signing in with a Claude subscription now completes inside the app, with the sign-in code pasted automatically, so you're no longer stuck partway through.
- Google Tasks now works correctly when the agent works with a specific task list.
### Improved
- The agent is better at recognizing when you're signed in to Google and at understanding your workspace.

## 19.14
_2026-07-12_

### Fixed
- Fixed a bug in version 19.13 where the AI agent wouldn't work at all.
### Improved
- Streamlined the Google sign-in permission screen so it asks for fewer permissions.
- Existing Google connections made through other tools are now carried over automatically.

## 19.13
_2026-07-11_

### New
- Knowledge tab that builds a picture of the people, projects, and commitments in your email, along with meeting attendees and topics from your calendar.
- Your inbox is now scanned for receipts, invoices, subscriptions, purchases, and travel plans, which are organized for you.
- A new communications agent, plus improved Slack support.
- Approvals now work right in the chat, so you can approve or decline actions there.
### Improved
- Cleaner toolbar and Knowledge panel.
- Stronger protection for your email, accounts, and connected apps, plus more reliable approval prompts before the agent takes actions.
- Better stability overall, with fewer crashes and fewer cases of lost or unsaved data.
### Fixed
- WhatsApp now re-pairs cleanly after you log out from your phone.
- Fixed a case where "reply all" could go to the wrong recipients.
- Fixed a crash caused by non-English (non-ASCII) characters.
- Fixed several cases where actions looked successful but didn't save.

## 19.12
_2026-07-10_

### New
- Pin any part of a web page to get a persistent Ozzy card anchored to it. The card refreshes its content on each visit, and you can edit its prompt to regenerate it.
- Selected page components now show as a thumbnail chip in the composer, and the thumbnail stays in the message you send.
- Cards follow the page smoothly as you scroll, show a loading skeleton while regenerating, and hide when their element scrolls off-screen. They match light and dark themes. This feature is off by default and can be turned on in Settings.
- Connect WhatsApp, with setup guided right in the chat.
- Your browser agent can now work in its own tab group while you keep browsing, and you can take over at any time. A sidebar pill shows which session is active.
- Hands-off review: the agent can wait for your feedback in a conversational loop, and highlight mode opens automatically with its own blue-violet look.
- Personal Knowledge Graph helps Ozzy remember and update what it learns about you over time.
- A reworked onboarding with smoother pacing, a branded Ozzy avatar, a warmer look, email entry in the composer, and actions taken based on your answers.
### Improved
- Chat side pane opens and closes more smoothly, with less background layout work.
- Scrolling stays smooth on pages with ads, which no longer turn black.
### Fixed
- Sign-in with single sign-on and OAuth now works again on sites where cookies were being dropped.
- Onboarding no longer shows a too-narrow pane.
- Colored group icons in the minimized sidebar now display correctly.
- The sidebar gradient now stays aligned with its panel.
- Page scrolling no longer freezes after touching a card.

## 19.11
_2026-07-07_

### New
- Choose where your downloads are saved, with a new Downloads pane in Settings.
- Ozzy now has a Knowledge tab in Control Center where you can view and edit what Ozzy knows.
- Ozzy can read the actual reply in a Gmail thread, not just see that one arrived.
- Ozzy's session now carries over when you restart the app.
- Telegram now tells you when Ozzy goes online or offline.
- Monitoring tasks now run on a dedicated background watcher agent.
- The App Builder has a Build button in its header, and it recognizes more reliably when you confirm a build.
### Improved
- Notifications have a new look. The unread badge is redesigned in macOS style, and you can hover to clear it. Banners open the notification center.
- WhatsApp notifications now open the chat instead of an inline reply.
### Fixed
- Background wake-ups no longer steal focus from the window you're working in.

## 19.10
_2026-07-04_

### New
- Give your agents custom display names, shown across your agent fleet, connected tools, and the interface.
### Fixed
- The URL you typed in the address bar now stays visible when a page fails to load.
- Fixed a batch of correctness and reliability issues for smoother, more dependable everyday browsing.

## 19.09
_2026-07-03_

### Fixed
- Google-connected accounts no longer trigger repeated macOS keychain prompts, and sign-in tokens are now saved more reliably when several actions run at once.
- The agent no longer gets contradictory instructions, so it behaves more consistently.
- Scheduled tasks now run independently of each other, so one task can't hold up another.
### Improved
- Changes to the agent's persona and settings now take effect right away, without a restart.
- The agent hands work off between tasks more reliably and chooses the right route more often.
- Memory and onboarding are more dependable, and the agent keeps its information fresher.
- Security and stability are stronger across the app.

## 19.08
_2026-07-01_

- Behind-the-scenes improvements and fixes.

## 19.07
_2026-06-30_

### Fixed
- Fixed a slow, resource-heavy start when launching Nav8 with many tabs, so the browser opens more smoothly.
- Fixed an issue where the AI agent could sometimes fail on a page that was still loading.

## 19.06
_2026-06-30_

### New
- Interactive guided tour that walks you through Nav8 with action buttons and helpful tips as you go.
- Notifications now show icons, open a detail view when clicked, and let you reply right from there. You'll see a single badge, and alerts are hidden while you're already in the app.
- The chat header now shows a group icon, the conversation title beside the agent name, and a "+" button to start a new chat.
### Improved
- Connecting with a Claude Code subscription now works from the API-key card.
- Google accounts are now identified by email address instead of "Personal" or "Work" labels.
- Sidebar and the add-group button now line up neatly with group icons, and settings got a visual polish.
- Group chats now have a clearer indicator, and agent replies are more concise.
### Fixed
- Agent replies no longer vanish when you switch between groups or tabs.
- Agents now reliably start with all their tools, and a stuck turn can no longer lock up an agent.
- Messages no longer get sent to Telegram by mistake when you switch groups.
- Fresh installs can now connect to Google, and Nav8 no longer takes Google offline over an unreadable version.

## 19.05
_2026-06-28_

### Fixed
- Fixed the AI agent sometimes becoming unresponsive ("agent not responding") when its background components got into a broken state. Nav8 now repairs them automatically.
- Fixed a crash that could leave connected app integrations unavailable.

## 19.04
_2026-06-28_

- Behind-the-scenes improvements and fixes.

## 19.03
_2026-06-27_

### New
- Chat now stays put when you switch tab groups, with a tap-to-open notice that takes you to a group's chat.
- Ozzy now sends three summaries a day, including a new midday one, and your morning briefing includes an overnight summary of what was improved.
- Pinned sites now work as bookmark shortcuts instead of tab groups.
- Custom icons for your mini-app tiles: upload an image or describe one and let AI create it.
- Tab lock is simpler, with two modes and a daily scheduled reset.
### Improved
- Chat replies show formatted text (Markdown) as they stream in, and links in finished replies are clickable.
- Automation tasks now always get a clearly named tab group, and the Ozzy thread is named too.
- Connecting Google asks only for the permissions it needs, and Google actions use your local sign-in.
### Fixed
- Chat messages and replies no longer show up as empty bubbles.
- "Working…" no longer gets stuck when a chat turn ends without a result.
- Fixed an empty reply when Ozzy hands a task off to a specialist.

## 19.02
_2026-06-21_

### New
- Import saved passwords from a CSV file or a Bitwarden JSON export.
- Manage your autofill data in a new Settings pane.
- Autofill now shows a dropdown when you focus a field, and a toast offers to save new details. It also captures profile info and turns off the browser's built-in autocomplete.
- Sign in with your subscription in one click inside the app. If sign-in fails, a clear card tells you what happened.
- Web search and image/PDF understanding now work on your subscription.
- A new full-pane inbox list shows all your chats in one place.
- Pulse now sits in the chat-pane header, and the sidebar shows a live status dot.
### Improved
- Control Center is now the single home for managing your team of agents.
- Choosing which AI brain to use is simpler, with one place to select it and more consistent messaging.
- Gmail connections are more reliable.
- Subscription admin controls now work on fresh installs.
### Fixed
- The chat composer now scrolls when your message is longer than its maximum height.
- Fixed a bug where the concierge opened the wrong Gmail group instead of the agent's own thread.
- Fixed an issue where some tasks weren't handed off correctly to your agent team.
- Fixed repeated keychain password prompts.

## 19.01
_2026-06-16_

### New
- Sign in with your Claude subscription in one click to power the agent's brain, with access managed by your account's admin settings.
### Improved
- Cleaner first-run experience: the "Set up your agent?" popup no longer appears after the welcome screen.
- Changes to your account access now take effect right away, with no restart needed.
- Improved handling of multiple sessions, including settings.
### Fixed
- Fixed the nav8 hologram getting stuck during onboarding.
- Fixed an issue with the identity vault's keychain storage.

## 19
_2026-06-16_

- Stability and performance improvements.

## 18
_2026-06-16_

### New
- Mini-apps can now read files you give them, including Word documents, PDFs, images, and text files.
- Mini-apps can use AI-powered PDF reading and web search.
### Improved
- Improved the reliability of Google connections and the agent's tools.
- Inbox concierge setup and delivery are smoother.
- The app's startup screen is more dependable.
### Fixed
- Fixed an issue with the file dialog in mini-apps.

## 17
_2026-06-15_

- Stability and performance improvements.

## 16
_2026-06-15_

- Stability and performance improvements.

## 15
_2026-06-15_

- Stability and performance improvements.

## 0.9.0
_2026-06-15_

### New
- Set up Nav8 with a new guided setup wizard and a refreshed Agents Hub, including support for your own custom agents.
- Chats history now lives in the Notification Center, so you can find past conversations.
- King briefings now show up as desktop notifications, and email digests can be sent to your custom agents.
- Scheduled tasks are easier to manage: create, test, then approve, with tasks grouped in a clearer view.
- Agents can open their own dedicated workspace groups for a task.
- Read-aloud for chat replies, plus new sounds for sent messages and incoming agent messages.
- Settings has a redesigned sidebar and a new Profile pane.
### Improved
- Switching between groups, and opening Slack and WhatsApp, is much faster and smoother, with no white flashes.
- A single, clear "Working" indicator now shows when an agent is busy.
- Chat text is easier to read, and colors update correctly when you change theme or group.
- Updated browser engine for better video and media playback.
### Fixed
- Fixed Google apps getting stuck in an endless reload loop and re-clicking a tab sending it to the wrong account.
- Fixed the "took too long" error appearing on long automations that actually succeeded.
- Fixed repeated keychain password prompts.

## 0.8.5
_2026-06-03_

### New
- Personal Assistant gives you a proactive morning brief covering your inbox and calendar.
- The App Builder now defaults to a more capable model, and requests like "build a … app" go straight to it.
- Mini-apps you build can now call real web APIs.
- WhatsApp specialist agent can work in the background and detects when you need to log in.
- Switch between tabs in a group instantly, with a new set of themes and polished sidebar and toolbar.
- Hovering an app tile in the sidebar now shows a tooltip.
### Improved
- Building apps is faster, and the preview now matches the installed app more closely.
- Resizing the window reflows content in real time, and the app feels smoother at startup.
- Switching between custom apps is smoother, with no flicker.
- The assistant knows which agents you have and what each one does, and handles Google tasks directly.
- Removed the cost preview step from chat.
### Fixed
- Fixed white flashes when switching between apps and tabs.
- Fixed a crash when approving actions.
- Fixed a launch crash and a flood of keychain prompts on macOS 26.
- Fixed mobile-style pages rendering incorrectly in narrow panes.

## 0.8.4
_2026-05-31_

### New
- Chat now has a "King" front-door assistant that understands your request and hands it to the right agent. It can ask which Google account to use before it starts.
- Create persistent agents, including an inbox concierge that proposes actions and waits for your approval before it does them.
- Message Nav8 from Telegram. You can also approve actions and answer questions there.
- The chat pane has a new agent toggle with Builder, and an amber input frame shows while King is reasoning.
- A fleet activity strip now always shows what your agents are doing.
- Each automation gets its own tab group and session, and Nav8 switches you to it when work starts.
### Improved
- Building and editing apps is faster and more reliable. Edit App now works correctly, and leftover drafts are cleaned up.
- Google Docs, Sheets and Slides are now created and filled through your connected Google account instead of through the browser.
- Video and audio that use H.264/AAC now play.
- If a task fails, you now get a clear explanation. Nav8 waits for you to sign in instead of reporting success when it hasn't succeeded.
### Fixed
- Fixed a crash in chat when a streaming reply was closed.
- Fixed duplicate tab groups and lost conversation context across follow-up messages.
- Fixed missing replies and API errors showing up inside chat bubbles.
- Fixed a crash when closing split-view panes.

## 0.8.3
_2026-04-28_

### New
- A new onboarding experience helps you get started with Nav8.
### Improved
- Voice call transcripts and AI responses are no longer saved in logs by default, for better privacy.
### Fixed
- Fixed a problem with the Nav8 installer download that could affect installation.
- Improved the safety of sign-in and connected-app authorization pages.

## 0.8.2
_2026-04-27_

### New
- Build your own mini-apps with a hands-free app builder: describe what you want, and Nav8 builds, tests, and installs it for you, with a progress view and animation while it works.
- Mini-apps can now use the full range of Google services, including sending email through Gmail.
- Telegram is now built in, and starts automatically.
- Click a suggestion in Google Docs and a line connects it to the source text on the page.
- A new first-run onboarding walks you through theme, groups, connected apps, Telegram, your Claude API key, browser import and setting Nav8 as your default browser.
- A new Nav8 splash screen with sound plays on every launch.
### Improved
- Switching between tabs in a group is faster, since the whole group is now preloaded.
- Links to the same site now stay inside your custom app group, and stray tabs in that group close after 10 minutes away.
- Results for page actions and email scans are cached, so they load faster the second time.
- Sidebar shortcuts and pinned sites now match the size of tab icons, and Gmail, Calendar and Slack have clearer, distinct icons.
### Fixed
- Fixed a crash when clicking an external link.
- Fixed the repeated keychain prompts: you now see one instead of three.
- The app builder no longer hides your open browser tabs, and its preview refreshes automatically as changes are made.
- The Extensions button now resets properly when its popover closes.

## 0.8.1
_2026-04-22_

- Behind-the-scenes improvements and fixes.

## 0.8.0
_2026-04-22_

### New
- Telegram can now be connected as an alternative to WhatsApp for relaying messages to your agent.
- Google Workspace card in Settings lets you grant full Google access, so the agent can read your Google Docs.
- Notion pages can now be read by the agent.
- Generate slide decks from the page you're viewing, shown as native mini-slide cards.
- The side panel now has three tabs (Tasks, TLDR, HUD) with a new liquid-glass card design, collapsible cards, and hover animations.
### Improved
- Tabs open and switch faster, since recently used tabs stay ready in the background.
- The browser agent works more efficiently and reliably on pages, with more compact page reading and steadier element targeting.
- Long articles and documents are analyzed much faster, with fuller coverage on sites like Wikipedia, news and arXiv.
- Integrations and settings are better organized.
### Fixed
- Fixed tabs needing two clicks to activate, and stale "leave page" prompts appearing.
- Fixed WhatsApp connection and pairing problems, including duplicate pairing windows and incomplete resets on disconnect.
- Fixed Gmail and Google disconnect so they always show as disconnected.

## 0.7.3
_2026-04-07_

### Improved
- Nav8 is more stable and reliable, especially during long sessions.
### Fixed
- Fixed memory leaks that could make Nav8 use more memory and slow down over time.

## 0.7.2
_2026-04-07_

- Stability and performance improvements.

## 0.7.1
_2026-04-06_

### New
- Ask the built-in agent to browse for you. It can now carry out tasks in the browser and shows clear action cards as it works.
- Share a tab group with a simple link. Teammates get a preview page and can open your tabs, and the group stays in sync as you add tabs or navigate.
- One AI bubble for every page type. Its menu adapts to what you're viewing and offers a summary, color-coded highlights you can click to jump to the spot on the page, and key takeaways.
- Gmail inbox scan sorts your mail into six color-coded categories. You can archive, delete or organize emails from the results, or click one to open it.
- Fact-check shows each claim with a verdict badge. Click a claim to scroll to it on the page.
- Shopping product pages get a combined price and review analysis, with deal badges added to the page.
- Smart Groups are rebuilt as tab groups that refresh themselves automatically.
- Themes can use images. Custom themes are bundled, and each group can have its own theme.
### Improved
- Calendar Event Analysis now has a heatmap, smart grouping and insights.
- CrossView now supports up to 8 panes.
- The tab bar, omnibar, hover effects and light mode have a cleaner look, and tabs follow Safari's style.
- Creating a group is easier, with icon and color pickers, and the group gets a default name if you leave it blank.
### Fixed
- Gmail scans and Calendar analysis no longer cut off partway through.

## 0.65.3
_2026-03-30_

- Behind-the-scenes improvements and fixes.

## 0.65.2
_2026-03-29_

### New
- Shared tabs now sync with CrossView, so everyone in a shared group sees the same tabs.
- Close a shared tab for everyone at once, with a confirmation first.
- Each Slack channel now has just one shared tab group.
### Improved
- Shared tabs refresh when you open Cmd+K, so the list is always current.
- You no longer get duplicate Slack notifications for shared tabs.
- Your sharing session now renews automatically instead of signing you out.
- Joining a shared group now shows a loading panel while it connects.
### Fixed
- Joining a shared group no longer hangs.
- Sidebar icons and tab states now display correctly.
- Internal CrossView pages no longer appear in shared tab lists.

## 0.65.1
_2026-03-29_

- First public release.

