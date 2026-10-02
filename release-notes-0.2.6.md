Computer tasks can work in supported Mac apps without bringing their windows to the foreground. Progress, pause and stop controls stay inside Frankie. Repeated in-app consent prompts and the floating activity overlay have been removed; macOS still requires its system permissions.

Document tasks preserve the full observed original and retain it across steps. A supported text area can now be copied directly to Downloads when you request an exact .txt filename. This bounded export preserves Unicode and whitespace, refuses existing files, and verifies the saved bytes and SHA-256 before reporting success. The original stays unchanged.

Live acceptance on build 22: Frankie exported a 2,534-character workshop estimate in three background steps. Independent readback matched all 2,542 UTF-8 bytes and the reported hash, and the original remained unchanged. Focused native and planner checks passed 37 tests.

Known limits: this direct export supports complete plain text up to 8 KB. Rich-text Save As and some other app-specific controls cannot run in the background. This update is not complete beta feature sign-off.

Source: `7faa50f84b2a2dd34fe840b21da091c10e0c27cf` in AskFrankie V2. Version 0.2.6, build 22. App and DMG are Developer ID signed, notarized and stapled; the updater ZIP has a verified Sparkle signature.
