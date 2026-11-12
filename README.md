# Country Draw

**Draw Countries From Memory. Test Your Geography Skills.**

[Country Draw](https://countrydraw.org/) is a free online geography drawing game that challenges you to recreate the outline of a randomly selected country from memory.

Instead of simply identifying countries on a map, you have to remember their actual shapes. Draw a country's borders by hand, submit your sketch, and compare it with the real geographic outline.

After each attempt, Country Draw evaluates your drawing using an accuracy score and detailed metrics, showing where your sketch matches the real country and where it goes beyond or falls short of the actual borders.

Whether you're a geography enthusiast, a student, a teacher, or someone who enjoys testing their knowledge of the world, Country Draw turns geography practice into a fun and interactive challenge.

**Play Online:** https://countrydraw.org/

---

## Table of Contents

- [Features](#features)
- [How to Play](#how-to-play)
- [Drawing and Scoring System](#drawing-and-scoring-system)
- [Understanding Your Results](#understanding-your-results)
- [Geographic Data](#geographic-data)
- [Supported Devices](#supported-devices)
- [Who Is Country Draw For?](#who-is-country-draw-for)
- [Learning Benefits](#learning-benefits)
- [Tips for Better Drawings](#tips-for-better-drawings)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Privacy and Accessibility](#privacy-and-accessibility)
- [Try Country Draw](#try-country-draw)

---

## Features

### 1. Random Country Selection

Every round begins with a randomly selected country.

Click **New Country** to receive a country name. The name is your only hint — there is no outline to trace before you start drawing.

This makes every round a genuine test of your geographic memory rather than a simple tracing exercise.

### 2. Freehand Country Drawing

Draw the country's outline from memory using your mouse, finger, or stylus.

- Click and drag on desktop.
- Draw directly with your finger on mobile devices.
- Use a stylus on supported devices.
- Release and start another stroke to restart your attempt.

The goal is to recreate the country's recognizable silhouette, including its major curves, peninsulas, indentations, coastlines, and land borders.

### 3. Instant Drawing Evaluation

Once you finish your drawing, Country Draw compares your sketch with the actual geographic outline.

Your result includes:

- An overall accuracy score.
- A missed-area rate.
- Inside coverage.
- Outside rate.
- A visual comparison of your sketch and the real border.

You can see more than just a number: the color-coded result highlights the areas you reproduced correctly and the regions where your drawing differs from the reference.

### 4. Shape-Only Scoring

The scoring system automatically scales and centers your sketch to match the country's actual area before evaluating it.

This means:

- Drawing larger does not improve your score.
- Drawing smaller does not reduce your score.
- An off-center drawing is not automatically penalized.
- Shape and proportions are what matter.

The goal is to measure how accurately you remember the country's shape, not how well you position or size your drawing on the canvas.

### 5. Detailed Accuracy Metrics

Country Draw uses multiple geographic comparison metrics to explain your performance.

Instead of relying on a vague visual impression, the game measures how closely your drawing overlaps the actual country outline.

### 6. Authentic Geographic Borders

The reference country outlines come from the Natural Earth Admin 0 — Countries dataset at 1:110m scale.

This means the game evaluates your drawings against real geographic border data rather than simplified, hand-created approximations.

### 7. Vintage Cartographer Design

Country Draw features a distinctive cartography-inspired visual style.

Its interface uses:
- Paper-like textures.
- Ink-style drawing strokes.
- A hand-drawn grid.
- A vintage map worksheet aesthetic.

The design makes each round feel like sketching in a traditional geography notebook.

### 8. No Registration or Downloads

Country Draw is free to play directly in your browser.

- No account required.
- No registration.
- No software installation.
- No payment required.
- No downloads needed to start playing.

Open the website and begin drawing.

---

## How to Play

Playing Country Draw is simple. Each round follows three steps.

### Step 1 — Choose a Random Country

Visit [countrydraw.org](https://countrydraw.org/) and click **New Country**.

The game selects a country at random and displays its name.

Your challenge is to remember what the country looks like without using a reference outline.

### Step 2 — Draw the Country Outline

Use your mouse, finger, or stylus to draw the country's shape on the canvas.

Try to reproduce its overall silhouette, paying attention to:

- The general proportions.
- Major coastal curves.
- Peninsulas and protrusions.
- Inland borders.
- Distinctive indentations.

Your drawing should be made from memory rather than copied from an existing map.

### Step 3 — Compare Your Drawing

Click **Finish Drawing** to submit your attempt.

Country Draw then overlays your sketch with the real geographic outline and calculates your accuracy.

Review your score and the color-coded map to understand which parts you remembered correctly and which parts need improvement.

---

## Drawing and Scoring System

Country Draw evaluates your sketch using a shape-comparison approach based on Intersection over Union (IoU).

Before calculating the score, the drawing is automatically scaled and centered to match the actual area of the selected country.

The normalized drawing is then compared with the reference shape.

### 1. Score (IoU)

**Intersection over Union (IoU)** is the main accuracy metric.

It measures the overlap between your drawing and the real country outline, divided by the total area covered by either shape.

Conceptually:

```text
IoU = Intersection Area / Union Area
```

A higher IoU score means your drawing more closely matches the actual country.

The result is displayed as a percentage.

### 2. Missed Rate

Missed Rate measures the proportion of the real country's area that your drawing failed to cover.

A lower missed rate means you captured more of the country's actual territory.

For example, if your sketch leaves out a large peninsula or a significant section of the country, the missed rate will reflect that difference.

### 3. Inside Coverage

Inside Coverage measures how much of the actual country area is also covered by your drawing.

A higher value means you successfully captured more of the country's real shape.

This metric helps identify whether you remembered the overall extent of the country.

### 4. Outside Rate

Outside Rate measures the proportion of your drawing that extends beyond the actual country border.

A high outside rate indicates that your sketch includes areas that do not belong to the country.

This is particularly useful for identifying inaccurate bulges, oversized peninsulas, or misplaced boundaries.

---

## Understanding Your Results

After finishing a round, Country Draw displays a color-coded comparison.

The result distinguishes four important visual elements:

| Visual Element | Meaning |
|---|---|
| Hit | The area where your sketch overlaps the actual country |
| Overshoot | The area you drew outside the real country boundary |
| Missed | The real country area that your drawing failed to cover |
| Reference Border | The dashed outline showing the actual geographic shape |

These visual indicators make it easier to understand why your drawing received its score.

For example:

- A high Hit area means you remembered the country's shape well.
- A large Overshoot area means your drawing extended beyond the real border.
- A large Missed area means you left out important parts of the country.
- A close match with the Reference Border indicates accurate proportions and contours.

### Why Use IoU?

IoU is a widely used metric in fields such as:

- Cartography.
- Remote sensing.
- Computer vision.
- Image segmentation.

It provides an objective way to measure the overlap between two shapes.

Country Draw applies this concept to geography drawing, turning a freehand sketch into a measurable accuracy result.

---

## Geographic Data

Country Draw uses real geographic data rather than manually drawn reference shapes.

Its country borders come from:

**Natural Earth — Admin 0 Countries, 1:110m scale**

Natural Earth is a public-domain geographic dataset designed for world mapping and cartographic applications.

Using this dataset allows Country Draw to compare player drawings against genuine country outlines.

**Data source:** [Natural Earth](https://www.naturalearthdata.com/)

The geographic reference includes coastlines and land borders, so both contribute to the shape being evaluated.

---

## Supported Devices

Country Draw works across common devices and input methods.

| Device | Drawing Method |
|---|---|
| Desktop computers | Mouse |
| Laptops | Mouse or trackpad |
| Smartphones | Touchscreen |
| Tablets | Touchscreen |
| Stylus-enabled devices | Digital pen or stylus |

The drawing canvas adapts to different screen sizes and input methods.

On mobile devices, the drawing surface is designed to prevent unwanted page scrolling while you sketch.

You can play on iOS, Android, tablets, and desktop browsers without installing a separate application.

---

## Who Is Country Draw For?

### Geography Enthusiasts

Test how well you actually know the shapes of countries around the world.

Even if you can identify countries on a labeled map, drawing them from memory is a much more demanding challenge.

### Students

Use Country Draw as an interactive geography exercise.

It can help students become more familiar with:
- Country outlines.
- Continental geography.
- Coastlines.
- International borders.
- The relative shapes of neighboring countries.

### Teachers and Educators

Country Draw can be used as a classroom activity or an informal geography challenge.

Teachers can use it to encourage active participation and help students think about geographic shapes rather than simply memorizing country names.

### Quiz and Trivia Fans

If you enjoy geography quizzes, map challenges, and general-knowledge games, Country Draw offers a different way to test your knowledge.

### Casual Players

You do not need to be a geography expert.

Start with familiar countries and gradually challenge yourself with countries whose outlines are less familiar.

---

## Learning Benefits

### Active Recall

Country Draw requires you to retrieve geographic information from memory rather than recognize an answer presented on a map.

You must actively reconstruct the shape of a country.

### Better Spatial Awareness

Repeatedly drawing different countries can help develop a stronger mental picture of how countries are shaped and positioned around the world.

### Understanding Geographic Proportions

The game encourages you to think about the relative width, length, curves, and distinctive features of country outlines.

### Learning from Mistakes

The visual scoring system helps you identify specific errors instead of simply telling you whether your answer was right or wrong.

You can use the feedback to improve your mental map over repeated attempts.

---

## Tips for Better Drawings

Want to improve your Country Draw scores? Try these techniques.

### 1. Start with the Overall Silhouette

Do not focus on tiny details immediately.

First, remember the country's general shape:
- Is it wide or narrow?
- Is it roughly circular or elongated?
- Does it have a distinctive peninsula?
- Are there major indentations along its coastline?

Getting the overall silhouette right is a good starting point.

### 2. Pay Attention to Proportions

Think about the relative width and height of the country.

A country that is long and narrow should not be drawn as a compact shape, even if its general outline looks familiar.

### 3. Remember Distinctive Features

Some countries are recognizable because of one or two major geographic features.

Pay special attention to:
- Large peninsulas.
- Narrow extensions.
- Major coastal bends.
- Large bays and indentations.
- Unusual border shapes.

### 4. Consider Both Coastlines and Land Borders

The game evaluates the complete country shape.

Do not focus only on the coastline. Land borders also contribute to the outline being measured.

### 5. Learn from the Color-Coded Feedback

After each round, examine the Hit, Overshoot, and Missed areas.

This gives you a clearer understanding of which geographic features you remembered correctly and which ones need more attention.

---

## Frequently Asked Questions

### What is Country Draw?

Country Draw is a free online geography game where you draw the outline of a randomly selected country from memory and compare your sketch with its real geographic border.

### Is Country Draw free?

Yes. The website describes the game as completely free to play, with no registration, download, or payment required.

### Do I need to create an account?

No. You can open the website and start playing immediately.

### How does the game choose a country?

Click **New Country** to receive a randomly selected country.

### Can I draw on my phone?

Yes. Country Draw supports touchscreen input on smartphones and tablets, as well as mouse and stylus input on desktop devices.

### How is my drawing scored?

Your sketch is automatically scaled and centered to match the country's actual area. It is then compared with the real geographic outline using IoU and additional metrics.

### Does drawing a bigger country improve my score?

No. The game normalizes the size and position of your sketch before scoring.

Only the accuracy of the shape and its proportions affect the result.

### What does IoU mean?

IoU stands for Intersection over Union.

It measures the area shared by your drawing and the actual country outline relative to the total area covered by both shapes.

A higher IoU score indicates a closer match.

### What is Missed Rate?

Missed Rate indicates how much of the actual country area your sketch failed to cover.

### What is Outside Rate?

Outside Rate indicates how much of your drawing extends beyond the real country boundary.

### Where do the country outlines come from?

The game uses the Natural Earth Admin 0 — Countries dataset at 1:110m scale, which is public-domain geographic data.

### Is Country Draw useful for learning geography?

Yes. Drawing countries from memory encourages active recall and helps develop a better mental understanding of country shapes and geographic relationships.

---

## Privacy and Accessibility

Country Draw is designed to be easy to access.

- **Browser-based:** Play directly on the website.
- **No registration:** No account is needed.
- **No installation:** No application download is required.
- **Multiple input methods:** Supports mouse, touch, and stylus drawing.
- **Mobile-friendly:** Works on phones and tablets.
- **Language options:** The website provides English and German interfaces.

For additional information, visit the website's [Privacy Policy](https://countrydraw.org/privacy) and [Terms of Service](https://countrydraw.org/terms).

---

## Try Country Draw

Ready to test your mental map of the world?

Visit the website, pick a random country, and see how accurately you can recreate its outline from memory.

**Play now: https://countrydraw.org/**

No sign-up. No downloads. Just geography, memory, and drawing.

---

## Disclaimer

Country Draw is an educational and entertainment-oriented geography game.

Its scoring system evaluates the similarity between a player's drawing and the geographic reference outline. The score is intended as a gameplay and learning metric, not an official measurement of geographic or cartographic expertise.

Country boundary data is sourced from Natural Earth, a public-domain geographic dataset.

---

**Country Draw — Draw Countries From Memory. Discover How Well You Know the World.**
