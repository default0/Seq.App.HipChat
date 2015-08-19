# Seq.App.HipChat

An app for Seq (http://getseq.net) that forwards messages to HipChat.

## Changes

### 1.1.0

- ([#3](https://github.com/stayhard/Seq.App.HipChat/pull/3)) Option for setting custom HipChat install base URL (thanks [ciwchris](https://github.com/ciwchris))
- ([#2](https://github.com/stayhard/Seq.App.HipChat/pull/2)) Links to Seq from HipChat messages are now compatible with Seq v2 (thanks [jerbri](https://github.com/jerbri))

## Building NuGet Package

From solution root, run:

- msbuild
- nuget pack ./Seq.App.HipChat/Seq.App.HipChat.nuspec