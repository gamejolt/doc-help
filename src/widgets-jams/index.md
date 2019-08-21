# Widgets

Widgets are pieces of placeholder code that are replaced by dynamic content. They start with `{%` and end with `%}`. In between goes the widget's name and any necessary parameters.

You can use widgets to enhance your jam pages with features that wouldn't otherwise be possible in <a href="../markdown-jams">Markdown</a> or simple HTML, such as a countdown timer or an activity feed.

## Countdown Timer

Shows a countdown timer indicating when the next period of your jam will hit. Timers help to dispel any confusion around timezones as they show the amount of time left.

- Before the jam has begun, the timer will count down to the start of the jam.
- While the jam is running, the timer will count down to the end of the jam.
- After the jam ends, if your jam has a voting period, the timer will count down to the end of the voting period.

_Note that after the jam is over, the timer will automatically disappear from where you've placed it, as there's nothing to count down to anymore._

#### Syntax

```
{% countdown %}
```

#### Notes

You can change the theme from light to dark in the theme customizer to make sure it fits your site's styling.

## Activity Feed

Displays a real time feed of various jam activity, including tweets, blog posts, screenshots, videos, announcements, etc.

#### Syntax

```
{% activity-feed %}
```

#### Notes

The activity feed will only show if it's turned on for your jam. This widget allows you to place it on any of your jam pages so you're not restricted to a page we choose.

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
