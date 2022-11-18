# html-cheatsheet
<!doctype html>
<html>
    <head>
        <title>HTML Tags Cheat Sheet</title>
    </head>
    <body>

        <h1 id="top-of-page">HTML Tags Cheat Sheet</h1>

       <h2>Headings</h2>
        <p>
            Headings from 'h1' to 'h6' identify blocks and sections.
        </p>
        <h2>Paragraphs</h2>
        <p>
            Paragraphs of text go in 'p' tags.
        </p>
        <h2>Lists</h2>
        <h3>Unordered Lists</h3>
        <p>
            Unordered lists are marked with bullet points and go in 'ul' tags
        </p>
        <h4>Types of Lists</h4>
        <ul>
            <li>Unordered lists ('ul')</li>
            <li>Ordered lists ('ol')</li>
        </ul>
        <h3>Ordered Lists</h3>
        <p>
            Ordered lists are numbered and go in 'ol' tags.
        </p>
        <h4>Polya's Problem Solving Framework</h4>
        <ol>
            <li>Understand the problem</li>
            <li>Come up with a plan</li>
            <li>Carry out a plan</li>
            <li>Go back and improve your solution</li>
        </ol>
        <h2>Anchors (i.e. links)</h2>
        <p>
            Anchor tags create links to other pages. The URL goes in the 'href'
       <a href="https://duckduckgo.com">
            Go to DuckDuckGo to search for more information.
       </a>
        </p>
        <p>
            Setting 'target="blank"' will open the link in a new window. See
            <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a" target="_blank">
                MDN
            </a>
            for more details
        </p>
        <p>
            Anchor tags can also create links to a new location on the same page.
            <a href="#top-of-page">
                Jump to the top of the page.
            </a>
        </p>
        <h2>Text Emphasis</h2>
        <h3>Italic</h3>
        <em>
            The 'em' element adds an extra emphasis to the text.
        </em>
        <h3>Bold</h3>
        <strong>
            You can also use the 'strong' element to emphasize text.
        </strong>
        <h2>Organizing Content with'div' and 'span'</h2>
            <h3>'div'</h3>
            <p>
                The 'div' element is a block element for container flow. Each 'div' will show up on a new line.
            </p>
            <div>1st div</div>
            <div>2nd div</div>
            <div>3rd div</div>
        <h3>'span'</h3>
        <p>
            The 'span' element is an inline element, there will be no line break between each 'span'.
        </p>
        <span>1st span</span>
        <span>2nd span</span>
        <span>3rd span</span>
        <h2>Breaking text using the `br` tag</h2>
    <p>
        In the twilight rain<br>
        these brilliant-hued hibiscus - <br>
        A loveley sunset<br>
    </p>
    </body>
</html>
