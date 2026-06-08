IDK MACHINE

Begin with a better question.

IDK MACHINE is a one-button prompt engine for strange, usable idea seeds.

It completes the phrase WHAT IF YOU... with a prompt that can become a scene, essay hook, image brief, game mechanic, story rule, first line, worldbuilding seed, or useful wrong turn.

It does not finish the work.

It gives the next question a sharper angle.

WHAT IT IS

IDK MACHINE is a self-contained browser app built as a single HTML file.

It contains a curated deck of 999 prompt cards. Each card has a theme and a prompt. The prompts are designed to be strange enough to break a blank page, but clear enough to use immediately.

The app is not a random nonsense generator.

It is a practical disturbance machine.

It gives the user a starting point, not an answer.

CURRENT STATUS

App: IDK MACHINE
Deck size: 999 cards
Format: single-file HTML
Mechanism: one-button random prompt draw
Storage: local browser only
Backend: none
Build step: none
Version status: expanded 999-card deck

CORE INTERACTION

The app has one primary action:

WHAT IF YOU...

Each press selects one random card from the internal deck and displays it as a usable prompt.

Secondary controls:

COPY copies the current prompt.

CLEAR resets the display.

ABOUT opens the app’s information panel.

RETURN closes the ABOUT panel and returns to the main prompt view.

INTENDED USE

IDK MACHINE is useful for:

creative prompts
fiction seeds
visual briefs
essay hooks
worldbuilding
game mechanics
dialogue starters
story exercises
writing warm-ups
image-generation ideas
conceptual experiments
escaping a blank page
finding an unexpected angle

A card can be used as:

a title
a first line
a scene
a rule
a question
a constraint
a drawing prompt
a game mechanic
a miniature world
a writing exercise
a paragraph starter
a strange object to think with

CONTENT PRINCIPLE

A good IDK MACHINE card should be strange, but usable.

It should not be vague.
It should not be random for its own sake.
It should not sound like normal advice.
It should not become BADVICE.
It should not become SAID IT.
It should not become a joke with no practical handle.

The best cards combine:

a familiar object or situation
a slightly impossible twist
a clear instruction for what to do next

Example:

turn your unread messages into a map? Make the oldest thread the road nobody wants to take.

That works because the object is familiar, the twist is strange, and the prompt immediately suggests a scene, image, story, or essay.

STYLE RULES FOR FUTURE CARDS

Keep the prompt clear.

Start from something recognisable.

Add one strange pressure.

Make the user know what to do with it.

Prefer concrete objects over abstract moods.

Prefer scenes over slogans.

Prefer useful weirdness over decorative weirdness.

Avoid overlong metaphors.

Avoid pure surrealism with no handle.

Avoid generic “write about your feelings” prompts.

Avoid cards that are only clever, but not usable.

Avoid repeating the same object too often.

Avoid cards that require explanation before they can be used.

The card should feel like a door, not a fog machine.

GOOD CARD TEST

Before adding a new card, ask:

Can this become a scene immediately?

Can this become an image?

Can this become a short story, essay, game rule, or dialogue?

Is the object or situation relatable?

Is the twist fresh but understandable?

Does the second sentence sharpen the task?

Would this help someone who has no idea what to make?

Does it still sound like IDK MACHINE?

DECK STRUCTURE

The deck lives inside the JavaScript array named CARDS.

Each card has two fields:

theme
text

The theme is a short label.

The text is the full prompt.

Example structure:

{
"theme": "Unread Messages",
"text": "turn your unread messages into a map? Make the oldest thread the road nobody wants to take."
}

The app’s button already supplies the framing phrase:

WHAT IF YOU...

So each card text should continue naturally after that phrase.

FILES

The app can be used as a standalone file:

index.html

It can also be placed inside a folder on a static site:

idk-machine/index.html

No extra files are required.

DEPLOYMENT

IDK MACHINE is static.

To publish it, upload the HTML file to any static web host or to a folder inside an existing website.

Recommended structure inside the SPARK TOOLS site:

spark-tools/
idk-machine/
index.html

Then the live path should be:

/spark-tools/idk-machine/

The app does not require a database, server code, package manager, build tool, or installation step.

UPDATING THE DECK

After adding or editing cards, check that:

The total card count is correct.

There are no duplicate card texts.

Every card has both theme and text.

Every theme is a non-empty string.

Every text field is a non-empty string.

The JavaScript still passes syntax checking.

The IDEA SEEDS counter reflects the current deck size.

The metadata count reflects the current deck size.

The app still loads, draws prompts, copies text, clears text, and opens and closes the ABOUT panel.

FINAL NOTE

IDK MACHINE works best when the prompt is neither too obvious nor too obscure.

It should make the user think:

I do not know exactly what this is yet, but I can start.

That is the point.

The machine does not answer the question.

It makes the question worth following.
