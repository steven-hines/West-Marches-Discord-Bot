# West-Marches-Discord-Bot
A discord bot utilizing the Google Sheets and JDA APIs to track a large-scale (200+ player) West Marches styled virtual tabletop roleplay game. The bot allows for character creation, marketplace generation, marketplace transactions with in-game currency, and several other features core to running a campaign of this scope.

## Code Example

TODO:

## Motivation

When playing in a high-frequency West Marches campaign with over 200+ players, multiple sessions in the same day, dozens of DMs and Guest-Dms, it became immediately obvious that some factor of automization would have to come into play. Moreover, unlike in home campaigns with people you know and trust, some measure of accountability and fairness would need to be core components. This means automating character rolls, and other events that might be taken on faith in a traditional, small campaign. In an effort to reduce the influence of bias on our campaign, we sought to automize several key random processes in a way that was both transparent and completely detached from any player, dm, or mod influence.

This project was pieces together primarily by stringing together the Java Discord API (JDA) and the Google Sheets API. The rationale behind using the JDA API was that the virtual tabletop campaign and underlying game sessions were largely coordinated and run through discord as the virtual tabletop (Fantasy Grounds) has no voip tools in place, meaning that having input and output from the bot largely run to our players all in the same place was of critical importance. The use of the Google Sheets API had the following rationales: 1) we needed something that could be easily editable and viewed by people without technical skills and by hand while the bot's functionality was being implemented, and 2) Google Sheets provides adequate (if somewhat lacking) version control that anyone, regardless of technical knowhow, can operate. 

## Installation

TODO: Provide code examples and explanations of how to get the project.

## Dependencies

TODO: Java 8, JDA, Google Sheets, etc. Logger?

## API Reference

TODO: Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

TODO: Describe and show how to run the tests with code examples.

## Contributing

If you want to contribute to the West Marches Discord Bot project, make sure to base your branch off of our development branch (or a feature-branch) and create your PR into that same branch. We will be rejecting any PRs between branches or into release branches!

It is also highly recommended to get in touch with the devs before opening Pull Requests (either through an issue or Discord). It is very possible that your change might already be in development or you missed something.

More information can be found at the wiki page: Contributing (TODO: insert link to wiki page)

## License

This project - and all the underlying code and intellectual property - is provided under the GNU General Public License Version 3. Please refer to the LICENSE file included with the repo for futher information.
