# **Changelog**

All notable changes to Skales will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),

and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v12.9.50 - Aftermath

**A release about work that takes many hands: agents you can watch and steer one by one, a composer that finishes your sentence, and films Skales cuts, mixes and checks itself.**

When several agents work on one thing, they now show as one panel with a band per phase and a tile per agent, and each agent can be stopped, steered or restarted on its own while the others carry on. A large task can be planned first, confirmed, run in phases with helpers on their own models and brought back as one answer that names what contradicts and what is missing. While you type, the composer suggests the rest of the sentence from a small model on your own computer, in the chat, Code, Flow, Lio AI and Iris, and a paired phone can borrow that model from this computer.

Skales reaches further out: the Chrome side panel and the Word, Excel, PowerPoint and Outlook task pane pair with your Skales like a phone does, sixteen ready-made automations become a scheduled job in a few answers, and a custom endpoint can speak Anthropic Messages or OpenAI Responses as well as Chat Completions. Claude on your own Anthropic key is priced from Anthropic's list and its effort level reaches the model on every surface, and long thinking turns are no longer cut off.

Flow learns the craft of a film. Skales can record itself in a separate demo copy, render one timeline in 16:9 and 9:16, look at its own film and redo only the seconds that changed, place takes as layers, slow clips around their moment, and mix voice, music, effects and clip sound into one track with stems. Narration and music come back measured, generated clips survive a restart, and an OpenRouter management key or an empty balance is named with the fix.


### Added

- **Your own background behind the main window.** Under Settings > General > Appearance the Skales X background now offers Honeycomb, Waves, Dots, Contours and Plain next to the drifting circles, all painted in your accent colours, plus a background colour that tints the light or dark base. You can also set your own picture: it lies behind the whole window, sidebar included, with Dim, Blur and an Overlay colour that follows your accent until you pick one, and Remove takes it away again. The picture is stored as a file in the data folder, stays out of Flow and Code, and its blur is drawn once, so it adds no GPU load while you work. Moving patterns stand still with Background animation off or reduced motion on, and nothing changes until you choose something.
- **Desert Day and Desert Night come with Skales as background pictures.** The Background picture row in Settings > General > Appearance now shows small previews of Desert (auto), which is Desert Day while the app is light and Desert Night while it is dark, Desert Day and Desert Night next to Choose picture, with the selected one marked, and Dim, Blur and the overlay colour work on them as on your own picture. Your own picture stays available while you try the others, and Remove simply turns a shipped picture off. A new installation starts on Desert (auto) in the Skales X theme; an updated installation keeps exactly the background it had.
- **Setup asks whether you want the desert behind the app.** While Skales X is chosen in the look step, a Desert background switch with Day and Night previews sits under the theme cards, on by default. Turn it off, or finish setup on Classic or Flat, and the installation starts without a picture, so switching to Skales X later in Settings brings no desert along. Only the choice at the end of setup counts; trying other themes on the way changes nothing.

- **Ready-made automations in a few steps.** Schedule now has a Blueprints view with sixteen automations, from an important-mail watch and a news digest to price, competitor and community watches, a morning brief and a weekly review. Pick one, answer a few questions, choose how often it runs and whether each result also goes to your paired phone, Telegram, WhatsApp or email. It becomes a normal scheduled job you can pause, run, edit or delete, asking twice never makes a second copy, and anything that is not set up yet is named with a link into Settings. Type /blueprint in the chat for the same catalogue.

- **Narration returns the timing a film is cut to.** Every voiced line comes back with its length and the measured start of each spoken phrase, a script with several speakers is one request with a voice and a direction per line, a tempo factor speeds lines up at the same pitch, and long pauses inside a line can be shortened.

- **Generated music comes back measured.** A track reports its real tempo, first downbeat, drop and bar-exact loop length, so the picture lands on the beat and a short track is extended on the bar; tracks over 30 seconds use the long Lyria model on OpenRouter.

- **Generated video clips survive a restart.** Each clip is a background job whose provider job id is saved before the first poll, so a restart collects the clip instead of paying for it again; several clips render side by side, slow clips are never cut short, renders are only given up when they stop moving, and the fast Veo tier is the default.

- **An OpenRouter management key and an empty balance are named.** "401 User not found" on every call is explained as a management key with the way to a normal API key, and a used-up balance is named as such, in the chat, in every tool result and in the Settings key test.

- **Skales can film itself for a video or tutorial.** Asked in Flow, the chat or Code, it records a second copy of the app in a separate demo profile (remote access, feed, telemetry and channels off), clicks through it by script (pages, typing, light and dark, the Appearance skins), and returns a 30 fps MP4, the picture sequence, sharp stills and the time of every step, ready to place in Flow. Your own window and desktop are never filmed, and the second copy closes when the take ends, fails or is stopped.

- **One motion film renders in 16:9 and 9:16 from a single timeline.** A composition declares its formats once and comes out as `motion.mp4` and `motion-9x16.mp4` (any aspect or pixel size works), laying itself out per format while the timing stays shared; a vertical cut shows an interface recording as the whole window, and Flow's render card lists every file.

- **The assistant checks its own film and fixes only the seconds that changed.** `check_motion` returns contact sheets of every format, a frame-by-frame flash scan, waveform and spectrum with loudness, and the layout rules (text cut at the edge, heading margins, subtitle line, overlapping text, cropped interface in 9:16, frames that change with seek order) as pictures the model looks at; `render_motion` re-renders a range of seconds and splices it into the existing files.

- **Takes become layers of a motion film.** `add_motion_take` turns a recording of the Skales interface, any video, a folder of pictures or a still into a frame sequence the composition can slow down, speed up or cut around a moment, with the same tools in Chat, Code and Flow. A take is placed with the same speed, fit and moment arguments as a clip in the editor, and the ready segment comes back with it.

- **A film's whole soundtrack is mixed in one step.** Voice lines on their seconds, music ducked under the voice with its drop landing on the cut you name and lengthened by whole bars when it is too short, tape stops, sound effects on timeline cues and the clips' own sound (or none) come out as one track at -14 LUFS plus separate voice, music, effects and clip stems, and Skales reports the measured loudness, peak, ducking depth, drop and loop.

- **Generated clips can be slowed down and cut around their moment.** A clip in the editor plays at any speed with its sound in step, fits a stretch of the film, or lands its one moment (a launch, a blink) exactly on a chosen second; video layers take a start point and a speed too.

- **Skales looks at every clip it generates.** The start picture and three frames of the finished clip come back to the model so a wrong picture is made again before it is used, and a clip the service's content filter refuses comes back with how to soften the wording and try again.

- **Several agents at work show as one panel you can act on.** Sub-agents of a chat turn, a job split into background parts, a plan with phases and a team run all draw the same panel, standing open in the conversation, chat, Code, Flow and Iris alike, instead of behind a folded header: the job's name with Stop for a dispatched job, a lead line with the phase, answers and time, phase counters ("Research 3/13"), then one band per phase that folds away once it is finished, holding one tile per agent: a rounded honeycomb cell in your accent colour with the agent's role icon inside, its state shown as the cell's outline, fill and mark. Clicking a tile shows its role, phase, errand, model, tokens, cost, run time, steps, attempt, last steps and result or error, with Stop for that one agent while its siblings carry on, Steer with a message field, and Restart once it has ended (it asks first, because only that agent is paid for again). "As table" folds out the agents with state, tokens and time, and the picked agent comes back after a reload. Reduced motion keeps the shapes and stops the pulse.

- **A paired phone gets its typing suggestions from this computer.** When the phone has no small model loaded, its composers ask this computer, which answers with the same model, the same cost row on the conversation and the same quiet hand-over after "too many requests" as here; the phone's Privacy Mode keeps the answer on this computer's own model, and a suggestion the phone no longer needs is stopped here too.

- **The composer suggests what you are about to write.** While you type, the rest of the sentence appears in grey behind the cursor, and with an empty box after an answer the message you are most likely to send next; Tab takes it, Esc or typing on drops it. It works the same in the chat, the new-chat page, Skales Code, Flow, Lio AI and Iris. A small model on this computer (Skales Local or Ollama) answers by default, asked only after a short pause in typing and cancelled by the next key. A small fast cloud model can be chosen instead; its cost counts toward the conversation, a free tier that refuses with "too many requests" quietly hands over to the local model, and Privacy Mode keeps it on this computer. Key, password and secret fields, and text that carries a key or a password, are never predicted. Switch it off or choose the source under Settings > Assistant > Typing suggestions; without a local model it stays quiet and the row offers to set up Skales Local.

- **A custom endpoint can speak Anthropic Messages or OpenAI Responses, not only Chat Completions.** Each endpoint in Settings > AI & Models > Providers names its protocol (OpenAI Chat Completions, Anthropic Messages at /v1/messages, OpenAI Responses at /v1/responses), and chat, tools, streaming, the effort dial, the long thinking wait, the model list, Code, skills, Discover and fallback all use the matching wire. Endpoints saved before keep Chat Completions. Every extra endpoint also has its own Test connection with the connection map, run against what the card holds before it is saved.

- **Reverting a file change does not count as new work.** Several edits and individual edits share the same progress history, so returning a file to an earlier state does not keep a turn running.

- **Conversation model labels stay with the answers.** Repeated model switches, concurrent message saves and reloads verify the existing paired provider and model stamp.

- **Several file changes can be applied together.** Every exact replacement is checked before writing; failed or interrupted batches restore the previous files and keep existing folder permissions and Undo.

- **Conversation compaction uses the real text tokenizer.** Tool arguments and results participate in the count, CJK and code no longer use a four-character guess, and image cost remains a provider-dependent estimate.

- **Independent file reads in one tool turn can run together.** Read, grep, glob and directory listing keep their existing permission checks and return in the requested order; writes and other tools wait at ordering barriers.

- **Each plugin run now executes in its own permission-bound child process.** Approved code and existing legacy approvals stay valid; file access stays inside its own folder and authorized calls use the parent broker. Stop, timeout, crashes and inspection share the same isolated launcher. Repeated unchanged plugin calls do not create extra code cards.

- **Hunter and Discord can be connected from a ready-made API preset.** Choose either in API Connectors, confirm its domain and add your key. Hunter finds and verifies emails; Discord reads a specific message or pages channel history with the bot permissions you granted. Each preset starts without a key or domain approval.

- **Large tasks can be planned, delegated in phases and combined into a sourced answer.** The lead proposes a confirmable plan, parallel helpers use their own instructions and configured models, and the final answer names contradictions and missing results. Progress appears in Chat, Code and the paired phone; unfinished work resumes after restart, Stop reaches every helper, and parallelism follows your settings.

- **Documents can be searched by their section hierarchy.** Local search returns parent paths, selectable sections and exact source citations without embeddings. The same search works on the local knowledge base; changed documents invalidate outdated section references while ordinary reads and keyword retrieval remain available.

- **A nine-role development team can be installed in one step.** The existing team picker creates a CTO, planner, architect, version-control specialist, builder, security and performance auditors, reviewer and QA. Review roles stay read-only through execution, and choosing the preset again reuses the existing team.

- **Scheduled work can run without a model.** Reusable JSON skills execute file, document, script and mail steps through the normal permission checks. Mail prefilters can stop before any further work, or queue a separate agent task only for matching messages. Saved jobs and their completed steps survive a restart.
- **Use Skales from Chrome and Microsoft Office.** Pair the Chrome side panel or Word, Excel, PowerPoint and Outlook task pane with your Skales server to chat and work in your open browser and documents, using the same conversations, attachments and action approvals as your paired phone. Manage and disconnect extensions in Settings.

- **You can write to a sub-agent while it works.** A working helper's chip in Chat and Code, a running child in Tasks and the paired phone offer a one-line field; the helper reads the message after its current step, and a message that comes too late is shown as not delivered instead of disappearing.

- **Earlier sub-agents can be named again.** Skales keeps what a conversation delegated with an id per helper, so it can list them, give one more work with its earlier answer in front of it, or run only the one that failed again without paying for the others twice.

- **Sub-agents can be asked for an answer in a fixed JSON shape.** Skales asks a helper to correct an answer that does not fit and clearly marks one that still does not match.

- **Memory has a Journey view: everything Skales learned, on one timeline.** Facts, lessons, procedures and every change to them, episodes and what waits for your approval sit newest first; each entry can be corrected, removed or restored, and `/journey` opens it from the chat or answers in Code, the messengers and on the phone. What you change there is saved at once, also when learning waits for your OK; a memory topic the assistant deleted can be restored there, and a topic deleted to be written anew can be written again. "Reset what Skales learned", the character reset and asking Iris to forget something erase for good and keep no copy.

- **Skales tidies up its own procedures once a week.** Procedures nobody used for weeks are marked and later archived, never deleted, after a grace period however the tidy-up was started; a procedure you asked for is only marked, never archived. Custom Skills shows the archive with Restore, a Pin keeps a procedure, and an optional merge of near-duplicates can be undone and is declined when its procedures changed since it was proposed.

- **A trusted project brings its own skills.** In a folder-bound chat or Code session, the skills a repository ships in its skills folders come first, a skill that arrives later is named before it is used, and Skales changes them only when you ask and as your approval setting says.

- **Skales can rewrite, trim and archive the procedures it keeps.** A whole procedure can be replaced after reading it, a reference file taken out, and a procedure archived and restored; one file a skill brought can be read on its own.

- **NVIDIA Parakeet transcribes on your computer, without any provider.** Settings > Voice > On-device voice offers Parakeet TDT 0.6B v3 (25 European languages, German, English, French, Spanish, Italian and Croatian among them) and v2 (English), about 490 MB each, next to Whisper. It is several times faster than Whisper Small on a laptop CPU. Speech in a language the chosen model does not cover goes to the next service, and the answer says why.

- **Higher-quality offline voices.** German (Thorsten High) and English (Cori High, British, and LJSpeech High, American) are offered as the larger Piper voices, which sound clearly less mechanical. Every Piper voice now says on its card whether it is high or medium quality, and when several voices for one language are downloaded, the high one speaks.

- **Skales can dub a video or an audio file into another language with ElevenLabs.** Ask in chat and the speech is translated and re-spoken in the speakers' own voices, with music and background kept; the dubbed MP4 or MP3 lands in the Studio dubbing folder. Stop asks ElevenLabs to delete the job and says whether it succeeded. A failed cancellation keeps the job number so you can ask to cancel again; a dub that takes longer than expected can be fetched later without starting another.

- **You can clone a voice on your ElevenLabs account from your own recordings.** Settings > Voice > ElevenLabs takes one or more recordings and a name, asks once whether the voice is yours or the speaker agreed, and only then uploads them; the new voice is selected and appears in the library for chat, Studio, Flow and Iris. Voices you made yourself can be deleted from the same list.

- **ElevenLabs Scribe can transcribe your voice, with the same ElevenLabs key that speaks.** Settings > Voice > Speech to text has a new choice: pick ElevenLabs Scribe and its model, and it goes first for dictation, the chat microphone, Call mode, Iris, voice messages and video understanding, with the existing chain behind it as the fallback. A key saved only for speaking is never spent on listening. A missing key, a refused key or an empty balance is named on screen.

- **The ElevenLabs speech model can be chosen.** Multilingual v2, v3, Flash and Turbo are offered in Settings > Voice next to the voice, and chat, Studio, Flow and Iris speak with the one you pick.

- **Signing in with ChatGPT now also makes pictures, without an OpenAI API key.** Image requests in chat, Studio and Flow go through your subscription's own image tool; the subscription picks the GPT Image model and the reply says the picture was made that way. With an API key the key is still used, so a picked model is honoured. Video is not offered through a ChatGPT sign-in.

- **Code roles can be switched from a paired phone.** The choice belongs to the coding session and survives reopening; phone tasks run through the same architect, coder and reviewer chain as the Code window.

- **A Flow 3D scene can render to MP4.** Use the same Render as video button and progress display as for a Motion composition.

- **The diagnostics report has a Skales Local section.** It names the graphics backend, the device the engine found, how many layers actually went across versus how many were asked for, the active model and its context window, or says plainly that the local engine is not running with the last known values when it isn't.

- **Flow's composer can now pick a narration voice and a music service.** Your choices are kept with the project for video, film, motion and courses; naming a different service or voice in a later message changes that choice. With nothing configured, the composer says so and where to set it up.

- **A local or custom model now shows a connection map instead of one green check.** Test Connection on the LM Studio, Ollama, KoboldCpp or custom endpoint card draws Skales, address, server, model, context, tools and a real test turn with arrows between them, names the link where it breaks with the reason and the next step, and turns green only when the test turn comes back. It recognizes the usual traps: a server that is off or on another port, LM Studio or Skales inside WSL2, a server that only listens on its own machine, no model loaded, a context window too small for Skales, and a model without tool calls. The last map comes back after a restart.
- **A chat or Skales Code error from a local or custom model offers Check connection.** It runs the same check with your saved settings and shows the same map right under the error, with a way to the provider card.
- **The diagnostics report shows the connection map of your local and custom models.** The same links, reasons and next steps, in plain text for a bug report, without any key that sits in an address. When Skales reads its own logs it uses the last map instead of testing the model it is running on.
- **A paired phone can show the connection map of this computer's local model.** An error from a desktop-run conversation can be checked from the phone with the same test; the map never carries a key from a custom address, and a second tap joins the check that is running.
- **The LM Studio guide has a section for Windows with WSL2.** It explains which side listens where, which address to use, Serve on Local Network, the firewall, the loaded model and the context length.

- **Skales Code checks many more languages after every write.** Rust, C and C++, Objective-C, Java, C#, PHP, Ruby, Kotlin, Swift, Lua, Bash, YAML, JSON, HTML, CSS, Dockerfile and Terraform join TypeScript, Python and Go. A missing checker is installed only after you agree to the exact command on the card, which picks the package manager your computer already has and names a missing one, and it installs in the background while the session keeps working; where your system has no install command, the card says which program to install yourself.

- **An undone turn in Skales Code can be redone.** `/redo`, or the Redo button that appears above the message box after an undo, puts the turn back with its files and its conversation, the most recent undo first, and it still works after restarting Skales. A file you edited by hand in between is named and kept, and nothing is redone; sending a new message ends the Redo. A paired phone can redo the same way.

- **Start a plugin of your own from a template.** The Plugins page offers four working examples: a list you keep by hand, a page that asks your model, a weekly review and Snippets for text you reuse. Give one a name and it is yours, ready to change by hand or by asking the chat. Snippets also shows tools the chat and the plugin can use; suggested text waits for you to add or discard it. The weekly review starts only when you switch it on and costs one agent run a week.

- **A guide page on building plugins that hold up.** The plugin blueprint walks through the brief, the three modes, where your approval sits, how to check a plugin and how to share it, and the Plugins chapter of the guide links to it.

- **Language checks no longer run code from folders you have not trusted.** In Skales Code, a language server that runs a project's own build files or plugins starts only in the folder you opened, a folder on your trusted list, or one you trusted for this session; a repository cloned into the project, code downloaded into it later, or a folder the assistant picked for the conversation itself, stays untrusted until you say otherwise, and a checker that would load such a folder along with your project leaves it out or does not start. A project you bound to a chat before this version counts as yours, and the submodules your repository lists are trusted with it. The Code window and a chat in Code mode ask "trust this folder" on a card, the status bar says which checks are off and why, and Settings > Assistant > Skales Code > Trusted folders lists every trusted folder and takes it back.

- **Fifteen more languages are checked as you code.** Vue, Svelte, Astro, Laravel Blade, OCaml, Dart, Haskell, Julia, Clojure, Nix, Zig, Gleam, Elixir, Prisma and PowerShell join the languages Skales Code checks after every write. A missing checker is installed only after you answer the install card, which names the exact command and where it lands, in the Code window and in a chat in Code mode alike.

- **Shell commands and file changes in a project chat can be undone, and every Undo in the chat can be redone.** When a chat works in a project's folder, a command that can change files is snapshotted first and a file the assistant writes, edits or deletes in that folder keeps its earlier version, so each step gets the same Undo button Code mode has. Reading commands are not snapshotted, audio and video stay out, large folders are skipped with a note (the limit is under Settings > Assistant > Skales Code), and if a command changed files it does not name, the Undo asks before restoring those. After any Undo in the chat, the same place offers Redo until you send the next message; a file you changed in between is kept and named instead of overwritten.

- **Plugins you build in the chat can bring tools of their own.** Ask for a plugin with its own tool and the chat creates it; a bad name or a missing file is refused with the reason instead of half-written. The plugin's agent can use those tools too, and a tool that sends something outward still asks you first. Creating or changing a tool's code shows you the code and asks in every mode. If the code changes while you are reviewing it, a new card asks you to review the current version. Confirming that new card from a paired phone keeps the conversation usable for the next turn. Reopening a conversation keeps the review code on its approval card without duplicating it in the conversation history or crowding out earlier messages. Page-only edits no longer repeat unchanged tool code in approval requests. Plugin updates recover from unreadable code files and explain which file needs attention. Updated approval cards stay answerable in Telegram, Discord and WhatsApp.


- **You can decide what Skales keeps before it keeps it.** With "Keep new things only after my OK" on in Settings > Memory > Learning, nothing Skales learns about you is written until you say so, whichever way it learned it; new facts, lessons and procedures wait in a block at the top of the Memory page and under the learning line in the chat, each with Keep and Discard. Changes Skales makes to its own procedures (a rewrite, taking out a reference file, archiving, restoring) and a merge the weekly tidy-up proposes wait there too. The same thing said again in more detail grows its entry, a longer entry shows its full text before Keep is offered, and an entry that changed after you looked asks you to look again. What you remove from the Journey or discard here is not offered again, with or without approval; when you ask for it again in so many words, Skales checks with you once. Removed entries stay restorable and declined entries stay declined until you change your decision. Large learning histories stay responsive when you remove or restore an entry. Nothing is dropped without your decision, and a paired phone can show and decide the same list.

- **Telegram, WhatsApp, Discord and the terminal learn the way the chat does, and only from you.** Your conversations there get the same look-back, its cost counts toward that conversation's daily budget, and one short line after the answer says what was kept (in a group only how many; it can be switched off). `/learn`, `/refine` and `/btw` work there too. Other people in a group, or on Discord anyone but the owner, are answered, but nothing they say is kept. While Skales does not know who the owner is, it says so once with the way to set it, Settings shows the same, and nobody can confirm an action there; on Discord, Settings gives a one-time code that makes whoever sends it to the bot in a direct message the owner.

- **A message you send on Telegram, WhatsApp, Discord or in the terminal while Skales is working joins that turn at its next step.** It works like the chat window and follows the same setting; "After the turn" keeps the previous behaviour, and "stop" still stops at once. A message that was acknowledged is always answered, or, if you stopped the turn first, named back to you.

- **Standing instructions now have their own place under Persona, and can go at the very top.** Settings > Assistant > Persona shows the instructions that apply to every agent, your own included, while the persona text says it is for the default agent only. A new switch, off by default, makes the standing instructions the first thing every agent reads in the chat, your own agents, Code, the messengers and Buddy.

### Fixed

- **Asking whether Skales works in Word, Excel, PowerPoint, Outlook or Chrome gets the real answer.** A question about "office docs", "word" or "the Chrome extension" now finds the Office add-in and the Chrome side panel, each with how it is installed, paired, limited and disconnected, and while nothing is paired the answer says where to pair it instead of pointing at the Skills page. The agent panel, the progress honeycomb, the protocols of a custom endpoint, the connection map, the effort dial, the on-device voices and the other additions of this release are found by the words people use for them, too. The Guide lists both extensions with their pairing state and a way into Settings.

- **The guide explains Chrome and Office from the download to disconnecting.** Installing the Chrome side panel, serving and sideloading the Office add-in on the web, on a Mac and on Windows, connecting Outlook to Microsoft 365 with an Entra application, what each extension can do, its limits, what each connection message means and what to do about it, and how to disconnect. When Skales looks something up in its docs, a long list of places no longer pushes the explaining section out of the answer.

- **Asking Skales about itself in German, French, Spanish, Portuguese or Croatian finds the guide.** "Wie verbinde ich Skales mit Word?" or "Wie koppele ich mein Handy?" now brings back the guide section that explains it, as the English question does; English answers are unchanged, and a question about the world in any language still finds nothing in the docs.

- **An OpenRouter key problem is explained once.** A failed step that hit a management key or an empty balance carries the explanation a single time, even when the same result passes through more than one check.

- **The effort dial reaches the model in a plain chat.** A conversation on the default assistant with no model picked in the composer now sends the chosen effort level to Claude (and every other model with its own effort setting) instead of quietly running at the model's default.

- **Claude on your own Anthropic key shows what each turn cost.** Chat, Skales Code and Flow price Claude Opus, Sonnet, Haiku and Fable from Anthropic's list instead of "price unknown", with prompt-cache reads and writes billed at their own rates, so the spend meter and the spending limit count these turns; a model Anthropic has not priced yet still says unknown rather than borrowing an older model's rate.

- **French and Russian keep talking to you informally on the new screens.** The automation blueprints, the paired browser and Office extensions, the custom endpoint warning and the agent panel no longer switch to the formal address.

- **Reading pictures through your own vision endpoint reaches the same server the chat does.** The custom Vision Provider in Settings > AI & Models > Models per task reads its address like the chat (a bare host gets /v1, a pasted /chat/completions is removed), can speak Anthropic Messages or OpenAI Responses as well as Chat Completions, and an active custom endpoint that can see now reads screenshots instead of answering "Unsupported vision provider".

- **Adding a custom endpoint such as Tetrate works on the first try.** The address is read the same way everywhere (with or without https://, /v1, a trailing slash, the full endpoint path or the version twice), so the model list and the chat no longer reach different addresses. Fetch models uses the key typed into the endpoint before it is saved, reads a paged catalogue to its end and names a refusal with its status, the endpoint's proxy is honoured, a second identical endpoint is named instead of saved, Add no longer stacks empty endpoints, and an error names "your custom endpoint" instead of a number.

- **The effort control is in sight in a Flow project and follows what the model list says.** The project toolbar wraps onto a second row instead of hiding pills past the edge of the chat pane, and the model pill, which holds the model and the reasoning-effort choice, comes first. Whether a Claude model takes an effort level, and which levels, is read from Anthropic's own model list (also for your own endpoint speaking Anthropic Messages) after Fetch models; a model written with a date, a long-context suffix, a routed or Bedrock prefix, capitals or a dotted version (for example `claude-opus-5-5[1m]` or `claude-sonnet-4.6`) is recognised when the list says nothing.

- **Long Claude tasks no longer break off while the model is thinking.** Claude from 3.7 on, GPT-5 and later and o4 get the long silence window and the longer call budget on every route (Anthropic direct, OpenRouter, Chat, Flow and Code), and any request sent with an effort level counts as a thinking request, so a quiet minute of reasoning is no longer reported as "stream stalled".

- **A Flow project that reaches into another project now explains the way forward.** The model is told to say that you can name the project in your message or attach it with "Reference another project", and it loads any missing tools itself instead of asking you to change a setting.

- **Plugins and custom skills reach only the hosts their rights name, on every network path.** WebSocket, EventSource, the shared HTTP client, sockets handed out by an allowed connection and a dynamic import of a socket or process module are now held to the same host list as fetch; plugins approved before keep running unchanged.

- **A delegated part whose role shares no tool with the conversation now stops with that reason.** Narrowing still never widens a helper's tools; when the role's tools and the tools the run may use have nothing in common, the part fails at once, names both lists and is reported as a gap instead of running as a helper without tools. Team runs report the same reason for that member.

- **Very large files and results from the Chrome and Office extensions stop with a clear reason instead of filling memory.** Files, screenshots, pages and attachments up to 64 MB still cross in pieces; a larger one is refused in the panel or the tool result right away, not after a timeout. Disconnecting the last extension that used an origin also stops that origin from reaching the server.

- **Code sessions can be archived, restored or deleted from a paired phone.** Remote requests use the same session writers as the desktop, archive views remain distinct from active work, and archiving preserves the session's recency.

- **Server capabilities explain FTP and FTPS alongside SSH.** Profile listings point FTP users to ftp_list, ftp_download and ftp_publish, while keeping SSH commands and sync tied to SFTP/SSH profiles.

- **Tool discovery survives tight input budgets.** Available load_tools and check_capabilities stay in capped catalogues, and the payload accounting includes them even when their minimum cost exceeds the provider budget.

- **Cloud tool budgets follow the API account's measured limits.** Anthropic and OpenAI token limits survive a restart, lower limits reported by refusals replace earlier measurements, and Override Model Limits accepts input tokens per minute alongside context and output.

- **Agents can use their own FTP profiles and mail accounts.** Regular agents also retain shared accounts; isolated agents continue to see only their own resources, and a running turn keeps the identity it started with. Incognito retains its existing privacy boundary.

- **Linux .deb installations keep the Chromium sandbox enabled.** AppImage fallback checks the setuid helper and its mount, and the Linux package includes the installation guide.

- **An AppImage running under an AppArmor profile that allows user namespaces keeps the Chromium sandbox.** Skales reads the profile it runs under at startup, and the Linux guide shows the profile line for the AppImage path.

- **A picture made with the image bar appears only once.** Google, Replicate and fal.ai results in the chat no longer show a second copy as a thumbnail below the answer.

- **A dropped Anthropic or Gemini stream no longer suggests a longer timeout.** The message names what can cut a streaming answer, such as the network, a proxy or antivirus web protection.

- **Temporary provider limits no longer leave acknowledgments and learning reviews paused.** They resume after the waiting period or when you switch outside the affected free tier. Limits reported after an answer has begun also pause these extra calls while keeping the text already received.

- **Skales IQ congestion messages use your selected language.** The waiting hint and available alternatives stay alongside the message.

- **Model lists refresh without disturbing other settings.** Reopening an unchanged catalogue keeps your existing preferences intact.

- **Learning history restores reliably from a backup made on another computer.** Backups also keep a consistent history while Skales is learning.

- **Rate-limit messages name the provider and explain your options.** When available, they show the account tier and retry time; after a free-tier refusal, acknowledgments and conversation reviews pause for that session.

- **Continuing an image question starts showing progress immediately.** The answer streams into the open conversation, including in a remote browser, and a failed start leaves the question ready to retry.

- **Image support follows the current model catalogue.** DeepSeek Flash can receive pictures, and a provider’s declared text-only models no longer inherit image support from their names.

- **Privacy Mode keeps your standing instructions out of cloud conversations on every surface.** This also applies to custom agents, Code, messengers and Buddy when instructions are placed at the top, and when a local model falls back to a cloud provider.

- **A background task that fails stops completely.** This also applies when it was allowed to run without a time limit. Folder triggers now report filesystem watcher failures in their existing schedule logs and can be restarted safely after the underlying problem is resolved.

- **Sub-agents ask you in the conversation when they need approval.** In Safe mode, a background helper that needs to write a file or run a command puts the question in the chat that started it and carries on after your answer. A helper that does not finish says why in its report.

- **NVIDIA NIM no longer offers or defaults to models NVIDIA has switched off.** Llama 3.3 70B and the other retired ids are gone from the list, a setting that still names one is sent as its current replacement, and a model NVIDIA retires later is named with its end-of-life notice and where to change it.

- **The setting "Keep new things only after my OK" is found by Settings search in every language.** Words like memory, approval or remember, and each language's own words for them, now lead to it.

- **When a provider reports an error mid-answer, Skales now shows that error instead of "the connection closed".** An overload such as NVIDIA's "Service temporarily overloaded (503)" is named with its status and text and retried after a short wait like any other 503; a stream the server ended and a connection that dropped each get their own sentence, and only a real timeout suggests raising the timeout.

- **A busy NVIDIA model that times out in NVIDIA's queue says so.** The 504 NVIDIA sends after about five minutes is named as its queue giving up, so nobody raises a timeout that cannot help.

- **Nemotron 3 Ultra and Super on NVIDIA get their real context window.** They were budgeted at 32K tokens, which compacted long tool-heavy conversations far too early.

- **Diagnostics explain a failed answer more clearly.** The report includes the provider's error and distinguishes an answer the server ended from a connection that dropped.


- **An answer on an old approval card no longer approves the next question.** A late answer from a phone or a second window is refused with a sentence instead of letting a different action through. An older Skales Mobile can answer the first question it sees in a task; after another question, the phone and the computer both say to update the app while the task keeps waiting, including after reconnecting or restarting.

- **Someone else in a group chat or a Spaces room can no longer change or delete what Skales knows about you.** A message from another person in a Telegram, Discord or WhatsApp group, or a task another room member gives your agent, is never learned from and cannot rewrite or remove a remembered topic, and an approval card raised by their message can only be confirmed by you.

- **Telegram answers each person in a group on their own.** Messages from different people that arrive at the same moment are no longer answered as one.

- **A conversation with a local model is not sent to a cloud model for the look-back.** Skales says it skipped that conversation for privacy instead of learning from it quietly.

- **What you remove on your phone is removed from the computer's copy too.** The phone's memory on a paired computer now follows it line for line, and what you already kept on the phone is not asked about a second time on the computer.

- **DeepSeek works again with the models DeepSeek retired.** A DeepSeek card, a fallback entry or an agent still set to the old chat, coder or reasoner model now runs on the current DeepSeek V4.1 Flash in the same mode as before: without thinking for chat and coder, with thinking for reasoner. The DeepSeek card says so beside the old model, and the model list offers the current Flash and V4 Pro models.
- **DeepSeek V4 turns show what they cost instead of "unknown".** The current Flash and Pro models are priced from DeepSeek's own price list, including the lower price for cached input and the half price outside DeepSeek's peak hours.
- **Motion videos with music or narration finish encoding.** The sound is now cut to the exact length of the picture; before, the encoder could wait on padded silence after the last frame until the render failed.
- **Motion videos longer than a minute keep their full length.** A 61-second composition was cut at 60 seconds without a word.
- **A failed render says why.** The message names the encoder's actual error instead of its statistics, and a failed composition check names its reason.
- **Project files shows a folder with many files as one card.** A render's frame dump no longer fills the panel with hundreds of empty rows.

- **Answers no longer show half-written tool calls or say the same thing twice.** A tool call the model was cut off in the middle of is removed from the answer, and it no longer flickers into view while the answer streams. A sentence, a block of sentences or a paragraph repeated word for word is shown once, unless you asked for the repetition.

- **A file Skales says it wrote is now checked on disk.** A file result confirms the saved file or says the write failed. If the assistant claims to have created a file without doing so, it is asked to finish the work and otherwise tells you the file is not confirmed.

- **A video render or a Flow PDF, PowerPoint or Word export that gets stuck is now stopped and explained.** Instead of standing unfinished with no file, it ends after a few minutes without progress and says which step it was on and how far it got.

- **Exporting a Skales Visual, an animated Type or a multi-scene Studio video to MP4 works again.** Earlier Visuals export too, and a page without animation support no longer stops the export.

- **Local AI no longer reads as disconnected while Ollama downloads a model.** The dashboard row says which model is downloading and how far it is, and testing the Ollama card during a download says the runtime is busy instead of unreachable.

- **A Flow project works in its own folder.** Its agent no longer lists, reads or copies other Flow projects unless you name one in your message or attach it with "Reference another project"; a refused step says why.

- **Stopping Code from a paired phone confirms when that task has stopped.** A delayed reply from an earlier task cannot clear a newer coding task or its waiting question.

- **Undo in Code reliably restores quick edits, including changes that keep the same file size.** Files you edited yourself after the turn are still kept and named instead of overwritten.

- **Iris keeps the full Voice settings button visible when there is room.** An empty spoken line no longer clips the button or causes unnecessary scrolling; short windows still let you scroll.
- **Keyboard activation in Iris acts on the focused control.** Space and Enter on recording, permission and settings buttons no longer start a microphone or open the text field; a configured alternate push-to-talk key and the original held-turn owner keep working. Repeating that key keeps the same turn, and releasing it after a settings change ends only the turn it opened.
- **Iris keeps its orbit and decisions reachable in short windows.** Long explanations and their buttons scroll together without covering the orbit; reopening, resizing and reloading preserve the conversation and its usable layout.

- **Iris recording and permission choices follow their explanation.** Retry, Discard and Voice settings stay in the same text flow when a notice wraps or an orbit opens, instead of covering the reason or becoming unclickable.

- **Stopping an answer no longer leaves an unfinished thought marker in the visible text.** The answer and its reasoning stay readable when reopened, exported or read aloud.

- **An Iris held key stops only the turn it opened.** Releasing the original key or leaving the window still works after changing push-to-talk settings; a later hands-free turn is no longer stopped by an older held press.

- **Releasing Iris push-to-talk ends a microphone start that is still waiting for permission or the device.** A late microphone or audio-context response can no longer open an unowned recorder or leave Stop waiting forever; the next turn remains usable.

- **A partial control-window failure describes the surface that failed.** A healthy frame or Stop bar is no longer described as invisible when only its neighbour could not load.
- **A missing control page now names its HTTP error.** A 404 or server error stays visible in the existing notification and tool-result paths until a healthy page and control bridge return, rather than opening a silent, unusable frame or Stop window.

- **The control frame covers the whole display on macOS.** Its window stays at the display origin instead of shifting below the menu bar, so the comet marks the actual desktop point and the bottom edge stays on screen; the Stop bar keeps its place inside the work area.

- **Computer-control window failures now name their cause.** A window that fails to load or stops responding says why in the existing notification and tool result. The reason stays until the window recovers; a delayed error from an earlier task cannot affect the next one.

- **The new local-provider checks and LM Studio errors use the familiar form of address.** French, Croatian, Russian and Turkish match the surrounding interface.

- **Flow voice and music choices show their translated labels in all twelve languages.** The composer uses the same familiar wording as the rest of Settings.

- **Motion exports keep looping audio and long end fades as heard in the preview.** A short music bed repeats through its timeline, and a fade longer than the clip reaches silence at the same moment.

- **The control frame and Stop remain visible when screen recording permission is denied.** You can still stop the task, and taking a screenshot explains which permission is missing.

- **Flow describes all eleven design modes when explaining what it can make.** Film and narrated E-Learning courses are included alongside the other existing modes.

- **Flow Motion renders projects with their own fonts, animations and video clips.** The export and contact sheet include the project's files just as the preview does.

- **A Motion render no longer rejects a frame whose picture has not changed.** A still frame can be revisited reliably while an unexpected visible change is still reported.

- **Diagnostics distinguish errors from the current version from older ones.** An error left by an earlier installation is listed separately instead of blamed on the version you are running.

- **When the agent cannot draw its on-screen control frame, it says so instead of clicking blind.** A missing display or a window that failed to open names itself as a toast and in the agent's own reply, rather than leaving a silent gap between what the agent believes is visible and what the user actually sees.

- **Installing a plugin package that only partly writes to disk is no longer reported as a successful install.** A brand-new install that could not finish is removed instead of left behind as a broken entry; updating an existing plugin that cannot finish leaves the working version in place and says what did not arrive.

- **A sub-agent that keeps repeating itself now stops and says why.** A helper stuck repeating the same unsuccessful work no longer leaves you waiting without an explanation.

- **Push to talk now does what Settings says it does.** Choose off, hold, or toggle, and the key you set is the one that actually starts and stops Iris Orbit's microphone - and the Iris window now shows which key and which mode are active.

- **Completed replies stay visible even when the model never separates its thinking from its answer.** Interrupted streams keep their text, saved affected replies are restored when reopened, and clearly separated thinking remains folded.

- **The Business page says what its provider figure counts.** The number is the providers people actually use with Skales, custom endpoints included, and it is now labelled as providers in use in every language instead of reading like the list you can pick from.

- **Flow's live preview shows the page as soon as it is written.** It used to stay on "Building your preview" until the whole turn had finished, and sometimes until the window was reloaded; it now shows the page once the agent's files stand still and catches files that settle just after the turn ends, without restarting the preview while the agent is still writing.

- **Flow follows the brief over the project's defaults.** A length the brief names for the whole piece now wins over a duration preset you did not change in the composer (one you picked still stands), and the finished piece speaks the language the brief is written in, even when the brief names an audience somewhere else or the app runs in another language.

- **Pictures Skales generates for a Flow page show up in the preview.** A missing picture is named and the agent is asked to repair it.

- **Code roles ask you instead of giving up.** When the Architect or the Reviewer needs your approval for a step, for example running a script, the question now appears on the session's approval card with the role named on it, under the same rules as the main run in Auto; it no longer ends the chain with "there was nobody to ask".

- **Skales Code no longer creates a near-duplicate of a file that is already there.** When a similarly named file already exists, the agent uses it unless a second file is wanted.

- **An approval you already answered on the phone no longer comes back as a second card.** When a session was refreshed on the phone at the moment you approved a step, the phone could show the same approval again after the step had already run; it now only ever shows a question that is still open.

- **A paired phone reconnects on its own after the computer restarts.** The computer now rejoins its paired phones from its own background heartbeat as soon as it is running again, instead of waiting for the app window to open, so the phone no longer shows the computer as offline until it is paired again.

- **The look-back no longer competes with your next message on a local model.** When the helper model runs on your computer, it waits until nothing else is running and the conversation has been quiet for a minute. It also looks first at the procedures the conversation actually used, and Stop or deleting the conversation ends it without keeping anything.

- **A development team member installed earlier gets the tools its role gained since.** A preset role's newer tools, such as section search for the read-only roles, reach members that were installed before; nothing they already had is taken away, and an agent whose tools you picked yourself keeps exactly your list.

### Changed

- **Burned-in subtitles of a landscape film sit higher.** Their centre line now keeps about 200 px above the bottom of a 1080p frame.

- **Code Roles also govern queued phone and relay messages and Code sessions handed to Iris.** A queued task waits for the whole Architect–Coder–Reviewer sequence, survives restart, and starts through the same session setting. Stopping leaves waiting tasks available to send explicitly, using the current role setting even for older waiting messages.

- **PetDex and custom pixel skins have been removed.** Desktop Buddy keeps its Skales, Bubbles and Capy skins. Saved pixel-skin selections fall back safely; imported files stay on disk. Old PetDex links return home before the app renders, including nested links; settings search no longer advertises pixel skins.

- **A plugin tool that can reach the internet asks before each call, and the Plugins page says which ones do.** A scheduled plugin run leaves such a call as a card on the plugin's page, and the page also names any tool in a plugin's list that plugins may not use, such as starting helper runs.
