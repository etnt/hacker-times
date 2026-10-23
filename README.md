# Hacker News - Front Page

Let's explore if we can make self-contained HTML page with the
necessary Javascript included to make a cool Newspaper Front Page
out of the 10 (currently) top news over at Hacker News ( https://news.ycombinator.com/news ).

A real newspaper usually consists of the following:

The Header Area

• Masthead (or Nameplate): The large, distinctive title of the newspaper printed at the top of the front page (e.g., The New York Times).
• Dateline / Folio: The line right below or near the masthead that contains the publication date, volume number, and price.
• Ears: The small corners on either side of the masthead often used for weather forecasts, edition names, or small advertisements.

Main Content & Layout Blocks

• Lead Story: The most important news article of the day, typically placed at the top right of the page with the largest headline.
• Columns: The vertical layout zones that split the text to make it readable. Newspaper pages are traditionally divided into 6 columns.
• Fold: The physical crease where the paper is folded in half. The most critical, attention-grabbing content is kept "above the fold" to be visible on newsstands.
• Sidebar: A shorter, self-contained article placed next to a major story, providing closely related background information or a human-interest angle.

Visual Elements

• Banner Headline (or Streamer): A massive headline that stretches all the way across the top of the front page, reserved for major breaking news.
• Teasers (or Skyboxes): Strips or promotional boxes at the very top of the page (often above the masthead) that preview exciting stories found inside the paper.
• Photo / Graphic Block: The prominent visual focal point of the page, usually tied to the lead story.
• Caption (or Cutline): The explanatory text directly underneath or beside a photograph.

Small Structural Anchors

• Credit Line: A small line of text giving credit to the photographer or news agency (like AP or Reuters) for an image.
• Byline: The line at the beginning of an article that gives the writer's name.
• Jump Line: A directional line at the bottom of a front-page article instructing the reader where to continue reading (e.g., "Continued on Page A4").
• Index: A small directory table, usually near the bottom, listing where to find specific sections inside (e.g., Sports, Business, Obituaries).

Let's create something similar but using the news as presented via the hacker news API,
where the most upvoted news currently makes the biggest headlines.

Each news piece shown should show some text (truncated) with small icons that either opens up
a new browser tab with the original article, or pop-up a window with the comments made for that article.




## Usage

To run this app: Open `index.html` in a browser. Note that it needs internet access to fetch the Hacker News data from the internet.
