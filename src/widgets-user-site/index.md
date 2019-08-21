# Widgets

Widgets are pieces of placeholder code that are replaced by dynamic content. They start with `{%` and end with `%}`. In between goes the widget's name and any necessary parameters.

## User Bio

Simply includes your profile bio. You can use this to keep your content in sync with your bio.

#### Syntax

```
{% user-bio %}
```

## Game List

Shows a grid of thumbnails for all your games. They can be clicked to go to their Game Jolt game pages. If you have a Site for the game, it will instead go to its Site page.

#### Syntax

```
{% game-list %}
```

## YouTube Video

Embed a video from [YouTube](https://youtube.com).

#### Syntax

```
{% youtube videoID %}
```

#### Required Parameters

- **videoID**
  You can find the video ID at the end of the video's URL. For example, the YouTube video ID of `https://www.youtube.com/watch?v=dQw4w9WgXcQ` is `dQw4w9WgXcQ`.

#### Example

```
{% youtube dQw4w9WgXcQ %}
```

## Vimeo Video

Embed a video from [Vimeo](https://vimeo.com).

#### Syntax

```
{% vimeo videoID %}
```

#### Required Parameters

- **videoID**
  You can find the video ID at the end of video's URL. For example, the Vimeo video ID of `http://vimeo.com/2619976` is `2619976`.

#### Example

```
{% vimeo 2619976 %}
```

## SoundCloud Audio

Embed a [SoundCloud](http://soundcloud.com) audio clip.

#### Syntax

```
{% soundcloud clipID [color] %}
```

#### Required Parameters

- **clipID**
  Finding the audio clip's ID can be kind of tricky. Go to the clip's SoundCloud page, click the Share button, switch over to the Embed tab, and then search through the embed code for a piece of text that looks similar to `api.soundcloud.com/tracks/152931962`. The string of numbers at the end `152931962` is the ID.

#### Optional Parameters

- **color** | Example: `0066CC`
  You can choose the color of the audio player. Use standard color hex values. You can use a color picker like [this one](http://www.rapidtables.com/web/color/color-picker.htm) to find the value you want.

#### Examples

```
{% soundcloud 152931962 %}
```

```
{% soundcloud 152931962 0066CC %}
```
