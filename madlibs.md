<section id="user-input">
    <form method="get">
        <div>
            <label for="adjective1">Adjective</label>
            <input type="text" name="adjective1" placeholder="adjective" />
        </div>
        <!-- Button for the user to click when submiting the form -->
        <input type="submit" />
        <div>
            <label for="plural-noun1">Plural Noun</label>
            <input type="text" name="plural-noun1"
            placeholder="Plural Noun" />
        </div>
        <input type="submit" />
        <div>
            <label for="noun1">Noun</label>
            <input type="text" name="noun1"
            placeholder="Noun" />
        </div>
        <input type="submit" />
        <div>
            <label for="adjective2">Adjective</label>
            <input type="text" name="adjective2"
            placeholder="Adjective" />
        </div>
        <input type="submit" />
        <div>
            <label for="part_of_the_body1">Part of the Body</label>
            <input type="text" name="part_of_the_body1"
            placeholder="Part of the Body" />
        </div>
        <input type="submit" />
        <div>
            <label for="adjective3">Adjective</label>
            <input type="text" name="adjective3"
            placeholder="Adjective" />
        </div>
        <input type="submit" />
        <div>
            <label for="plural-noun2">Plural Noun</label>
            <input type="text" name="plural-noun2"
            placeholder="Plural Noun" />
        </div>
        <input type="submit" />
        <div>
            <label for="part_of_the_body2">Part of the Body</label>
            <input type="text" name="part_of_the_body2"
            placeholder="Part of the Body" />
        </div>
        <input type="submit" />
        <div>
            <label for="adjective4">Adjective</label>
            <input type="text" name="adjective4"
            placeholder="Adjective" />
        </div>
        <input type="submit" />
        <div>
            <label for="adverb1">Adverb</label>
            <input type="text" name="adverb1"
            placeholder="Adverb" />
        </div>
        <input type="submit" />
        <div>
            <label for="noun2">Noun</label>
            <input type="text" name="noun2"
            placeholder="Noun" />
        </div>
        <input type="submit" />
        <div>
            <label for="part_of_the_body_-_plural">Part of the Body-Plural</label>
            <input type="text" name="part_of_the_body_-_plural"
            placeholder="Part of the Body-Plural" />
        </div>
        <input type="submit" />
        <div>
            <label for="adverb2">Adverb</label>
            <input type="text" name="adverb2"
            placeholder="Adverb" />
        </div>
        <input type="submit" />
    </form>
</section>

<!-- The madlib we will populate -->
<section id="madlib">
    <!-- we wrap the mad lib in a paragraph tag, inside of this we will need something to place the text into that the user submits. I am using a span because it displays on the page inline instead of something that would cause a linebreak to happen, such as another p tag or div.  The id is a tag we can use to specify which field this is, I am naming it the same as the name on the form input to keep things simple, it could be anything as long as it is unique. -->
    <p>The Force is a mystical, <span id="adjective1"></span></p>. As Jedi Master Obi-Wan Kenobi once said, “The Force is an energy field, created by all living <span id="plural-noun1"></span></p>, that surrounds us, penetrates us, and binds the <span id="noun1"></span></p>." Using the power of the Force, a Jedi can do many <span id="adjective2"></span></p> things, like using the Force to exercise <span id="part_of_the_body1"></span></p> control over <span id="adjective3"></span></p>-minded <span id="plural_noun2"></span></p>. A Jedi can also use the Force to move objects with their <span id="part_of_the_body2"></span></p>. It doesn't matter how <span id="adjective4"></span></p> these objects are; it only matters how <span id="adverb1"></span></p> the Jedi believes in the Force. Most importantly, the Force teaches a Jedi to rely on their feelings. As Obi-Wan Kenobi told his student Luke <span id="noun2"></span></p>-Walker: "Your <span id="part_of_the_body_-_plural"></span></p> can deceive you. Don't trust them." Instead, a Jedi should <span id="adverb2"></span></p> trust the Force.
</section>

<!-- We will be putting code inside of script to handle the logic of how to handle the madlib population -->
<script>

</script>