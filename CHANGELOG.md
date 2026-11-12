# What's new in WexStack

Every version installs over the previous one and keeps your data. The app offers updates by itself
(Settings → About → Check for updates). Download: **[wexstack.com/download](https://wexstack.com/download)**

---

## 0.5.0 — Trash, private messages, remote help

- **Project trash.** Deleting a project moves it to Trash for 30 days. *Project Library → Trash → Restore* brings it back for
  every member with its chat, tasks and history. Files on each PC are never deleted.
- **Private messages** with friends (*Teams → Message*), with unread counts and a notice when a message arrives.
- **Remote help.** *Teams → ⋯ → Remote help* lets one chosen person see your whole screen and use your mouse and keyboard.
  In a private call the sharer can *Give control*, and a viewer can *Request control*. A warning bar stays visible the whole
  time; *Stop control* or closing the window ends it at once.
- **Two people, one file.** Nothing is uploaded until you save. When you save, your edits and your teammate's queued edits are
  merged line by line: no lost lines, no duplicated code, line-ending (CRLF/LF) differences ignored, neighbouring lines
  merged. An editor that still had the old text when a teammate's change arrived no longer removes their lines.
  Only the very same line changed differently by both is kept as two versions for you to choose.
- **Notification sounds** — quiet and short: teammate online, files in/out, message, call or screen-share invite.
  *Settings → Appearance → Notification sounds*.
- Admin panel: payments that need attention, mark paid, cancel/refund, record a payment by hand, quick plan assignment,
  income charts.

## 0.4.1

- Notices at the bottom right are see-through and close by themselves (4 s, warnings 7 s, errors 10 s).

## 0.4.0 — Delete for everyone, friends, screen sharing

- **Delete a project for everyone** (owner, confirmed by typing the name). It disappears from every member's app at once;
  members can *Leave* instead. Right-click a project in the library.
- **Friends** on the Teams page: add by username, accept/decline, remove, block, online status.
- **Screen sharing** with *everyone in the project* or *only people you choose* (friends and teammates). Teammates get a
  notice and press *Watch*. Private shares open in their own window and end when the sharer leaves.
- Join a call **without a microphone** to watch and listen. Double-click a shared screen for full view.

## 0.3.9

- Fix: with "Windows language" selected, text no longer flickers between English and the chosen language.

## 0.3.8 — Languages and command palette

- **20 interface languages** (full Turkish; core texts in Azerbaijani, German, Spanish, French, Italian, Portuguese, Dutch,
  Polish, Russian, Ukrainian, Arabic, Persian, Hindi, Indonesian, Chinese, Japanese, Korean). Right-to-left for Arabic and Persian.
- Compact **Problems** panel: one-line summary, the first problems at a glance, *Show all*, errors/warnings filter, copy.
- **Ctrl+K** command palette: jump to any page, project or server, switch theme or language.

## 0.3.3 – 0.3.7 — Calls, server tools, terminal

- **Calls and screen sharing** in every project (direct, encrypted; relay server for strict networks).
- Servers: live monitoring bar, **server assistant** (disk, memory, updates, failed services, open databases, firewall,
  certificates) with one-click fixes, file checks after editing, **backups** of files and databases with daily schedule.
- **Upload to server** straight from a project.
- Project **terminal** tab (PowerShell in the project folder) and **Run from GitHub**.
- Update reminders become stronger the longer an update waits.

## 0.3.0 – 0.3.2 — Servers

- Your own Linux servers over SSH: terminal tabs, file manager with drag & drop and editor, tunnels.
- **One-click deploy** (secret scan first, only changed files uploaded, runs as a service, health check).
- **Domains with HTTPS** (Let's Encrypt) and **databases** (PostgreSQL, MySQL, MariaDB, MongoDB, Redis).
- **Share server access** with a teammate without a password; see who connected.

## 0.2.0 — Restore points

- Save the whole project (or chosen files) and go back to it later; automatic points every hour while files change;
  every restore can be undone.

## 0.1.x — The beginning

- Encrypted project sync between PCs, conflict handling that never overwrites anyone's work, local version store.
- Teams, invitations, roles, join requests; project chat and task board.
- **Smart Runtime:** run any local project with one click; **Problems** detection with file, line and fix suggestion.
- Per-user installer (no admin rights), tray icon, **automatic updates** (from 0.1.5).
- Free trial and plans; crypto payments (TRX).
