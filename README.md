# Hurdle: Enhanced Wordle with Custom Challenges

**Hurdle** is an app that introduces customizable gameplay features in the popular game "Wordle" including variable word lengths, adjustable guess numbers, thematic word selections, and an "Alien Wordle" mode for increased difficulty. Additionally, it incorporates a reset function allowing players to start new games with current settings, enhancing user experience and replayability.

## Features

The following features are implemented:

- [x] User can change the number of letters per row (the length of the goal word)
- [x] User can change the numbers of rows on the board (how many guesses allowed)
- [x] User can select a new themed set to pull the goal word from
- [x] User can select "alien wordle", causing the goal word to change after each guess
- [x] App displays a reset button on the top left to reset the game (but make no changes to the settings)

## Video Walkthrough

 <div>
    <a href="https://www.loom.com/share/15ff04b388b64becaecf433e90a0d6ed">
    </a>
    <a href="https://www.loom.com/share/15ff04b388b64becaecf433e90a0d6ed">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/15ff04b388b64becaecf433e90a0d6ed-with-play.gif">
    </a>
  </div>

## Notes

While building the app, challenges included managing optional values safely to prevent crashes, casting data types correctly from the settings dictionary, and ensuring the UI updates correctly in response to setting changes. Implementing the "Alien Wordle" mode also required careful logic to reset the goal word without affecting other game settings.

## License

    Copyright [2024] [Pragnavi Ravuluri Sai Durga]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
