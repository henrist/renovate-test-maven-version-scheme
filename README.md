# renovate-test-maven-version-scheme

This is a test setup for showing how to override the `versionScheme`
property of Renovate Bot.

I had the problem that Renovate wanted to update to e.g.
`org.jetbrains.kotlinx:kotlinx-coroutines-core to v1.3.3-1.3.70-eap-42`,
while I wanted to stay on the normal release track (`v1.3.3`).

Some related documentation around this:

- https://github.com/renovatebot/renovate/blob/825c866757a4ab8dd525fd196bd5a3e9bc93445b/docs/usage/docker.md#version-compatibility
- https://docs.renovatebot.com/configuration-options/#versionscheme
