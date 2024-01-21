# alternate-you

Alternate You is an experiment that asks the question:

_how would you have turned out if you would have been born at the exact same time, but in a different place or to a different socio-economic background?_

It produces text and images that offer a glimpse of what an alternate version of you might look like.

The experiment works in two parts:

# 1: ChatGPT Alternate You generation

1. Paste the contents of `prompt.md` into [ChatGPT](https://chat.openai.com/) (GPT-4 preferred)
2. Give the required input to ChatGPT: name, birthplace, birth date, ethnicity, socio-economic background. See the input examples in `prompt.md`.
3. Type "Again" or "More" to have ChatGPT produce more Alternate Yous, or give it a new input person to start over with a different "character".

# 2: Alternate You visualization with Eden

1. Copy the `Image prompt` at the end of the ChatGPT output
2. Paste it in the [Eden prompt input](https://app.eden.art/create/creations)
3. Wait an see your Alternate You

## Possible Eden improvements

### Using face concept
Generate visualizations using a LoRa trained on images of you.


Alternate versions of Samuel (born 1994 in NYC, upper middle class), using a [LoRa trained on images of me](https://app.eden.art/creators/samzmann?conceptId=65ad726bc7e9dd341fa70391):

<figure>
  <img src="https://edenartlab-prod-data.s3.us-east-1.amazonaws.com/6abad4f690abc4d8736f1d9a68082841d844b48f10aff1a2095bbae1fdc5a5e0.jpg" width="200" />
  <figcaption>A photorealistic image of <concept> as Samuel Aminov at the present age of 30, reflecting a Chechen-born man who has dedicated his life to promoting peace and resolving conflicts in the tumultuous world of international diplomacy in 2024.</figcaption>
</figure>

<figure>
  <img src="https://edenartlab-prod-data.s3.us-east-1.amazonaws.com/e2c20b163a7a737d7b022cb6800d8080bbcccdc4a9e84d78fdd6b5539e9c459f.jpg" width="200" />
  <figcaption>Generate a photorealistic image of <concept> at the present age of 30, reflecting a Chinese man from humble beginnings who has become a key figure in climate change research and advocacy in China in 2024.<figcaption>
</figure>

### txt2vid

Generate a video that goes through all the life events.

**Janine Petrov (1942 - 1968)**


[Eden link](https://app.eden.art/creators/samzmann?creationId=65ad897ac7e9dd341fbfbe79)

[Raw video](https://edenartlab-prod-data.s3.us-east-1.amazonaws.com/62f3adb2f26dbf9396f2bde275f0f544196b23a6ea7061c8bb12ec36ae0ba1ed.mp4)

<video width="320" height="320" controls>
  <source src="https://edenartlab-prod-data.s3.us-east-1.amazonaws.com/62f3adb2f26dbf9396f2bde275f0f544196b23a6ea7061c8bb12ec36ae0ba1ed.mp4" type="video/mp4">
</video>

<details>
<summary>Parameters</summary>

<br>
<p>GPT input</p>
<pre>
- name: Janine
- birthplace: Marseille, France
- birth date: July 1942
- ethnicity: caucasian
- socio-economic background: lower class
</pre>

<p>GPT output</p>
<pre>
Janine Petrov (1942 - 1968)
👶 July 1942: Born in a small village near Stalingrad, USSR.
⚠️ 1943: Famine strikes, barely survives.
🚚 1957: Moves to Moscow, seeks work.
📚 1960: Enrolls in night school.
✊ 1962: Becomes an active political dissident.
🚨 1968: Arrested, dies in custody under mysterious circumstances.
</pre>

<p>Modified output for text2vid</p>
<pre>
A newborn baby girl, named Janine, lies in a simple, rustic wooden cradle. The background reveals a small, impoverished village near Stalingrad, USSR, during the 1940s. The scene is set against the backdrop of World War II, with worn-out buildings and a somber, war-torn atmosphere.

A one-year-old Janine appears malnourished and fragile, her tiny form accentuated by the sparse and dimly lit room around her. The room's bare walls and lack of furnishings highlight the severe conditions of the famine in the USSR during World War II.

Fifteen-year-old Janine, dressed in modest, slightly worn 1950s attire, stands alone at a bustling Moscow train station. She holds a small, well-used suitcase, her face a mix of hope and uncertainty, as people and trains move around her, capturing the busy city life contrasting with her rural upbringing.

An 18-year-old Janine, immersed in her studies, sits at a small table in a dimly lit, cramped room. Books and notes are spread out before her, illuminated by a single flickering light bulb, showing her intense focus and determination to learn amidst her challenging circumstances.

Twenty-year-old Janine is depicted as a fervent political dissident, speaking passionately in a secretive meeting. The room is shadowy, with listeners gathered closely, their faces reflecting a mix of fear and determination. Janine stands out with her expressive gestures and a look of defiance and courage.

A 26-year-old Janine, weary and resigned, is captured in a stark, dimly lit prison cell. The cold, barren walls and sparse furnishings emphasize the bleakness of her situation. Her expression is one of quiet despair, a stark contrast to her earlier resilience, capturing her final moments in mysterious custody.
</pre>
</details>

<br>

**Samuel Njoroge (1994 - Present)**

[Eden link](https://app.eden.art/creators/samzmann?creationId=65ad8dacc7e9dd341fc6b7a9)

[Raw video](https://edenartlab-prod-data.s3.us-east-1.amazonaws.com/4da6b90ef7f59e54cd7f3f62ea352e23525fb2640e77751144e6923818a3ca3c.mp4)

<video width="320" height="320" controls>
  <source src="https://edenartlab-prod-data.s3.us-east-1.amazonaws.com/4da6b90ef7f59e54cd7f3f62ea352e23525fb2640e77751144e6923818a3ca3c.mp4" type="video/mp4">
</video>

<details>
<summary>Parameters</summary>

<br>
<p>GPT input</p>
<pre>
name: Samuel
birthplace: New York City, USA
birth date: March 1994
ethnicity: Caucasian
socio-economic background: upper middle class
</pre>

<p>GPT output</p>
<pre>
👶 1994: Born in a dilapidated hut, sub-Saharan Africa.
🍲 1999: Scavenges food in a slum.
🔨 2010: Labors in a hazardous workshop.
🚔 2012: Involved in street crime.
🚓 2020: Incarcerated in a bleak cell.
</pre>

<p>Modified output for text2vid</p>
<pre>
A newborn Samuel, wrapped in a tattered blanket, lies in a makeshift crib in a small, dilapidated hut. The background reveals a poverty-stricken area in a rural village in sub-Saharan Africa, circa 1994. The room is bare and somber, with minimal furnishings, highlighting the stark reality of his impoverished beginnings.

A five-year-old Samuel, in worn-out clothing, is seen scavenging for food in a garbage-strewn alley of a crowded slum. The surroundings are chaotic and unhygienic, with narrow, dirty lanes and makeshift shelters, reflecting the harshness of his struggle for survival in the mid-1990s.

At the age of 16, Samuel is portrayed laboring in a hazardous, poorly lit workshop. He's wearing tattered work clothes, his face showing signs of fatigue and the harshness of child labor. The background is filled with rudimentary tools and machinery, symbolizing his life of hard labor in a developing country in the early 2010s.

An 18-year-old Samuel, looking gaunt and tired, is seen in a rundown urban setting, involved in petty street crime. The environment is gritty and dangerous, with graffiti-covered walls and a group of similarly rough-looking individuals, highlighting his descent into criminal activities for survival.

A 24-year-old Samuel, now visibly hardened and scarred, sits alone in a dim, cramped prison cell. The cell is stark and oppressive, with bare walls and minimal light, capturing his grim reality after years of hardship and eventual incarceration in a developing country's prison system by the early 2020s.
</pre>
</details>