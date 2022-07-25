<p align="center">
  <a href="https://amplitude.com" target="_blank" align="center">
    <img src="https://static.amplitude.com/lightning/46c85bfd91905de8047f1ee65c7c93d6fa9ee6ea/static/media/amplitude-logo-with-text.4fb9e463.svg" width="280">
  </a>
  <br />
</p>

[![npm version](https://badge.fury.io/js/%40amplitude%2Fnode.svg)](https://badge.fury.io/js/%40amplitude%2Fnode)

# Announcement 📣
Amplitude is introducing a NEW [SDK for Node.js](https://www.npmjs.com/package/@amplitude/analytics-node) [BETA]. This new SDK provides improved developer experience, helps users instrument data more seamlessly and provide more control over data being instrumented using custom plugins.

To learn more about the new SDK, here are some useful links:

* NPM: https://www.npmjs.com/package/@amplitude/analytics-node
* GitHub: https://github.com/amplitude/Amplitude-TypeScript/tree/main/packages/analytics-node
* Documentation: https://www.docs.developers.amplitude.com/data/sdks/typescript-node

# Official Amplitude SDK for Node.js
This is Amplitude Node.js SDK written in Typescript, the 1st backend SDK for Amplitude. At this moment, we keep it minimal and simple because we want to give more thoughts over different customers' needs. Modularization and flexiblity will be the main priorities for this SDK. We would like to hear your ideas as well on how you plan on using this library!

## Amplitude and Ampli SDK
[Ampli SDK](https://developers.data.amplitude.com/ampli-sdk-overview/) is autogenerated library based on your pre-defined [tracking plan](https://developers.data.amplitude.com/what-is-a-tracking-plan). The Ampli SDK, is a lightweight wrapper over the Amplitude SDK that provides type-safety, supports linting, and enables features like input validation. The code replicates the spec in the Tracking Plan and enforces its rules and requirements. This repository is about **Amplitude SDK**. To learn more about Ampli SDK, please refer to the [Ampli Node](https://developers.data.amplitude.com/nodejs-ampli) and [examples](https://github.com/amplitude/ampli-examples).

## Installation and Quick Start
Please visit our :100:[Developer Center](https://developers.amplitude.com/docs/nodejs) for instructions on installing and using our the SDK.

## Check Out the Sub-Packages

In order of what might be good to read to get acquainted with the Node SDK:

- [(`@amplitude/node`)](https://github.com/amplitude/Amplitude-Node/tree/main/packages/node): The core Node SDK and a starting place for logging events in Node.js.
- [(`@amplitude/types`)](https://github.com/amplitude/Amplitude-Node/tree/main/packages/types): Contains our helper types and enums(What an event looks like, what to expect the response to look like). A resource for interfacing with the Node SDK.
- [(`@amplitude/identify`)](https://github.com/amplitude/Amplitude-Node/tree/main/packages/identify): A builder-type class that helps interface with the Identify API and the Node SDK. Use it to compose Identify events for both users and groups.
- [(`@amplitude/identity`)](https://github.com/amplitude/Amplitude-Node/tree/main/packages/identity): A helper class to store the "identity" (device + user ID) of a certain event or client.
- [(`@amplitude/utils`)](https://github.com/amplitude/Amplitude-Node/tree/main/packages/utils): A list of shared (mostly) polymorphic utilities across our javascript-based SDK's.
- [("@amplitude/eslint-config-typescript`)](https://github.com/amplitude/Amplitude-Node/tree/main/packages/eslint-config-typescript): The ESLint configuration shared across our repositories.
## Need Help?
If you have any problems or issues over our SDK, feel free to [create a github issue](https://github.com/amplitude/Amplitude-Node/issues/new) or submit a request on [Amplitude Help](https://help.amplitude.com/hc/en-us/requests/new).
