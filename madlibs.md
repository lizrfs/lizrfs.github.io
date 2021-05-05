<section id="user-input">
    <form method="get">
        <div>
            <label for="adjective1">Adjective</label>
            <input type="text" name="adjective1" placeholder="adjective" />
        </div>
        <div>
            <label for="plural-noun1">Plural Noun</label>
            <input type="text" name="plural-noun1"
            placeholder="Plural Noun" />
        </div>
        <div>
            <label for="noun1">Noun</label>
            <input type="text" name="noun1"
            placeholder="Noun" />
        </div>
        <div>
            <label for="adjective2">Adjective</label>
            <input type="text" name="adjective2"
            placeholder="Adjective" />
        </div>
        <div>
            <label for="part_of_the_body1">Part of the Body</label>
            <input type="text" name="part_of_the_body1"
            placeholder="Part of the Body" />
        </div>
        <div>
            <label for="adjective3">Adjective</label>
            <input type="text" name="adjective3"
            placeholder="Adjective" />
        </div>
        <div>
            <label for="plural-noun2">Plural Noun</label>
            <input type="text" name="plural-noun2"
            placeholder="Plural Noun" />
        </div>
        <div>
            <label for="part_of_the_body2">Part of the Body</label>
            <input type="text" name="part_of_the_body2"
            placeholder="Part of the Body" />
        </div>
        <div>
            <label for="adjective4">Adjective</label>
            <input type="text" name="adjective4"
            placeholder="Adjective" />
        </div>
        <div>
            <label for="adverb1">Adverb</label>
            <input type="text" name="adverb1"
            placeholder="Adverb" />
        </div>
        <div>
            <label for="noun2">Noun</label>
            <input type="text" name="noun2"
            placeholder="Noun" />
        </div>
        <div>
            <label for="part_of_the_body_-_plural">Part of the Body-Plural</label>
            <input type="text" name="part_of_the_body_-_plural"
            placeholder="Part of the Body-Plural" />
        </div>
        <div>
            <label for="adverb2">Adverb</label>
            <input type="text" name="adverb2"
            placeholder="Adverb" />
        </div>
        <input type="submit" />
    </form>
</section>

![maythe4th] (https://www.google.com/imgres?imgurl=https%3A%2F%2Fimages.squarespace-cdn.com%2Fcontent%2Fv1%2F561ee3d0e4b0f64d49ce3405%2F1553102574557-EL6KBSL4X9S0WGCTY2FW%2Fke17ZwdGBToddI8pDm48kGDpvalPb1SqHoCn1hwN0Y57gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmQPoRzxSr1hzN-vPBHt7YyLLXgctAyUJRqJUUGWVDK_ZzIgvsybGcZEPqUYiXY8im%2FMayTheFourth.jpg%3Fformat%3D1500w&imgrefurl=https%3A%2F%2Fwww.sjquiltmuseum.org%2Fevents%2F2019%2F3%2F20%2Fmay-the-4th-be-with-you-star-wars-day-at-sjmqt&tbnid=XOf9ss_EPe9SfM&vet=12ahUKEwjo6KGtrLHwAhX5qnIEHfWtB64QMygNegUIARD2AQ..i&docid=jPnJQTmxo2HeaM&w=1200&h=1200&q=may%20the%204th%20be%20with%20you&safe=active&client=safari&ved=2ahUKEwjo6KGtrLHwAhX5qnIEHfWtB64QMygNegUIARD2AQ)

<!-- The madlib we will populate -->
<section id="madlib">
    <!-- we wrap the mad lib in a paragraph tag, inside of this we will need something to place the text into that the user submits. I am using a span because it displays on the page inline instead of something that would cause a linebreak to happen, such as another p tag or div.  The id is a tag we can use to specify which field this is, I am naming it the same as the name on the form input to keep things simple, it could be anything as long as it is unique. -->
    <p>The Force is a mystical, <span id="adjective1"></span>. As Jedi Master Obi-Wan Kenobi once said, “The Force is an energy field, created by all living <span id="plural-noun1"></span>, that surrounds us, penetrates us, and binds the <span id="noun1"></span>." Using the power of the Force, a Jedi can do many <span id="adjective2"></span> things, like using the Force to exercise <span id="part_of_the_body1"></span> control over <span id="adjective3"></span>-minded <span id="plural_noun2"></span>. A Jedi can also use the Force to move objects with their <span id="part_of_the_body2"></span>. It doesn't matter how <span id="adjective4"></span> these objects are; it only matters how <span id="adverb1"></span> the Jedi believes in the Force. Most importantly, the Force teaches a Jedi to rely on their feelings. As Obi-Wan Kenobi told his student Luke <span id="noun2"></span>-Walker: "Your <span id="part_of_the_body_-_plural"></span> can deceive you. Don't trust them." Instead, a Jedi should <span id="adverb2"></span> trust the Force.</p>
</section>

<!-- We will be putting code inside of script to handle the logic of how to handle the madlib population -->
<script>

</script>