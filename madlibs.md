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
            placeholder="plural noun" />
        </div>
        <input type="submit" />
    </form>
</section>

<!-- The madlib we will populate -->
<section id="madlib">
    <!-- we wrap the mad lib in a paragraph tag, inside of this we will need something to place the text into that the user submits. I am using a span because it displays on the page inline instead of something that would cause a linebreak to happen, such as another p tag or div.  The id is a tag we can use to specify which field this is, I am naming it the same as the name on the form input to keep things simple, it could be anything as long as it is unique. -->
    <p>I said <span id="adjective1"></span></p>
</section>

<!-- We will be putting code inside of script to handle the logic of how to handle the madlib population -->
<script>

</script>