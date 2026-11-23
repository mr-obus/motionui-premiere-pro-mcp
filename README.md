# MotionUI for Premiere: Premiere Pro MCP server for Claude Code and Codex

MotionUI for Premiere is an MCP server for Adobe Premiere Pro. It gives Claude Code or Codex 33 tools in the project you have open: read footage and transcripts, cut, set markers, mix sound, color grade, add captions and export. Every new cut lands in a new sequence next to your original.

The server is part of the MotionUI app for Mac and Windows, made by HIVER in Lucerne, Switzerland. The app installs the Premiere plugin with Adobe's own installer and connects Claude Code or Codex for you: no config file to edit and no Node.js to install.

This repository holds documentation only. The source code is private.

Website: https://www.motionui.net/help/premiere-pro-mcp

## Free and Pro

Claude Code and Codex can use MotionUI's basic After Effects tools without a license: comps, layers, keyframes, easing, animation presets, basic text effects, rectangle rigs and frame renders. MotionUI Pro adds file import, the Figma import, sequencing, camera moves, cursors, Proximity, Pins&Grid, Matchcut, all text effects, reference analysis, scene review and all Premiere Pro tools.

Plans: https://www.motionui.net/pro

## Tools

33 tools in the current release (MotionUI for Premiere 2.0.2). All of them need MotionUI Pro, except `premiere_status`.

| Area | Tools |
|---|---|
| Project and reading | `premiere_status`, `premiere_media`, `premiere_sequence`, `premiere_open_sequence`, `premiere_playhead`, `premiere_save` |
| Transcripts | `premiere_transcribe`, `premiere_transcript` |
| Looking | `premiere_frame`, `premiere_source_frames`, `premiere_shots`, `premiere_compare` |
| Cutting | `premiere_new_sequence`, `premiere_assemble`, `premiere_place`, `premiere_remove_clips`, `premiere_markers`, `premiere_transform` |
| Color | `premiere_scopes`, `premiere_color`, `premiere_grade`, `premiere_match`, `premiere_look`, `premiere_window` |
| Captions | `premiere_captions` |
| Sound and tracks | `premiere_volume`, `premiere_fade`, `premiere_beats`, `premiere_tracks`, `premiere_copy_track` |
| Import and export | `premiere_import`, `premiere_import_ae`, `premiere_export` |

## Requirements

* Adobe Premiere Pro 2026 (version 26.0 or newer) on Mac or Windows
* The MotionUI app 2.0 or newer and MotionUI Pro
* Claude Code or Codex
* Optional: your own OpenAI API key for transcripts with the timing of every word

## Set it up

1. Download the MotionUI app: https://www.motionui.net/getting-started
2. In the Premiere tab of the app, click Install plugin. Restart Premiere Pro once.
3. In Premiere, open Window, then UXP Plugins, then MotionUI. Keep the panel open while the agent works.
4. In the Premiere tab, choose Connect next to Claude Code or Codex.
5. Start a new session and ask: "Which Premiere project is open?"

Full walkthrough: https://www.motionui.net/help/premiere-pro

## Clients

* Claude Code (terminal or the Code tab of the Claude desktop app)
* Codex

A regular Claude chat or a ChatGPT chat cannot reach Premiere.

## Compared with other Premiere Pro MCP servers

https://www.motionui.net/guides/premiere-pro-after-effects-mcp-servers

## License

Proprietary. Part of MotionUI by HIVER. No source code is published here.
